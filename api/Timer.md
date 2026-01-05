# Class Timer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Timer
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Timer

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Timer()

```csharp
public Timer()
```

## Fields

### autoStop

```csharp
public bool autoStop
```

#### Field Value

**Type:** System.Boolean

### elapsed

```csharp
public float elapsed
```

#### Field Value

**Type:** System.Single

### endCmd

```csharp
public Timer.OnTimerRunningEnd endCmd
```

#### Field Value

**Type:** Global.Timer.OnTimerRunningEnd

### maxTime

```csharp
public float maxTime
```

#### Field Value

**Type:** System.Single

### started

```csharp
public bool started
```

#### Field Value

**Type:** System.Boolean

## Properties

### Rate

```csharp
public float Rate { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### GetRate()

```csharp
public virtual float GetRate()
```

#### Returns

**Type:** System.Single

### RunTimer()

```csharp
public virtual bool RunTimer()
```

#### Returns

**Type:** System.Boolean

### SetEndCmd(OnTimerRunningEnd)

```csharp
public virtual void SetEndCmd(Timer.OnTimerRunningEnd cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.Timer.OnTimerRunningEnd` |  |

### StartTimer()

```csharp
public virtual void StartTimer()
```

### StartTimer(float)

```csharp
public virtual void StartTimer(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### StopTimer()

```csharp
public virtual void StopTimer()
```

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
