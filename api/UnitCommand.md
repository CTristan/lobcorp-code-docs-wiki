# Class UnitCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitCommand

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UnitCommand()

```csharp
public UnitCommand()
```

## Fields

### actor

```csharp
public UnitModel actor
```

#### Field Value

**Type:** Global.UnitModel

### isFinished

```csharp
public bool isFinished
```

#### Field Value

**Type:** System.Boolean

### isRemoved

```csharp
public bool isRemoved
```

#### Field Value

**Type:** System.Boolean

## Methods

### Execute()

```csharp
public virtual void Execute()
```

### Finish()

```csharp
public void Finish()
```

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnInit(StandingItemModel)

```csharp
public virtual void OnInit(StandingItemModel standing)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### OnInit(UnitModel)

```csharp
public virtual void OnInit(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnInit(WorkerModel)

```csharp
public virtual void OnInit(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OnStart()

```csharp
public virtual void OnStart()
```

### OnStop()

```csharp
public virtual void OnStop()
```
