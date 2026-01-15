---
uid: Global.CreatureOverloadManager
canonical_path: /api/Global/Creature/CreatureOverloadManager
---

# Class CreatureOverloadManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureOverloadManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureOverloadManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureOverloadManager()

```csharp
public CreatureOverloadManager()
```

## Fields

### _instance

```csharp
private static CreatureOverloadManager _instance
```

#### Field Value

**Type:** Global.CreatureOverloadManager

### _nextOrdeal

```csharp
private OrdealBase _nextOrdeal
```

#### Field Value

**Type:** Global.OrdealBase

### _qliphothOverloadMax

```csharp
private int _qliphothOverloadMax
```

#### Field Value

**Type:** System.Int32

### clearedBossMissions

```csharp
private HashSet<SefiraEnum> clearedBossMissions
```

#### Field Value

**Type:** System.Collections.Generic.HashSet{SefiraEnum}

### overflowValue

```csharp
private readonly int[] overflowValue
```

#### Field Value

**Type:** System.Int32[]

### qliphothOverloadGauge

```csharp
private int qliphothOverloadGauge
```

#### Field Value

**Type:** System.Int32

### qliphothOverloadIsolateNum

```csharp
private int qliphothOverloadIsolateNum
```

#### Field Value

**Type:** System.Int32

### qliphothOverloadLevel

```csharp
private int qliphothOverloadLevel
```

#### Field Value

**Type:** System.Int32

## Properties

### instance

```csharp
public static CreatureOverloadManager instance { get; }
```

#### Property Value

**Type:** Global.CreatureOverloadManager

### qliphothOverloadMax

```csharp
public int qliphothOverloadMax { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ActivateOverload()

```csharp
private void ActivateOverload()
```

### ActivateOverload(int, OverloadType, float, bool, bool, bool, params long[])

```csharp
public List<CreatureModel> ActivateOverload(int overloadCount, OverloadType type, float overloadTime, bool ignoreWork = false, bool ignoreBossReward = false, bool ignoreDefaultOverload = false, params long[] ignoredCreatureMetaId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overloadCount` | `System.Int32` |  |
| `type` | `Global.OverloadType` |  |
| `overloadTime` | `System.Single` |  |
| `ignoreWork` | `System.Boolean` |  |
| `ignoreBossReward` | `System.Boolean` |  |
| `ignoreDefaultOverload` | `System.Boolean` |  |
| `ignoredCreatureMetaId` | `System.Int64[]` |  |

#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### AddOverloadGague()

```csharp
public void AddOverloadGague()
```

### CheckOrdealActivate(int)

```csharp
private bool CheckOrdealActivate(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### GetQliphothOverloadLevel()

```csharp
public int GetQliphothOverloadLevel()
```

#### Returns

**Type:** System.Int32

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### SetQliphothOverloadLevel(int)

```csharp
private void SetQliphothOverloadLevel(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
