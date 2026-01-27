---
uid: Global.AutoTimer
canonical_path: /api/Global/Misc/AutoTimer
---

# Class AutoTimer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AutoTimer : Timer, IObserver
```
Calls a target method after a certain amount of time.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Timer](/api/Global/Misc/Timer) → AutoTimer

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[elapsed](/api/Global/Misc/Timer#elapsed), [maxTime](/api/Global/Misc/Timer#maxtime), [started](/api/Global/Misc/Timer#started), [autoStop](/api/Global/Misc/Timer#autostop), [endCmd](/api/Global/Misc/Timer#endcmd), [StartTimer(float)](/api/Global/Misc/Timer#starttimer-float), [SetEndCmd(OnTimerRunningEnd)](/api/Global/Misc/Timer#setendcmd-ontimerrunningend), [RunTimer()](/api/Global/Misc/Timer#runtimer), [StartTimer()](/api/Global/Misc/Timer#starttimer), [StopTimer()](/api/Global/Misc/Timer#stoptimer), [ToString()](/api/Global/Misc/Timer#tostring), [GetRate()](/api/Global/Misc/Timer#getrate), [Rate](/api/Global/Misc/Timer#rate), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AutoTimer()

```csharp
public AutoTimer()
```

## Fields

### del1

```csharp
private AutoTimer.TargetMethod del1
```

#### Field Value

**Type:** Global.AutoTimer.TargetMethod

### isInitialized

```csharp
public bool isInitialized
```
#INC


#### Field Value

**Type:** System.Boolean

### mode

```csharp
private AutoTimer.UpdateMode mode
```

#### Field Value

**Type:** Global.AutoTimer.UpdateMode

### removeAfterRun

```csharp
private bool removeAfterRun
```
#INC


#### Field Value

**Type:** System.Boolean

### updateCalled

```csharp
private AutoTimer.TargetMethod updateCalled
```

#### Field Value

**Type:** Global.AutoTimer.TargetMethod

## Methods

### Destroy(AutoTimer)

```csharp
public static void Destroy(AutoTimer timer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `timer` | `Global.AutoTimer` |  |

### FixedUpdate()

```csharp
public void FixedUpdate()
```
#INC


### Init()

```csharp
public void Init()
```
#INC


### OnDestroy()

```csharp
public void OnDestroy()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### Update()

```csharp
public void Update()
```
#INC

