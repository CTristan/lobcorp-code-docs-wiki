# Class RandomEventManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RandomEventManager()

```csharp
public RandomEventManager()
```

## Fields

### descPatch

```csharp
public const string descPatch = "Desc"
```

#### Field Value

**Type:** System.String

### randomEventTime

```csharp
public RandomEventManager.RandomEventTime[] randomEventTime
```

#### Field Value

**Type:** Global.RandomEventManager.RandomEventTime[]

## Properties

### instance

```csharp
public static RandomEventManager instance { get; }
```

#### Property Value

**Type:** Global.RandomEventManager

### IsLoadedInfo

```csharp
public bool IsLoadedInfo { get; }
```

#### Property Value

**Type:** System.Boolean

### Timer_Elapsed

```csharp
public float Timer_Elapsed { get; }
```

#### Property Value

**Type:** System.Single

### TodayMax

```csharp
public RandomEventRank TodayMax { get; }
```

#### Property Value

**Type:** Global.RandomEventRank

## Methods

### CheckEnableEvent()

```csharp
public void CheckEnableEvent()
```

### ConvertRank(RandomEventRank)

```csharp
public static string ConvertRank(RandomEventRank rank)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `Global.RandomEventRank` |  |

#### Returns

**Type:** System.String

### ConvertRank(string)

```csharp
public static RandomEventRank ConvertRank(string rank)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `System.String` |  |

#### Returns

**Type:** Global.RandomEventRank

### ConvertRankFromInt(int)

```csharp
public static RandomEventRank ConvertRankFromInt(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.RandomEventRank

### ConvertRankToInt(RandomEventRank)

```csharp
public static int ConvertRankToInt(RandomEventRank rank)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `Global.RandomEventRank` |  |

#### Returns

**Type:** System.Int32

### DisableRandomEvent(long)

```csharp
public bool DisableRandomEvent(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### DisableRandomEvent(RandomEventBase)

```csharp
public bool DisableRandomEvent(RandomEventBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.RandomEventBase` |  |

#### Returns

**Type:** System.Boolean

### EnableRandomEvent(long)

```csharp
public bool EnableRandomEvent(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### EnableRandomEvent(RandomEventBase)

```csharp
public bool EnableRandomEvent(RandomEventBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.RandomEventBase` |  |

#### Returns

**Type:** System.Boolean

### GenerateRandomEvent(long, ref RandomEventBase, ref long)

```csharp
public bool GenerateRandomEvent(long eventId, ref RandomEventBase output, ref long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventId` | `System.Int64` |  |
| `output` | `Global.RandomEventBase` |  |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### GetAllEventInfo()

```csharp
public List<RandomEventInfo> GetAllEventInfo()
```

#### Returns

**Type:** System.Collections.Generic.List{RandomEventInfo}

### GetMidnightTime()

```csharp
public float GetMidnightTime()
```

#### Returns

**Type:** System.Single

### GetRandomEventInfo(long, out RandomEventInfo)

```csharp
public bool GetRandomEventInfo(long eventId, out RandomEventInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventId` | `System.Int64` |  |
| `info` | `Global.RandomEventInfo` |  |

#### Returns

**Type:** System.Boolean

### GetScriptInEnabled(long)

```csharp
public RandomEventBase GetScriptInEnabled(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** Global.RandomEventBase

### GetScriptInGenerated(long)

```csharp
public RandomEventBase GetScriptInGenerated(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** Global.RandomEventBase

### InfoInit(Dictionary<long, RandomEventInfo>)

```csharp
public void InfoInit(Dictionary<long, RandomEventInfo> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.Int64,RandomEventInfo}` |  |

### MakeTimeTypo(string)

```csharp
public void MakeTimeTypo(string time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.String` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
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

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnUpdate()

```csharp
public void OnUpdate()
```

### Prob(float)

```csharp
public bool Prob(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### SetAllocateUIText()

```csharp
public void SetAllocateUIText()
```

### SetDayEventRank(RandomEventRank)

```csharp
public void SetDayEventRank(RandomEventRank maxRank)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `maxRank` | `Global.RandomEventRank` |  |

### UpdateDay()

```csharp
public void UpdateDay()
```

### UpdatedEvents()

```csharp
public void UpdatedEvents()
```
