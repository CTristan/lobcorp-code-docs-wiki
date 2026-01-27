---
uid: BinahBoss.ThirdPhase
canonical_path: /api/BinahBoss/ThirdPhase
---

# Class ThirdPhase

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ThirdPhase : BinahPhaseExecution
```

[An Arbiter](/api/Global/Script/BinahCoreScript)'s third phase behavior.

Binah gets a [Golden](/api/BinahBoss/GoldenOverload), [Black Fog](/api/BinahBoss/BlackFogOverload), [Wave](/api/BinahBoss/WaveOverload), and [|Column](/api/BinahBoss/EightColumn) overloads, then opens with the [Black Fog](/api/BinahBoss/BlackThron) attack, Column attack, and then begins moving. If she gets her overloads back, she will open with the Black Fog attack, then decide randomly to start the column attack (if she isn't doing it already), or otherwise queue an overload.

If someone is near her, she will randomly choose to either use her [Blade Wave](/api/BinahBoss/BladeWaveThrow) or [Column throw](/api/BinahBoss/ColumnThrow) attack. She then moves for a random amount of time determined by her attack delay.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahPhaseExecution](/api/BinahBoss/BinahPhaseExecution) → ThirdPhase

## Inherited Members
[binah](/api/BinahBoss/BinahPhaseExecution#binah), [overloadActivated](/api/BinahBoss/BinahPhaseExecution#overloadactivated), [overloadTimer](/api/BinahBoss/BinahPhaseExecution#overloadtimer), [overloadTypeList](/api/BinahBoss/BinahPhaseExecution#overloadtypelist), [HaltOverload()](/api/BinahBoss/BinahPhaseExecution#haltoverload), [StartTimer(float)](/api/BinahBoss/BinahPhaseExecution#starttimer-float), [GetOverloadType()](/api/BinahBoss/BinahPhaseExecution#getoverloadtype), [OnOverloadEnd()](/api/BinahBoss/BinahPhaseExecution#onoverloadend), [ToString()](/api/BinahBoss/BinahPhaseExecution#tostring), [BinahHasOverload](/api/BinahBoss/BinahPhaseExecution#binahhasoverload), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ThirdPhase(BinahCoreScript)

```csharp
public ThirdPhase(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### columnTimer

```csharp
private Timer columnTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### forcelyRunTime

```csharp
private const float forcelyRunTime = 70
```
#INC


#### Field Value

**Type:** System.Single

### forcelyTimer

```csharp
private Timer forcelyTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### GetNextAction(List<UnitModel>)

```csharp
public override BinahAction GetNextAction(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** BinahBoss.BinahAction

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

