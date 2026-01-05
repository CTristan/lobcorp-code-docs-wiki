# Class SefiraBossManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraBossManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraBossManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

### EndingStartDay

```csharp
public const int EndingStartDay = 45
```

#### Field Value

**Type:** System.Int32

### ketherSaveRegions

```csharp
public static string[] ketherSaveRegions
```

#### Field Value

**Type:** System.String[]

### keyValues

```csharp
public static string[] keyValues
```

#### Field Value

**Type:** System.String[]

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
public SefiraBossBase CurrentBossBase { get; }
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

### CheckBossActivation(SefiraEnum)

```csharp
public bool CheckBossActivation(SefiraEnum sefira)
```

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

#### Returns

**Type:** System.Boolean

### ForcelyClear()

```csharp
public void ForcelyClear()
```

### GenerateHodBuf()

```csharp
public void GenerateHodBuf()
```

### GenYesodBossSetting()

```csharp
public void GenYesodBossSetting()
```

### GetKetherBossType()

```csharp
public KetherBossType GetKetherBossType()
```

#### Returns

**Type:** Global.KetherBossType

### GetWorkId(int)

```csharp
public int GetWorkId(int id)
```

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

### IsAnyBossSessionActivated()

```csharp
public bool IsAnyBossSessionActivated()
```

#### Returns

**Type:** System.Boolean

### IsBossReady(SefiraEnum)

```csharp
public bool IsBossReady(SefiraEnum sefira)
```

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

#### Returns

**Type:** System.Boolean

### IsKetherBoss()

```csharp
public bool IsKetherBoss()
```

#### Returns

**Type:** System.Boolean

### IsKetherBoss(KetherBossType)

```csharp
public bool IsKetherBoss(KetherBossType type)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

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

### OnOverloadActivated(int)

```csharp
public void OnOverloadActivated(int currentValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentValue` | `System.Int32` |  |

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnStartBossSession(SefiraEnum)

```csharp
public bool OnStartBossSession(SefiraEnum sefira)
```

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

### OnUpdate()

```csharp
public void OnUpdate()
```

### PlayBossBgm(int)

```csharp
public void PlayBossBgm(int index = -1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### RandomizeWorkId()

```csharp
public void RandomizeWorkId()
```

### ResetYesodBossSetting()

```csharp
public void ResetYesodBossSetting()
```

### SaveBossSessionData(Dictionary<string, object>)

```csharp
public void SaveBossSessionData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### SetActivatedBoss(SefiraEnum)

```csharp
public void SetActivatedBoss(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### SetRecoverBlockState(bool)

```csharp
public void SetRecoverBlockState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetWorkCancelableState(bool)

```csharp
public void SetWorkCancelableState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### TryGetBossDesc(SefiraEnum, SefiraBossDescType, int, out string)

```csharp
public bool TryGetBossDesc(SefiraEnum sefira, SefiraBossDescType type, int index, out string text)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `type` | `Global.SefiraBossDescType` |  |
| `max` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean
