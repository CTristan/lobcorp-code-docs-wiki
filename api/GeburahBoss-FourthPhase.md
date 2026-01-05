# Class FourthPhase

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FourthPhase : GeburahPhaseExectuion
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss-GeburahPhaseExectuion) → FourthPhase

## Inherited Members
[geburah](/api/GeburahBoss-GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss-GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss-GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss-GeburahPhaseExectuion#getrandommovenode), [OnPrevSuppressed()](/api/GeburahBoss-GeburahPhaseExectuion#onprevsuppressed), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FourthPhase(GeburahCoreScript)

```csharp
public FourthPhase(GeburahCoreScript geburah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GetNextAction(List<UnitModel>)

```csharp
public override GeburahAction GetNextAction(List<UnitModel> near)
```

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
