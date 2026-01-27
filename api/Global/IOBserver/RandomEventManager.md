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

#unused 


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
#INC


#### Field Value

**Type:** Global.RandomEventManager

### _isLoadedInfo

```csharp
private bool _isLoadedInfo
```
#INC


#### Field Value

**Type:** System.Boolean

### _todayMax

```csharp
private RandomEventRank _todayMax
```
#INC


#### Field Value

**Type:** Global.RandomEventRank

### checkEvents

```csharp
private List<RandomEventBase> checkEvents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### checkRemove

```csharp
private List<RandomEventBase> checkRemove
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### currentInst

```csharp
private long currentInst
```
#INC


#### Field Value

**Type:** System.Int64

### currentTimeIndex

```csharp
private int currentTimeIndex
```
#INC


#### Field Value

**Type:** System.Int32

### descPatch

```csharp
public const string descPatch = "Desc"
```
#INC


#### Field Value

**Type:** System.String

### enableDay

```csharp
private const int enableDay = 20
```
#INC


#### Field Value

**Type:** System.Int32

### enabledEvents

```csharp
private List<RandomEventBase> enabledEvents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### GameStarted

```csharp
private bool GameStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### generatedEvents

```csharp
private List<RandomEventBase> generatedEvents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### infoTable

```csharp
private Dictionary<long, RandomEventInfo> infoTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,RandomEventInfo}

### midnight

```csharp
private RandomEventBase midnight
```
#INC


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
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase}

### table

```csharp
private Dictionary<RandomEventRank, List<RandomEventInfo>> table
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{RandomEventRank,System.Collections.Generic.List{RandomEventInfo}}

### timer

```csharp
private Timer timer
```
#INC


#### Field Value

**Type:** Global.Timer

### todayMaxEnergy

```csharp
private float todayMaxEnergy
```
#INC


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
#INC


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
#INC


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
#INC


### CheckEnergy()

```csharp
private void CheckEnergy()
```
#INC


### ConvertRank(RandomEventRank)

```csharp
public static string ConvertRank(RandomEventRank rank)
```
#INC


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
#INC


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
#INC


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
#INC


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
#INC


### DisableRandomEvent(long)

```csharp
public bool DisableRandomEvent(long instId)
```
#INC


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
#INC


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
#INC


### EnableRandomEvent(long)

```csharp
public bool EnableRandomEvent(long instId)
```
#INC


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
#INC


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
#INC


### GenerateRandomEvent(long, ref RandomEventBase, ref long)

```csharp
public bool GenerateRandomEvent(long eventId, ref RandomEventBase output, ref long instId)
```
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.List{RandomEventInfo}

### GetMidnightTime()

```csharp
public float GetMidnightTime()
```
#INC


#### Returns

**Type:** System.Single

### GetRandomEventInfo(long, out RandomEventInfo)

```csharp
public bool GetRandomEventInfo(long eventId, out RandomEventInfo info)
```
#INC


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
#INC


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
#INC


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
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.Int64,RandomEventInfo}` |  |

### MakeTimeTypo(string)

```csharp
public void MakeTimeTypo(string time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.String` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
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

### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### OnUpdate()

```csharp
public void OnUpdate()
```
#INC


### Prob(float)

```csharp
public bool Prob(float val)
```
#INC


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
#INC


### SetDayEventRank(RandomEventRank)

```csharp
public void SetDayEventRank(RandomEventRank maxRank)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `maxRank` | `Global.RandomEventRank` |  |

### SetTodayMaxEnergy()

```csharp
private void SetTodayMaxEnergy()
```
#INC


### UpdateDay()

```csharp
public void UpdateDay()
```
#INC


### UpdatedEvents()

```csharp
public void UpdatedEvents()
```
#INC

