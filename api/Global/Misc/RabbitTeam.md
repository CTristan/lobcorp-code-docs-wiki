---
uid: Global.RabbitTeam
canonical_path: /api/Global/Misc/RabbitTeam
---

# Class RabbitTeam

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitTeam
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitTeam

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitTeam()

```csharp
public RabbitTeam()
```

## Fields

### _aiTimer

```csharp
private Timer _aiTimer
```

#### Field Value

**Type:** Global.Timer

### _area

```csharp
private RabbitOperationArea _area
```

#### Field Value

**Type:** Global.RabbitOperationArea

### _cleared

```csharp
private bool _cleared
```

#### Field Value

**Type:** System.Boolean

### _clearTimer

```csharp
private Timer _clearTimer
```

#### Field Value

**Type:** Global.Timer

### _currentTargetPassage

```csharp
private PassageObjectModel _currentTargetPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### aiFreq

```csharp
private const float aiFreq = 1
```

#### Field Value

**Type:** System.Single

### closeFreq

```csharp
private const float closeFreq = 10
```

#### Field Value

**Type:** System.Single

### rabbits

```csharp
public List<RabbitModel> rabbits
```

#### Field Value

**Type:** System.Collections.Generic.List{RabbitModel}

### sefira

```csharp
public SefiraEnum sefira
```

#### Field Value

**Type:** Global.SefiraEnum

## Properties

### IsCleared

```csharp
public bool IsCleared { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ClearOperation()

```csharp
public void ClearOperation()
```

### ExistsTargetPassage()

```csharp
public bool ExistsTargetPassage()
```

#### Returns

**Type:** System.Boolean

### GetRabbitsTarget(PassageObjectModel)

```csharp
private UnitModel GetRabbitsTarget(PassageObjectModel p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.UnitModel

### Init(RabbitOperationArea)

```csharp
public void Init(RabbitOperationArea area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `Global.RabbitOperationArea` |  |

### IsDeadAll()

```csharp
public bool IsDeadAll()
```

#### Returns

**Type:** System.Boolean

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### UpdateTargetPassage()

```csharp
private void UpdateTargetPassage()
```
