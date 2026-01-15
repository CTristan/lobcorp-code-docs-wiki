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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → SecondPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SecondPhase(GeburahCoreScript)

```csharp
public SecondPhase(GeburahCoreScript geburah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### attackDist

```csharp
private float attackDist
```

#### Field Value

**Type:** System.Single

### AttackProb

```csharp
private static DefaultAttack.AttackProb[] AttackProb
```

#### Field Value

**Type:** GeburahBoss.DefaultAttack.AttackProb[]

### attackProbList

```csharp
private static List<DefaultAttack.AttackProb> attackProbList
```

#### Field Value

**Type:** System.Collections.Generic.List{GeburahBoss.DefaultAttack.AttackProb}

### currentTarget

```csharp
private UnitModel currentTarget
```

#### Field Value

**Type:** Global.UnitModel

### fillCount

```csharp
private int fillCount
```

#### Field Value

**Type:** System.Int32

### MoveProb

```csharp
private float MoveProb
```

#### Field Value

**Type:** System.Single

### spearProb

```csharp
private const float spearProb = 0.2
```

#### Field Value

**Type:** System.Single

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

### OnDamageFilled()

```csharp
public void OnDamageFilled()
```

### OnPrevSuppressed()

```csharp
public override void OnPrevSuppressed()
```

### Update()

```csharp
public override void Update()
```
