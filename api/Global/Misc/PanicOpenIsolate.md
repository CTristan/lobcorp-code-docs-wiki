---
uid: Global.PanicOpenIsolate
canonical_path: /api/Global/Misc/PanicOpenIsolate
---

# Class PanicOpenIsolate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicOpenIsolate : PanicAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicOpenIsolate

## Inherited Members
[GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicOpenIsolate(AgentModel)

```csharp
public PanicOpenIsolate(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

## Fields

### _currentOpenTargetCreature

```csharp
private CreatureModel _currentOpenTargetCreature
```

#### Field Value

**Type:** Global.CreatureModel

### _currentTargetPassage

```csharp
private PassageObjectModel _currentTargetPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### _openActionCooltime

```csharp
private const float _openActionCooltime = 5
```

#### Field Value

**Type:** System.Single

### _openActionTimer

```csharp
private Timer _openActionTimer
```

#### Field Value

**Type:** Global.Timer

### _openTryCount

```csharp
private int _openTryCount
```

#### Field Value

**Type:** System.Int32

### _openTryMax

```csharp
private const int _openTryMax = 5
```

#### Field Value

**Type:** System.Int32

### actor

```csharp
private AgentModel actor
```

#### Field Value

**Type:** Global.AgentModel

## Methods

### Execute()

```csharp
public override void Execute()
```

### GetDefenseMultiplier()

```csharp
public override float GetDefenseMultiplier()
```

#### Returns

**Type:** System.Single

### GetMovementMultiplier()

```csharp
public override float GetMovementMultiplier()
```

#### Returns

**Type:** System.Single

### GetTarget()

```csharp
public CreatureModel GetTarget()
```

#### Returns

**Type:** Global.CreatureModel

### Init()

```csharp
public override void Init()
```

### OnAgentAnimEvent(int)

```csharp
public void OnAgentAnimEvent(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDie()

```csharp
public override void OnDie()
```

### PanicEnd()

```csharp
public override void PanicEnd()
```

### TryOpen()

```csharp
private void TryOpen()
```

### UpdateNextTarget()

```csharp
private void UpdateNextTarget()
```
