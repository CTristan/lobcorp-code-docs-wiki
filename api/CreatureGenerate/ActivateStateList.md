---
uid: CreatureGenerate.ActivateStateList
canonical_path: /api/CreatureGenerate/ActivateStateList
---

# Class ActivateStateList

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ActivateStateList
```
Contains a list of potential abnormalities to pull of a given risk level. Has a list of ones which can still be pulled (the others are flagged as removed or used).

See [CreatureGenerateInfoManager](/api/CreatureGenerate/CreatureGenerateInfoManager)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ActivateStateList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ActivateStateList()

```csharp
public ActivateStateList()
```

## Fields

### list

```csharp
public List<ActivateStateModel> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### riskLevel

```csharp
public RiskLevel riskLevel
```
#INC


#### Field Value

**Type:** Global.RiskLevel

### Usable

```csharp
public List<ActivateStateModel> Usable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

## Properties

### CurrentDay

```csharp
private int CurrentDay { get; }
```

#### Property Value

**Type:** System.Int32

### LevelEnabled

```csharp
public bool LevelEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

### Max

```csharp
public int Max { get; }
```

#### Property Value

**Type:** System.Int32

### UsableCount

```csharp
public int UsableCount { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Add(ActivateStateModel)

```csharp
public void Add(ActivateStateModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `CreatureGenerate.ActivateStateModel` |  |

### CheckUsableState()

```csharp
public void CheckUsableState()
```
#INC


### DayUpdate()

```csharp
public void DayUpdate()
```
#INC


### GetRandomCreature()

```csharp
public ActivateStateModel GetRandomCreature()
```
#INC


#### Returns

**Type:** CreatureGenerate.ActivateStateModel

### GetUsableCreatures()

```csharp
public List<ActivateStateModel> GetUsableCreatures()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### OnUsed(long)

```csharp
public void OnUsed(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### RemoveAction(long)

```csharp
public void RemoveAction(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
