---
uid: GeburahBoss.FourthPhase
canonical_path: /api/GeburahBoss/FourthPhase
---

# Class FourthPhase

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FourthPhase : GeburahPhaseExectuion
```

[The Red Mist](/api/Global/Script/GeburahCoreScript)'s fourth phase.

Sets attack probabilities and queues actions for this phase. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → FourthPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [OnPrevSuppressed()](/api/GeburahBoss/GeburahPhaseExectuion#onprevsuppressed), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FourthPhase(GeburahCoreScript)

```csharp
public FourthPhase(GeburahCoreScript geburah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### defaultAttackProb

```csharp
private float defaultAttackProb
```
#INC


#### Field Value

**Type:** System.Single

### greedy

```csharp
private float greedy
```
#INC


#### Field Value

**Type:** System.Single

### idleChase

```csharp
private float idleChase
```
#INC


#### Field Value

**Type:** System.Single

### moveProb

```csharp
private float moveProb
```
#INC


#### Field Value

**Type:** System.Single

### p4Speed

```csharp
private float p4Speed
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### GetNextAction(List<UnitModel>)

```csharp
public override GeburahAction GetNextAction(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** GeburahBoss.GeburahAction

### Update()

```csharp
public override void Update()
```
#INC
#code-generated

