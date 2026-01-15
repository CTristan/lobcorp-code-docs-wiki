---
uid: BinahBoss.SecondPhase
canonical_path: /api/BinahBoss/SecondPhase
---

# Class SecondPhase

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SecondPhase : BinahPhaseExecution
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahPhaseExecution](/api/BinahBoss/BinahPhaseExecution) → SecondPhase

## Inherited Members
[binah](/api/BinahBoss/BinahPhaseExecution#binah), [overloadActivated](/api/BinahBoss/BinahPhaseExecution#overloadactivated), [overloadTimer](/api/BinahBoss/BinahPhaseExecution#overloadtimer), [overloadTypeList](/api/BinahBoss/BinahPhaseExecution#overloadtypelist), [HaltOverload()](/api/BinahBoss/BinahPhaseExecution#haltoverload), [StartTimer(float)](/api/BinahBoss/BinahPhaseExecution#starttimer-float), [GetOverloadType()](/api/BinahBoss/BinahPhaseExecution#getoverloadtype), [OnOverloadEnd()](/api/BinahBoss/BinahPhaseExecution#onoverloadend), [ToString()](/api/BinahBoss/BinahPhaseExecution#tostring), [BinahHasOverload](/api/BinahBoss/BinahPhaseExecution#binahhasoverload), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SecondPhase(BinahCoreScript)

```csharp
public SecondPhase(BinahCoreScript binah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GetNextAction(List<UnitModel>)

```csharp
public override BinahAction GetNextAction(List<UnitModel> near)
```

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

### Update()

```csharp
public override void Update()
```
