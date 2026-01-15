---
uid: Global.RandomEventManager
canonical_path: /api/Global/IOBserver/RandomEventManager
---

# Class RandomEventManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RandomEventManager()

```csharp
public RandomEventManager()
```

## Fields

### _instance

```csharp
private static RandomEventManager _instance
```

#### Field Value

**Type:** Global.RandomEventManager

### _isLoadedInfo

```csharp
private bool _isLoadedInfo
```

#### Field Value

**Type:** System.Boolean

### _todayMax

```csharp
private RandomEventRank _todayMax
```

#### Field Value

**Type:** Global.RandomEventRank

### checkEvents

```csharp
private List<RandomEventBase> checkEvents
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### checkRemove

```csharp
private List<RandomEventBase> checkRemove
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### currentInst

```csharp
private long currentInst
```

#### Field Value

**Type:** System.Int64

### currentTimeIndex

```csharp
private int currentTimeIndex
```

#### Field Value

**Type:** System.Int32

### descPatch

```csharp
public const string descPatch = "Desc"
```

#### Field Value

**Type:** System.String

### enableDay

```csharp
private const int enableDay = 20
```

#### Field Value

**Type:** System.Int32

### enabledEvents

```csharp
private List<RandomEventBase> enabledEvents
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### GameStarted

```csharp
private bool GameStarted
```

#### Field Value

**Type:** System.Boolean

### generatedEvents

```csharp
private List<RandomEventBase> generatedEvents
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### infoTable

```csharp
private Dictionary<long, RandomEventInfo> infoTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,RandomEventInfo}

### midnight

```csharp
private RandomEventBase midnight
```

#### Field Value

**Type:** Global.RandomEventBase

### randomEventTime

```csharp
public RandomEventManager.RandomEventTime[] randomEventTime
```

#### Field Value

**Type:** Global.RandomEventManager.RandomEventTime[]

### removedFromEnabled

```csharp
private List<RandomEventBase> removedFromEnabled
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### table

```csharp
private Dictionary<RandomEventRank, List<RandomEventInfo>> table
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{RandomEventRank,System.Collections.Generic.List{RandomEventInfo}}

### timer

```csharp
private Timer timer
```

#### Field Value

**Type:** Global.Timer

### todayMaxEnergy

```csharp
private float todayMaxEnergy
```

#### Field Value

**Type:** System.Single

## Properties

### CurrentRandomEventTime

```csharp
private RandomEventManager.RandomEventTime CurrentRandomEventTime { get; set; }
```

#### Property Value

**Type:** Global.RandomEventManager.RandomEventTime

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

### CheckDuplicatable(long)

```csharp
private bool CheckDuplicatable(long metaId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metaId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### CheckEnabledDuplicate(RandomEventBase)

```csharp
private bool CheckEnabledDuplicate(RandomEventBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.RandomEventBase` |  |

#### Returns

**Type:** System.Boolean

### CheckEnableEvent()

```csharp
public void CheckEnableEvent()
```

### CheckEnergy()

```csharp
private void CheckEnergy()
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

### DisabledRemoveFromExecute()

```csharp
private void DisabledRemoveFromExecute()
```

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

### EnabledRemoveFromCheck()

```csharp
private void EnabledRemoveFromCheck()
```

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

### Execute()

```csharp
private void Execute()
```

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

### SetTodayMaxEnergy()

```csharp
private void SetTodayMaxEnergy()
```

### UpdateDay()

```csharp
public void UpdateDay()
```

### UpdatedEvents()

```csharp
public void UpdatedEvents()
```
