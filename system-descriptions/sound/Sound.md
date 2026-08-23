---
title: Sound
description: How sound works in LobCorp
published: true
date: 2026-08-23T22:18:58.459Z
tags: 
editor: markdown
dateCreated: 2026-08-23T22:18:58.459Z
---

# Sound

This page provides an overview of how Lobotomy Corporation scripts handle sounds. For a more detailed description of sound in Unity, see also [their documention for AudioSource](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioSource.html) and [AudioListener](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioListener.html).

## Sound in Unity
Sound in Lobotomy Corporation is produced by Unity AudioSources playing AudioClips and listened to by a Unity AudioListener. 

### AudioListener
The AudioListener "hears" sounds and plays them through the speakers. In LobCorp (and most games), the AudioListener is attached to the camera, and sounds are heard as though the player is at the position of the AudioListener. This means, for example, that sounds played left of the camera are played in the left ear, and sounds played further from the camera are played quieter. A scene is only allowed to have one AudioListener, so it is required that the existing one is used.

The AudioListener also has controls for volume, which are affected by the sound settings. When the master volume is changed, it affects the volume of the AudioListener, rather than any of the audio sources directly.

More information about AudioListeners can be found at the [Unity 2017.4 documentation for AudioListener](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioListener.html).

### AudioSource
AudioSources are sources of sounds, played at a point in the game space. They have a few parameters which can be changed:
- Volume;
- Pitch;
- Loop mode, which determines whether the sound should play once or repeat when finished;
- [AudioRolloffMode](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioRolloffMode.html), which affects how sounds get quieter as the AudioListener gets further away;
- Minimum and maximum distance, which affect the AudioRolloffMode;
- Clip time, which determines what time in the sound file the AudioSource should play.

A single AudioSource can play multiple AudioClips at once using `AudioSource::PlayOneShot(AudioClip)`.

For a more complete list of properties and methods, see the [Unity 2017.4 documentation for AudioSource](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioSource.html).

### AudioClip
AudioClips contain the audio data to be played through AudioSources. They usually represent sound files loaded from the game's data, and cannot be altered. All changes to the sound (pitch, volume, speed, start time, etc.) are done through the AudioSource component.

More information can be found at the [Unity 2017.4 documentation for AudioClip](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioClip.html).

## SoundEffectPlayer
The SoundEffectPlayer object is how almost[^soundeffectplayer-exceptions] all sounds in Lobotomy Corporation are played. The SoundEffectPlayer class contains definitions for PlayOnce and Play, which create a new SoundEffectPlayer object from a Prefab that plays a sound from a file and is destroyed once done[^performance].

[^soundeffectplayer-exceptions]: Not all sounds are played using SoundEffectPlayer objects. Notably, the music, trumpet sounds, and UI sounds use a completely different method, described above. Additionally, some specific abnormalities (such as [Amber Dawn](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Dawn/BugDawnAnim)) play sounds directly through an AudioSource.

[^performance]: Creating and destroying game objects can have a performance hit. An AudioSource on the game object making sound, using the main camera's `z` position, is almost always a perfectly sufficient way to play sound without the overhead of loading, creating, updating, and subsequently destroying a SoundEffectPlayer.

Each SoundEffectPlayer has an AudioSource called `src` which plays an AudioClip. SoundEffectPlayers created with PlayOnce play the AudioClip once and are destroyed once the clip ends. SoundEffectPlayers created with Play play the AudioClip on loop until stopped or destroyed. There are several definitions for PlayOnce and Play which allow changing the pitch, AudioRolloffMode, or volume, though frequently scripts will directly modify the properties of `src` instead[^direct-modification].

[^direct-modification]: Scripts which directly modify the properties of the AudioSource may change a sound to loop or not loop, regardless of whether PlayOnce or Play was used.

All SoundEffectPlayers are initially[^zpos-exceptions] created at the same `z` coordinate as the camera, since the game is mostly 2D.

[^zpos-exceptions]: Some scripts move the SoundEffectPlayer after it is created. This can change the volume of sounds, since the `z` coordinate is used to determine how close a sound is to the camera.

Sounds played at the position of the camera (for example, when moved by [`SoundEffectPlayer::AttachToCamera`](/api/Global/Audio/SoundEffectPlayer#attachtocamera)) are heard at full volume regardless of where the camera currently is. For example, the bullet sounds when the player fires bullets are played at the camera. Scripts will also sometimes set the parent transform of the SoundEffectPlayer to the camera's transform or directly set the position to the current location of the camera.

## Music and Trumpets
Music and emergency sounds are managed by the [`BgmManager`](/api/Global/Audio/BgmManager) game object. It has a single AudioSource which continously loops the current song, and uses `AudioSource::PlayOneShot` to play the emergency sounds. During Core Suppressions, the default behaviour is overridden to never play the default music or silence the current music (e.g., by [`BlueStar::Escape`](/api/Global/Abnormalities/Blue-Star/BlueStar#escape) fading out the music).

## UI and AudioClipPlayer
UI elements have an [`AudioClipPlayer`](/api/Global/Audio/AudioClipPlayer) game object, which plays sounds when buttons are hovered over or clicked. These are either "local" (meaning from this UI element) or "global" (shared between all UI elements). Regardless of the origin, the [`GlobalAudioManager`](/api/Global/Audio/GlobalAudioManager) provides an AudioSource not currently in use and PlayOneShot is used to play the AudioClip.

Local AudioClips are stored in a [`LocalAudioManager`](/api/Global/Audio/LocalAudioManager) object as a list. LocalAudioManager still plays clips through GlobalAudioManager.

Global AudioClips each have an associated [`AudioType`](/api/Global/Audio/AudioType). These are common sounds such as the hovering-over sound, the confirm sound, or the cancel sound.

