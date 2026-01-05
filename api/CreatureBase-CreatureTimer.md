# Class CreatureBase.CreatureTimer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase.CreatureTimer
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase.CreatureTimer

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureTimer()

```csharp
public CreatureTimer()
```

### CreatureTimer(float)

```csharp
public CreatureTimer(float Time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Time` | `System.Single` |  |

## Fields

### elapsed

```csharp
public float elapsed
```

#### Field Value

**Type:** System.Single

### enabled

```csharp
public bool enabled
```

#### Field Value

**Type:** System.Boolean

### maxTime

```csharp
public float maxTime
```

#### Field Value

**Type:** System.Single

### oneShot

```csharp
public bool oneShot
```

#### Field Value

**Type:** System.Boolean

### started

```csharp
public bool started
```

#### Field Value

**Type:** System.Boolean

## Methods

### isStarted()

```csharp
public bool isStarted()
```

#### Returns

**Type:** System.Boolean

### TimerRun()

```csharp
public bool TimerRun()
```

#### Returns

**Type:** System.Boolean

### TimerStart(bool)

```csharp
public void TimerStart(bool oneShot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oneShot` | `System.Boolean` |  |

### TimerStart(float, bool)

```csharp
public void TimerStart(float Time, bool oneShot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Time` | `System.Single` |  |
| `oneShot` | `System.Boolean` |  |

### TimerStop()

```csharp
public void TimerStop()
```
