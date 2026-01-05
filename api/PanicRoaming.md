# Class PanicRoaming

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicRoaming : PanicAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/PanicAction) → PanicRoaming

## Inherited Members
[GetAttackSpeedMultiplier()](/api/PanicAction#getattackspeedmultiplier), [GetDefenseMultiplier()](/api/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PanicRoaming(AgentModel)

```csharp
public PanicRoaming(AgentModel actor)
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

### GetMovementMultiplier()

```csharp
public override float GetMovementMultiplier()
```

#### Returns

**Type:** System.Single

### Init()

```csharp
public override void Init()
```

### OnDie()

```csharp
public override void OnDie()
```

### PanicEnd()

```csharp
public override void PanicEnd()
```
