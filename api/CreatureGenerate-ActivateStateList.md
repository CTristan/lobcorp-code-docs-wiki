# Class ActivateStateList

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ActivateStateList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ActivateStateList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### riskLevel

```csharp
public RiskLevel riskLevel
```

#### Field Value

**Type:** Global.RiskLevel

### Usable

```csharp
public List<ActivateStateModel> Usable
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

## Properties

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `CreatureGenerate.ActivateStateModel` |  |

### CheckUsableState()

```csharp
public void CheckUsableState()
```

### DayUpdate()

```csharp
public void DayUpdate()
```

### GetRandomCreature()

```csharp
public ActivateStateModel GetRandomCreature()
```

#### Returns

**Type:** CreatureGenerate.ActivateStateModel

### GetUsableCreatures()

```csharp
public List<ActivateStateModel> GetUsableCreatures()
```

#### Returns

**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### OnUsed(long)

```csharp
public void OnUsed(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### RemoveAction(long)

```csharp
public void RemoveAction(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
