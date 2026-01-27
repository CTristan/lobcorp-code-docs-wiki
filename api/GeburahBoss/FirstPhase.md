---
uid: GeburahBoss.FirstPhase
canonical_path: /api/GeburahBoss/FirstPhase
---

# Class FirstPhase

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FirstPhase : GeburahPhaseExectuion
```

[An Arbiter](/api/Global/Script/BinahCoreScript)'s behavior for phase one.

She:
Creates the [Black Fog](/api/BinahBoss/BlackFogOverload) or [Golden](/api/BinahBoss/GoldenOverload) meltdowns, if she has her meltdowns currently.

If there's someone near her, she randomly chooses to smite them with the [Blade Wave](/api/BinahBoss/BladeWaveThrow) or the [Column throw](/api/BinahBoss/ColumnThrow) attack. She then moves for a random amount of time determined by her attack delay.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → FirstPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FirstPhase(GeburahCoreScript)

```csharp
public FirstPhase(GeburahCoreScript geburah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### attackDist

```csharp
private float attackDist
```
#INC


#### Field Value

**Type:** System.Single

### AttackProb

```csharp
private static DefaultAttack.AttackProb[] AttackProb
```
#INC


#### Field Value

**Type:** GeburahBoss.DefaultAttack.AttackProb[]

### attackProbList

```csharp
private static List<DefaultAttack.AttackProb> attackProbList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{GeburahBoss.DefaultAttack.AttackProb}

### currentPassage

```csharp
private PassageObjectModel currentPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### currentTarget

```csharp
private UnitModel currentTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### fillCount

```csharp
private int fillCount
```
#INC


#### Field Value

**Type:** System.Int32

### MoveProb

```csharp
private float MoveProb
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
#code-generated


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

### GetRandomTeleportCount()

```csharp
private int GetRandomTeleportCount()
```
#INC


#### Returns

**Type:** System.Int32

### OnDamageFilled()

```csharp
public void OnDamageFilled()
```
#INC


### OnPrevSuppressed()

```csharp
public override void OnPrevSuppressed()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC

