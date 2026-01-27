---
uid: Global.DamageInfo
canonical_path: /api/Global/Info/DamageInfo
---

# Class DamageInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DamageInfo
```
Stores information about damage.

Holds damage type, sound and effect data, whether a special death thing needs to happen if it kills.

Also provides the method that calculates damage.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DamageInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DamageInfo(RwbpType, float)

```csharp
public DamageInfo(RwbpType type, float damage)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `damage` | `System.Single` |  |

### DamageInfo(RwbpType, int, int)

```csharp
public DamageInfo(RwbpType type, int min, int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `min` | `System.Int32` |  |
| `max` | `System.Int32` |  |

## Fields

### effectInfo

```csharp
public EffectInfo effectInfo
```
#INC


#### Field Value

**Type:** Global.EffectInfo

### effectInfos

```csharp
public List<EffectInfo> effectInfos
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EffectInfo}

### max

```csharp
public float max
```
#INC


#### Field Value

**Type:** System.Single

### min

```csharp
public float min
```
#INC


#### Field Value

**Type:** System.Single

### param

```csharp
public string param
```
#INC


#### Field Value

**Type:** System.String

### soundInfo

```csharp
public SoundInfo soundInfo
```
#INC


#### Field Value

**Type:** Global.SoundInfo

### specialDeadSceneEnable

```csharp
public bool specialDeadSceneEnable
```
#INC


#### Field Value

**Type:** System.Boolean

### specialDeadSceneName

```csharp
public string specialDeadSceneName
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public RwbpType type
```
#INC


#### Field Value

**Type:** Global.RwbpType

## Properties

### zero

```csharp
public static DamageInfo zero { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### Copy()

```csharp
public DamageInfo Copy()
```
#INC


#### Returns

**Type:** Global.DamageInfo

### GetDamage()

```csharp
public float GetDamage()
```
#INC


#### Returns

**Type:** System.Single

### GetDamageWithDefenseInfo(DefenseInfo)

```csharp
public float GetDamageWithDefenseInfo(DefenseInfo defense)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defense` | `Global.DefenseInfo` |  |

#### Returns

**Type:** System.Single

## Operators

### operator *(DamageInfo, float)

```csharp
public static DamageInfo operator *(DamageInfo d, float f)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d` | `Global.DamageInfo` |  |
| `f` | `System.Single` |  |

#### Returns

**Type:** Global.DamageInfo

### operator *(float, DamageInfo)

```csharp
public static DamageInfo operator *(float f, DamageInfo d)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `f` | `System.Single` |  |
| `d` | `Global.DamageInfo` |  |

#### Returns

**Type:** Global.DamageInfo
