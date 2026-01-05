# Class BgmManager.AudioClipList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BgmManager.AudioClipList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BgmManager.AudioClipList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AudioClipList()

```csharp
public AudioClipList()
```

## Fields

### lastPlayed

```csharp
public int lastPlayed
```

#### Field Value

**Type:** System.Int32

### list

```csharp
public List<AudioClip> list
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.AudioClip}

## Methods

### GetClip(int)

```csharp
public AudioClip GetClip(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.AudioClip

### GetRandomClip()

```csharp
public AudioClip GetRandomClip()
```

#### Returns

**Type:** UnityEngine.AudioClip
