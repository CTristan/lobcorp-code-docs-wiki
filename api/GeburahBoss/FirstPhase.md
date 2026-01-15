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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahPhaseExectuion](/api/GeburahBoss/GeburahPhaseExectuion) → FirstPhase

## Inherited Members
[geburah](/api/GeburahBoss/GeburahPhaseExectuion#geburah), [isPrevAttack](/api/GeburahBoss/GeburahPhaseExectuion#isprevattack), [GetRandomNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandomnode), [GetRandomMoveNode()](/api/GeburahBoss/GeburahPhaseExectuion#getrandommovenode), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FirstPhase(GeburahCoreScript)

```csharp
public FirstPhase(GeburahCoreScript geburah)
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

### currentPassage

```csharp
private PassageObjectModel currentPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

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

### GetRandomTeleportCount()

```csharp
private int GetRandomTeleportCount()
```

#### Returns

**Type:** System.Int32

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
