# Class SoundInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SoundInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SoundInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SoundInfo()

```csharp
public SoundInfo()
```

## Fields

### soundSrc

```csharp
public string soundSrc
```

#### Field Value

**Type:** System.String

### soundType

```csharp
public DamageInfo_EffectType soundType
```

#### Field Value

**Type:** Global.DamageInfo_EffectType

## Methods

### LoadClip(SoundInfo)

```csharp
public static AudioClip LoadClip(SoundInfo sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `Global.SoundInfo` |  |

#### Returns

**Type:** UnityEngine.AudioClip

### PlaySound(SoundInfo, Vector2)

```csharp
public static SoundEffectPlayer PlaySound(SoundInfo sound, Vector2 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `Global.SoundInfo` |  |
| `pos` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySound(Vector2)

```csharp
public SoundEffectPlayer PlaySound(Vector2 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** Global.SoundEffectPlayer
