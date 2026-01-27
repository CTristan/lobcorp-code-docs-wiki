---
uid: Global.SoundInfo
canonical_path: /api/Global/Info/SoundInfo
---

# Class SoundInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SoundInfo
```
Used to play some sound effects by [weapons](/api/Global/Model/WeaponModel) (including [Paradise Lost](/api/Global/Weapon/DeathAngelWeapon) and [Adoration](/api/Global/Weapon/SlimeGirlWeapon)) and the [Rabbits' rifles](/api/Global/Model/RabbitModel).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SoundInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


#### Field Value

**Type:** System.String

### soundType

```csharp
public DamageInfo_EffectType soundType
```
#INC


#### Field Value

**Type:** Global.DamageInfo_EffectType

## Methods

### LoadClip(SoundInfo)

```csharp
public static AudioClip LoadClip(SoundInfo sound)
```
#INC
#code-generated


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** Global.SoundEffectPlayer
