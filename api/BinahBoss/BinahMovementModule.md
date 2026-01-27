---
uid: BinahBoss.BinahMovementModule
canonical_path: /api/BinahBoss/BinahMovementModule
---

# Class BinahMovementModule

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahMovementModule
```
Handles [An Arbiter](/api/Global/Script/BinahCoreScript)'s pathing and meltdowns

See also: [BinahMovement](/api/BinahBoss/BinahMovement)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahMovementModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahMovementModule(BinahCoreScript)

```csharp
public BinahMovementModule(BinahCoreScript coreScript)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `coreScript` | `Global.BinahCoreScript` |  |

## Fields

### _actionBlocked

```csharp
private bool _actionBlocked
```
#INC


#### Field Value

**Type:** System.Boolean

### _arrivedAction

```csharp
private BinahVoidAction _arrivedAction
```
#INC


#### Field Value

**Type:** BinahBoss.BinahVoidAction

### _coreScript

```csharp
private BinahCoreScript _coreScript
```
#INC


#### Field Value

**Type:** Global.BinahCoreScript

### _currentMoveState

```csharp
private BinahMoveState _currentMoveState
```
#INC


#### Field Value

**Type:** BinahBoss.BinahMoveState

### _stopMovetimer

```csharp
private Timer _stopMovetimer
```
#INC


#### Field Value

**Type:** Global.Timer

### currentDestSefira

```csharp
private SefiraEnum currentDestSefira
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### movableSefira

```csharp
private List<SefiraEnum> movableSefira
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraEnum}

### movementQueue

```csharp
private Queue<SefiraEnum> movementQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{SefiraEnum}

## Properties

### CoreScript

```csharp
public BinahCoreScript CoreScript { get; }
```

#### Property Value

**Type:** Global.BinahCoreScript

### CurrentMoveState

```csharp
public BinahMoveState CurrentMoveState { get; }
```

#### Property Value

**Type:** BinahBoss.BinahMoveState

### IsMoving

```csharp
private bool IsMoving { get; }
```

#### Property Value

**Type:** System.Boolean

### Movable

```csharp
private MovableObjectNode Movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

## Methods

### Arrived()

```csharp
public void Arrived()
```
#INC


### CheckArrived()

```csharp
private bool CheckArrived()
```
#INC


#### Returns

**Type:** System.Boolean

### Execute()

```csharp
public void Execute()
```
#INC


### GetCurrentDestNode()

```csharp
private MapNode GetCurrentDestNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### Init()

```csharp
private void Init()
```
#INC


### Move()

```csharp
public void Move()
```
#INC


### RelaseMovement()

```csharp
public void RelaseMovement()
```
#INC


### Stop()

```csharp
private void Stop()
```
#INC


### StopByAction()

```csharp
public void StopByAction()
```
#INC


### StopByTime(float)

```csharp
public void StopByTime(float stopTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stopTime` | `System.Single` |  |
