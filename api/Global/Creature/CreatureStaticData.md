---
uid: Global.CreatureStaticData
canonical_path: /api/Global/Creature/CreatureStaticData
---

# Class CreatureStaticData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureStaticData
```
Holds strings which can be accessed by a string key or by index.

Used by [Apocalypse Bird](/api/Global/Misc/BossBird)'s narration, [WhiteNight](/api/Legacy/DeathAngel)'s [time control restriction](/api/GameStatusUI/PlaySpeedSettingBlockedUI) narration, and for [Queen of Hatred](/api/Global/IOBserver/MagicalGirl)'s speech.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureStaticData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureStaticData()

```csharp
public CreatureStaticData()
```

## Fields

### paramList

```csharp
public List<CreatureStaticData.ParameterData> paramList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureStaticData.ParameterData}

## Properties

### count

```csharp
private int count { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetParam(int)

```csharp
public CreatureStaticData.ParameterData GetParam(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetParam(string)

```csharp
public CreatureStaticData.ParameterData GetParam(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData
