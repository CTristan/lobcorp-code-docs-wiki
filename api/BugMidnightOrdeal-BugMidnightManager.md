# Class BugMidnightOrdeal.BugMidnightManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightOrdeal.BugMidnightManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BugMidnightOrdeal.BugMidnightManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BugMidnightManager(BugMidnight)

```csharp
public BugMidnightManager(BugMidnight script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BugMidnight` |  |

## Properties

### Script

```csharp
public BugMidnight Script { get; }
```

#### Property Value

**Type:** Global.BugMidnight

### Sefira

```csharp
public Sefira Sefira { get; }
```

#### Property Value

**Type:** Global.Sefira

## Methods

### AddSpawn(BugOrdealCreature)

```csharp
public void AddSpawn(BugOrdealCreature spawn)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spawn` | `Global.BugOrdealCreature` |  |

### OnDie()

```csharp
public void OnDie()
```

### SetSefira(Sefira)

```csharp
public void SetSefira(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |
