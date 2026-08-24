---
title: AudioClipPlayer.PlayerData
description: 
published: true
date: 2026-08-24T18:50:00.107Z
tags: 
editor: markdown
dateCreated: 2026-08-24T18:50:00.107Z
---

# Class AudioClipPlayer.PlayerData
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlayerData
```

Holds information about sounds to play, used by [`AudioClipPlayer`](/api/Global/Audio/AudioClipPlayer) for UI sounds. Sounds are either local, unique sounds found on the UI element the `AudioClipPlayer` belongs to, or global, common sounds shared between all UI elements.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PlayerData

## Fields
### region
```csharp
public AudioRegion region
```
Holds whether this sound is a `GLOBAL` sound shared between all UI elements or a `LOCAL` sound unique to this UI element.

#### Field Value
**Type:** Global.AudioRegion

### localName
```csharp
public string localName = string.Empty
```
Holds the name of the local `AudioClip` to play, if applicable.

#### Field Value
**Type:** System.String


### localPlayIndex
```csharp
public int localPlayIndex = -1
```
Holds the index of the local `AudioClip` to play, if applicable.

#### Field Value
**Type:** System.Int32


### globalType
```csharp
public AudioType globalType = AudioType.CANCEL
```
Holds the type of the global sound to play, if applicable. See also [`AudioType`](/api/Global/Audio/AudioType).

#### Field Value
**Type:** Global.AudioType