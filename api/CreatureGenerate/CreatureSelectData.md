---
uid: CreatureGenerate.CreatureSelectData
canonical_path: /api/CreatureGenerate/CreatureSelectData
---

# Class CreatureSelectData

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSelectData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSelectData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSelectData(int)

```csharp
public CreatureSelectData(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

## Fields

### actionParam

```csharp
private List<long> actionParam
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int64}

### actionType

```csharp
private GenerateCommonAction actionType
```

#### Field Value

**Type:** CreatureGenerate.GenerateCommonAction

### d1

```csharp
private float[] d1
```

#### Field Value

**Type:** System.Single[]

### d2

```csharp
private float[] d2
```

#### Field Value

**Type:** System.Single[]

### d3

```csharp
private float[] d3
```

#### Field Value

**Type:** System.Single[]

### zeroAry

```csharp
public static float[] zeroAry
```

#### Field Value

**Type:** System.Single[]

## Properties

### Day

```csharp
public int Day { get; private set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetCreature()

```csharp
public List<long> GetCreature()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### GetRiskLevel(float[], out RiskLevel, params RiskLevel[])

```csharp
private bool GetRiskLevel(float[] d, out RiskLevel level, params RiskLevel[] reduced)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d` | `System.Single[]` |  |
| `level` | `Global.RiskLevel` |  |
| `reduced` | `Global.RiskLevel[]` |  |

#### Returns

**Type:** System.Boolean

### PickCreature(RiskLevel)

```csharp
private long PickCreature(RiskLevel risk)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `risk` | `Global.RiskLevel` |  |

#### Returns

**Type:** System.Int64

### SetActionType(GenerateCommonAction, params long[])

```csharp
public void SetActionType(GenerateCommonAction action, params long[] ids)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `CreatureGenerate.GenerateCommonAction` |  |
| `ids` | `System.Int64[]` |  |

### SetProb(List<float>, List<float>, List<float>)

```csharp
public void SetProb(List<float> d1, List<float> d2, List<float> d3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d1` | `System.Collections.Generic.List{System.Single}` |  |
| `d2` | `System.Collections.Generic.List{System.Single}` |  |
| `d3` | `System.Collections.Generic.List{System.Single}` |  |
