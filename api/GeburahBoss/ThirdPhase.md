---
uid: GeburahBoss.ThirdPhase
canonical_path: /api/GeburahBoss/ThirdPhase
---

# Class ThirdPhase

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ThirdPhase : GeburahPhaseExectuion
```

[An Arbiter](/api/Global/Script/BinahCoreScript)'s third phase behavior.

Binah gets a [Golden](/api/BinahBoss/GoldenOverload), [Black Fog](/api/BinahBoss/BlackFogOverload), [Wave](/api/BinahBoss/WaveOverload), and [|Column](/api/BinahBoss/EightColumn) overloads, then opens with the [Black Fog](/api/BinahBoss/BlackThron) attack, Column attack, and then begins moving. If she gets her overloads back, she will open with the Black Fog attack, then decide randomly to start the column attack (if she isn't doing it already), or otherwise queue an overload.

If someone is near her, she will randomly choose to either use her [Blade Wave](/api/BinahBoss/BladeWaveThrow) or [Column throw](/api/BinahBoss/ColumnThrow) attack. She then moves for a random amount of time determined by her attack delay.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → ThirdPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ThirdPhase(GeburahCoreScript)

```csharp
public ThirdPhase(GeburahCoreScript geburah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### _prevIsChase

```csharp
private bool _prevIsChase
```
#INC


#### Field Value

**Type:** System.Boolean

### fillCount

```csharp
private int fillCount
```
#INC


#### Field Value

**Type:** System.Int32

### hammerProb

```csharp
private float hammerProb
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

### spearProb

```csharp
private float spearProb
```
#INC


#### Field Value

**Type:** System.Single

### teleportProb

```csharp
private float teleportProb
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

