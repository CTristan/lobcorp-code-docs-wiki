# Class PanicOpenIsolate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicOpenIsolate : PanicAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/PanicAction) → PanicOpenIsolate

## Inherited Members
[GetAttackSpeedMultiplier()](/api/PanicAction#getattackspeedmultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PanicOpenIsolate(AgentModel)

```csharp
public PanicOpenIsolate(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

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
