---
uid: Global.SefiraBossManager
canonical_path: /api/Global/IOBserver/SefiraBossManager
---

# Class SefiraBossManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraBossManager : IObserver
```

Manages [core suppressions](/api/Global/Misc/SefiraBossBase).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraBossManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraBossManager()

```csharp
private SefiraBossManager()
```
#INC
#code-generated


## Fields

### _bossBgmDic

```csharp
private Dictionary<int, string> _bossBgmDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.String}

### _clearState

```csharp
private Dictionary<string, bool> _clearState
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Boolean}

### _currentBossBase

```csharp
private SefiraBossBase _currentBossBase
```
#INC


#### Field Value

**Type:** Global.SefiraBossBase

### _instance

```csharp
private static SefiraBossManager _instance
```
#INC


#### Field Value

**Type:** Global.SefiraBossManager

### _isCleared

```csharp
private bool _isCleared
```
#INC


#### Field Value

**Type:** System.Boolean

### _isRecoverBlocked

```csharp
private bool _isRecoverBlocked
```
#INC


#### Field Value

**Type:** System.Boolean

### _isWorkCancelable

```csharp
private bool _isWorkCancelable
```
#INC


#### Field Value

**Type:** System.Boolean

### _tutorial

```csharp
private bool _tutorial
```
#INC


#### Field Value

**Type:** System.Boolean

### _tutorialPlayed

```csharp
private bool _tutorialPlayed
```
#INC


#### Field Value

**Type:** System.Boolean

### cameraScript

```csharp
private YesodBossCameraScript cameraScript
```
#INC


#### Field Value

**Type:** Global.YesodBossCameraScript

### currentActivated

```csharp
private SefiraEnum currentActivated
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### EndingStartDay

```csharp
public const int EndingStartDay = 45
```
#INC


#### Field Value

**Type:** System.Int32

### ketherKeyFormat

```csharp
private const string ketherKeyFormat = "boss_{0}_{2}_{1}_"
```
#INC


#### Field Value

**Type:** System.String

### ketherSaveRegions

```csharp
public static string[] ketherSaveRegions
```
#INC


#### Field Value

**Type:** System.String[]

### keyCountDic

```csharp
private Dictionary<string, int> keyCountDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### keyFormat

```csharp
private const string keyFormat = "boss_{0}_{1}_"
```
#INC


#### Field Value

**Type:** System.String

### keyTravelMax

```csharp
private const int keyTravelMax = 15
```
#INC


#### Field Value

**Type:** System.Int32

### keyValues

```csharp
public static string[] keyValues
```
#INC


#### Field Value

**Type:** System.String[]

### nextInstId

```csharp
private int nextInstId
```
#INC


#### Field Value

**Type:** System.Int32

### workId

```csharp
private int[] workId
```
#INC


#### Field Value

**Type:** System.Int32[]

### yesodCamera

```csharp
private const string yesodCamera = "Effect/SefiraBoss/YesodBossRenderCamera"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### ClearState

```csharp
public Dictionary<string, bool> ClearState { get; }
```

#### Property Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Boolean}

### CurrentActivatedSefira

```csharp
public SefiraEnum CurrentActivatedSefira { get; }
```

#### Property Value

**Type:** Global.SefiraEnum

### CurrentBossBase

```csharp
public SefiraBossBase CurrentBossBase { get; private set; }
```

#### Property Value

**Type:** Global.SefiraBossBase

### Instance

```csharp
public static SefiraBossManager Instance { get; }
```

#### Property Value

**Type:** Global.SefiraBossManager

### IsCleared

```csharp
public bool IsCleared { get; }
```

#### Property Value

**Type:** System.Boolean

### IsRecoverBlocked

```csharp
public bool IsRecoverBlocked { get; }
```

#### Property Value

**Type:** System.Boolean

### IsTutorial

```csharp
public bool IsTutorial { get; }
```

#### Property Value

**Type:** System.Boolean

### IsWorkCancelable

```csharp
public bool IsWorkCancelable { get; }
```

#### Property Value

**Type:** System.Boolean

### TutorialPlayed

```csharp
public bool TutorialPlayed { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddBossBgm(params string[])

```csharp
public void AddBossBgm(params string[] bgmSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bgmSrc` | `System.String[]` |  |

### AddCreature(MapNode, SefiraBossBase, string, string, long)

```csharp
public SefiraBossCreatureModel AddCreature(MapNode pos, SefiraBossBase sefiraBoss, string scriptName, string animName, long metaId = 400001)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `Global.MapNode` |  |
| `sefiraBoss` | `Global.SefiraBossBase` |  |
| `scriptName` | `System.String` |  |
| `animName` | `System.String` |  |
| `metaId` | `System.Int64` |  |

#### Returns

**Type:** Global.SefiraBossCreatureModel

### BuildCreature(SefiraBossCreatureModel, long, string)

```csharp
private void BuildCreature(SefiraBossCreatureModel model, long metadataid, string scriptName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.SefiraBossCreatureModel` |  |
| `metadataid` | `System.Int64` |  |
| `scriptName` | `System.String` |  |

### CheckBossActivation(SefiraEnum)

```csharp
public bool CheckBossActivation(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### DisplayTutorial()

```csharp
public bool DisplayTutorial()
```
#INC


#### Returns

**Type:** System.Boolean

### ForcelyClear()

```csharp
public void ForcelyClear()
```
#INC


### GenBossBase()

```csharp
private SefiraBossBase GenBossBase()
```
#INC


#### Returns

**Type:** Global.SefiraBossBase

### GenerateHodBuf()

```csharp
public void GenerateHodBuf()
```
#INC


### GenYesodBossSetting()

```csharp
public void GenYesodBossSetting()
```
#INC


### GetKetherBossType()

```csharp
public KetherBossType GetKetherBossType()
```
#INC


#### Returns

**Type:** Global.KetherBossType

### GetWorkId(int)

```csharp
public int GetWorkId(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
public void Init()
```
#INC


### IsAnyBossSessionActivated()

```csharp
public bool IsAnyBossSessionActivated()
```
#INC


#### Returns

**Type:** System.Boolean

### IsBossReady(SefiraEnum)

```csharp
public bool IsBossReady(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### IsBossStartable(SefiraEnum)

```csharp
public bool IsBossStartable(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### IsBossStartable(SefiraEnum, out List<string>)

```csharp
public bool IsBossStartable(SefiraEnum sefira, out List<string> require)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `require` | `System.Collections.Generic.List{System.String}` |  |

#### Returns

**Type:** System.Boolean

### IsClearedDay()

```csharp
public bool IsClearedDay()
```
#INC


#### Returns

**Type:** System.Boolean

### IsKetherBoss()

```csharp
public bool IsKetherBoss()
```
#INC


#### Returns

**Type:** System.Boolean

### IsKetherBoss(KetherBossType)

```csharp
public bool IsKetherBoss(KetherBossType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.KetherBossType` |  |

#### Returns

**Type:** System.Boolean

### LoadSaveData(Dictionary<string, object>)

```csharp
public void LoadSaveData(Dictionary<string, object> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnDestroy()

```csharp
private void OnDestroy()
```
#INC


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

### OnOverloadActivated(int)

```csharp
public void OnOverloadActivated(int currentValue)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentValue` | `System.Int32` |  |

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


### OnStartBossSession(SefiraEnum)

```csharp
public bool OnStartBossSession(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### OnTutorialEnd()

```csharp
public void OnTutorialEnd()
```
#INC


### OnUpdate()

```csharp
public void OnUpdate()
```
#INC


### PlayBossBgm(int)

```csharp
public void PlayBossBgm(int index = -1)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### RandomizeWorkId()

```csharp
public void RandomizeWorkId()
```
#INC


### ResetYesodBossSetting()

```csharp
public void ResetYesodBossSetting()
```
#INC


### SaveBossSessionData(Dictionary<string, object>)

```csharp
public void SaveBossSessionData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### SetActivatedBoss(SefiraEnum)

```csharp
public void SetActivatedBoss(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### SetKeyCounts()

```csharp
private void SetKeyCounts()
```
#INC


### SetRecoverBlockState(bool)

```csharp
public void SetRecoverBlockState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetWorkCancelableState(bool)

```csharp
public void SetWorkCancelableState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### TryGetBossDesc(SefiraEnum, SefiraBossDescType, int, out string)

```csharp
public bool TryGetBossDesc(SefiraEnum sefira, SefiraBossDescType type, int index, out string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `type` | `Global.SefiraBossDescType` |  |
| `index` | `System.Int32` |  |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### TryGetBossDesc(SefiraEnum, SefiraBossDescType, out string)

```csharp
public bool TryGetBossDesc(SefiraEnum sefira, SefiraBossDescType type, out string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `type` | `Global.SefiraBossDescType` |  |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### TryGetBossDescCount(SefiraEnum, SefiraBossDescType, out int)

```csharp
public bool TryGetBossDescCount(SefiraEnum sefira, SefiraBossDescType type, out int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `type` | `Global.SefiraBossDescType` |  |
| `max` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean
