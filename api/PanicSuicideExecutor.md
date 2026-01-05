# Class PanicSuicideExecutor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicSuicideExecutor : PanicAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/PanicAction) → PanicSuicideExecutor

## Inherited Members
[GetAttackSpeedMultiplier()](/api/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PanicSuicideExecutor(AgentModel)

```csharp
public PanicSuicideExecutor(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

## Fields

### suicideWDmg

```csharp
public const int suicideWDmg = 20
```

#### Field Value

**Type:** System.Int32

## Methods

### Execute()

```csharp
public override void Execute()
```

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
