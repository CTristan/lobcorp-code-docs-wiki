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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DamageInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DamageInfo(RwbpType, float)

```csharp
public DamageInfo(RwbpType type, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `damage` | `System.Single` |  |

### DamageInfo(RwbpType, int, int)

```csharp
public DamageInfo(RwbpType type, int min, int max)
```

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

#### Field Value

**Type:** Global.EffectInfo

### effectInfos

```csharp
public List<EffectInfo> effectInfos
```

#### Field Value

**Type:** System.Collections.Generic.List{EffectInfo}

### max

```csharp
public float max
```

#### Field Value

**Type:** System.Single

### min

```csharp
public float min
```

#### Field Value

**Type:** System.Single

### param

```csharp
public string param
```

#### Field Value

**Type:** System.String

### soundInfo

```csharp
public SoundInfo soundInfo
```

#### Field Value

**Type:** Global.SoundInfo

### specialDeadSceneEnable

```csharp
public bool specialDeadSceneEnable
```

#### Field Value

**Type:** System.Boolean

### specialDeadSceneName

```csharp
public string specialDeadSceneName
```

#### Field Value

**Type:** System.String

### type

```csharp
public RwbpType type
```

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

#### Returns

**Type:** Global.DamageInfo

### GetDamage()

```csharp
public float GetDamage()
```

#### Returns

**Type:** System.Single

### GetDamageWithDefenseInfo(DefenseInfo)

```csharp
public float GetDamageWithDefenseInfo(DefenseInfo defense)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `f` | `System.Single` |  |
| `d` | `Global.DamageInfo` |  |

#### Returns

**Type:** Global.DamageInfo
