---
title: SoundEffectPlayer
description: 
published: true
date: 2026-08-24T18:29:57.448Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:02:44.134Z
---

# Class SoundEffectPlayer
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SoundEffectPlayer : MonoBehaviour
```

A `SoundEffectPlayer` is a game object used to play a sound. Most sounds are played this way, excluding UI sounds, the background music, and a few miscellaneous exceptions.

See also [Sound](/system-descriptions/sound/Sound) for an overview of how sound works in Lobotomy Corporation.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SoundEffectPlayer

## Constructors
### SoundEffectPlayer()
```csharp
public SoundEffectPlayer()
```
Default constructor.

## Fields
### clips
```csharp
private Queue<AudioClip> clips
```
A list of clips to play in order, though this is not used.

#### Field Value
**Type:** System.Collections.Generic.Queue{UnityEngine.AudioClip}

### destroyTime
```csharp
private float destroyTime
```
The time to wait before destroying this `SoundEffectPlayer`.

#### Field Value
**Type:** System.Single

### elapsedTime
```csharp
private float elapsedTime
```
The amount of time (unscaled) that has passed since this `SoundEffectPlayer` was created.

#### Field Value
**Type:** System.Single

### halted
```csharp
public bool halted
```
A flag indicating if this `SoundEffectPlayer` has been stopped with [`SoundEffectPlayer::Halt()`](/api/Global/Audio/SoundEffectPlayer#halt).

#### Field Value
**Type:** System.Boolean

### onshot
```csharp
private bool onshot
```
A flag indicating if this `SoundEffectPlayer` is playing its [`AudioClip`](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioClip.html) once or on loop.

#### Field Value
**Type:** System.Boolean

### src
```csharp
public AudioSource src
```
The [`AudioSource`](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioSource.html) on this `SoundEffectPlayer` playing the sound.

#### Field Value
**Type:** UnityEngine.AudioSource

## Methods
### AttachToCamera()
```csharp
public void AttachToCamera()
```
Attaches this `SoundEffectPlayer` to the camera's transform, causing sounds to be played centered and at full volume.

### DeQueue()
```csharp
private void DeQueue()
```
Unused. Plays the next sound in the sequence.

### DestroyPlayer(ref SoundEffectPlayer)
```csharp
public static bool DestroyPlayer(ref SoundEffectPlayer player)
```
Destroys the provided `SoundEffectPlayer` game object.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `player` | `Global.SoundEffectPlayer` | The `SoundEffectPlayer` to destroy. |

#### Returns
**Type:** System.Boolean

### Halt()
```csharp
public void Halt()
```
Stops the sound and sets a flag.

### Play(string, Transform)
```csharp
public static SoundEffectPlayer Play(string filename, Transform transf)
```
Creates a new `SoundEffectPlayer` object which loops the sound with the name `filename` (located at `Sounds/{filename}`) at the transform `transf`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `transf` | `UnityEngine.Transform` | The transform to play the sound at. |

#### Returns
**Type:** Global.SoundEffectPlayer

### Play(string, Transform, float)
```csharp
public static SoundEffectPlayer Play(string filename, Transform transf, float volume)
```
Creates a new `SoundEffectPlayer` object which loops the sound with the name `filename` (located at `Sounds/{filename}`) at the transform `transf` and with the volume `volume`.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `transf` | `UnityEngine.Transform` | The transform to play the sound at. |
| `volume` | `System.Single` | The volume to play the sound at. |

#### Returns
**Type:** Global.SoundEffectPlayer

### PlayOnce(string, float, Vector2)
```csharp
public static SoundEffectPlayer PlayOnce(string filename, float pitch, Vector2 position)
```
Creates a new `SoundEffectPlayer` object which plays the sound with the name `filename` once at the position `position` and pitch `pitch`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `pitch` | `System.Single` | The pitch to play the sound at. |
| `position` | `UnityEngine.Vector2` | The position to play the sound at. |

#### Returns
**Type:** Global.SoundEffectPlayer

### PlayOnce(string, Vector2)
```csharp
public static SoundEffectPlayer PlayOnce(string filename, Vector2 position)
```
Creates a new `SoundEffectPlayer` object which plays the sound with the name `filename` once at the position `position`.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `position` | `UnityEngine.Vector2` | The position to play the sound at. |

#### Returns
**Type:** Global.SoundEffectPlayer

### PlayOnce(string, Vector2, AudioRolloffMode)
```csharp
public static SoundEffectPlayer PlayOnce(string filename, Vector2 position, AudioRolloffMode mode)
```
Creates a new `SoundEffectPlayer` object which plays the sound with the name `filename` once at the position `position` and with the [`AudioRolloffMode`](https://docs.unity3d.com/2017.4/Documentation/ScriptReference/AudioRolloffMode.html) `mode`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `position` | `UnityEngine.Vector2` | The position to play the sound at. |
| `mode` | `UnityEngine.AudioRolloffMode` | The `AudioRolloffMode` to play the sound with. |

#### Returns
**Type:** Global.SoundEffectPlayer

### PlayOnce(string, Vector2, float)
```csharp
public static SoundEffectPlayer PlayOnce(string filename, Vector2 position, float volume)
```
Creates a new `SoundEffectPlayer` object which plays the sound with the name `filename` once at the position `position` and at the volume `volume`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `filename` | `System.String` | The name of the sound to play. |
| `position` | `UnityEngine.Vector2` | The position to play the sound at. |
| `volume` | `System.Single` | The volume to play the sound at. |

#### Returns
**Type:** Global.SoundEffectPlayer

### PlaySequence(Vector2, params string\[])
```csharp
public static SoundEffectPlayer PlaySequence(Vector2 position, params string[] fileName)
```
Unused. Plays a sequence of sounds with the names in `fileName` at the position `position`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector2` | The position to play the sequence of sounds at. |
| `fileName` | `System.String[]` | An array of filenames of the sounds to play. |

#### Returns
**Type:** Global.SoundEffectPlayer

### ReStart()
```csharp
public void ReStart()
```
Plays the sound from the beginning and resets the `halted` flag.

### SetDestroyTime(float)
```csharp
public void SetDestroyTime(float destroyTime)
```
Sets the time from creation that this `SoundEffectPlayer` should destroy itself. Note that this does not reset the amount of time that has elapsed. This has no effect on `SoundEffectPlayer` objects created by `Play`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `destroyTime` | `System.Single` | The amount of time this `SoundEffectPlayer` should wait before destroying itself after being created. |

### Stop()
```csharp
public void Stop()
```
Destroys this `SoundEffectPlayer`.

### Update()
```csharp
private void Update()
```
For `SoundEffectPlayer` objects created with `PlayOnce`, increments the `elapsedTime`. If the `elapsedTime` exceeds the `destroyTime`, this `SoundEffectPlayer` is destroyed.

If there are a queue of clips, once the `elapsedTime` exceeds `destroyTime`, the next sound is played and the `elapsedTime` is reset. This functionality is not used.

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









