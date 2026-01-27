---
uid: GeburahBoss.SecondPhase
canonical_path: /api/GeburahBoss/SecondPhase
---

# Class SecondPhase

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SecondPhase : GeburahPhaseExectuion
```

[An Arbiter](/api/Global/Script/BinahCoreScript)'s second phase behavior.
She gets [Black Fog](/api/BinahBoss/BlackFogOverload), [Golden](/api/BinahBoss/GoldenOverload), and [Wave](/api/BinahBoss/WaveOverload) meltdowns.

She starts P2 by using the [Black Fog](/api/BinahBoss/BlackThron) attack, activating the meltdowns, and then moving. If she gets the meltdowns back, she will do this again.

If someone is near her, she will randomly choose to either use her [Blade Wave](/api/BinahBoss/BladeWaveThrow) or [Column throw](/api/BinahBoss/ColumnThrow) attack. She then moves for a random amount of time determined by her attack delay.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → SecondPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SecondPhase(GeburahCoreScript)

```csharp
public SecondPhase(GeburahCoreScript geburah)
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

### spearProb

```csharp
private const float spearProb = 0.2
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

