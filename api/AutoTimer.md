# Class AutoTimer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AutoTimer : Timer, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Timer](/api/Timer) → AutoTimer

## Inherited Members
[elapsed](/api/Timer#elapsed), [maxTime](/api/Timer#maxtime), [started](/api/Timer#started), [autoStop](/api/Timer#autostop), [endCmd](/api/Timer#endcmd), [StartTimer(float)](/api/Timer#starttimer-float), [SetEndCmd(OnTimerRunningEnd)](/api/Timer#setendcmd-ontimerrunningend), [RunTimer()](/api/Timer#runtimer), [StartTimer()](/api/Timer#starttimer), [StopTimer()](/api/Timer#stoptimer), [ToString()](/api/Timer#tostring), [GetRate()](/api/Timer#getrate), [Rate](/api/Timer#rate), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AutoTimer()

```csharp
public AutoTimer()
```

## Fields

### isInitialized

```csharp
public bool isInitialized
```

#### Field Value

**Type:** System.Boolean

## Methods

### Destroy(AutoTimer)

```csharp
public static void Destroy(AutoTimer timer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `timer` | `Global.AutoTimer` |  |

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### Init()

```csharp
public void Init()
```

### OnDestroy()

```csharp
public void OnDestroy()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### StartTimer(float, TargetMethod, bool, UpdateMode)

```csharp
public void StartTimer(float time, AutoTimer.TargetMethod method, bool remove, AutoTimer.UpdateMode mode = UpdateMode.FIXEDUPDATE)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `method` | `Global.AutoTimer.TargetMethod` |  |
| `remove` | `System.Boolean` |  |
| `mode` | `Global.AutoTimer.UpdateMode` |  |

### StartTimer(float, TargetMethod, TargetMethod, UpdateMode)

```csharp
public void StartTimer(float time, AutoTimer.TargetMethod method, AutoTimer.TargetMethod update, AutoTimer.UpdateMode mode = UpdateMode.FIXEDUPDATE)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `method` | `Global.AutoTimer.TargetMethod` |  |
| `update` | `Global.AutoTimer.TargetMethod` |  |
| `mode` | `Global.AutoTimer.UpdateMode` |  |

### StartTimer(float, TargetMethod, UpdateMode)

```csharp
public void StartTimer(float time, AutoTimer.TargetMethod method, AutoTimer.UpdateMode mode = UpdateMode.FIXEDUPDATE)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `method` | `Global.AutoTimer.TargetMethod` |  |
| `mode` | `Global.AutoTimer.UpdateMode` |  |

### UnscaledRunTimer()

```csharp
public bool UnscaledRunTimer()
```

#### Returns

**Type:** System.Boolean

### Update()

```csharp
public void Update()
```
