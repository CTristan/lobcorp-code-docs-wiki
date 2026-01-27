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
A collection of a few [rabbits](/api/Global/Model/RabbitModel) spawned together in a [RabbitSquad](/api/Global/Misc/RabbitSquad).

#INC 


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
#INC


#### Field Value

**Type:** Global.Timer

### _area

```csharp
private RabbitOperationArea _area
```
#INC


#### Field Value

**Type:** Global.RabbitOperationArea

### _cleared

```csharp
private bool _cleared
```
#INC


#### Field Value

**Type:** System.Boolean

### _clearTimer

```csharp
private Timer _clearTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _currentTargetPassage

```csharp
private PassageObjectModel _currentTargetPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### aiFreq

```csharp
private const float aiFreq = 1
```
#INC


#### Field Value

**Type:** System.Single

### closeFreq

```csharp
private const float closeFreq = 10
```
#INC


#### Field Value

**Type:** System.Single

### rabbits

```csharp
public List<RabbitModel> rabbits
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitModel}

### sefira

```csharp
public SefiraEnum sefira
```
#INC


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
#INC


### ExistsTargetPassage()

```csharp
public bool ExistsTargetPassage()
```
#INC


#### Returns

**Type:** System.Boolean

### GetRabbitsTarget(PassageObjectModel)

```csharp
private UnitModel GetRabbitsTarget(PassageObjectModel p)
```
#INC


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
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `Global.RabbitOperationArea` |  |

### IsDeadAll()

```csharp
public bool IsDeadAll()
```
#INC


#### Returns

**Type:** System.Boolean

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### UpdateTargetPassage()

```csharp
private void UpdateTargetPassage()
```
#INC

