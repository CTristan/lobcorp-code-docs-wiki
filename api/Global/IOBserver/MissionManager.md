---
uid: Global.MissionManager
canonical_path: /api/Global/IOBserver/MissionManager
---

# Class MissionManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MissionManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MissionManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MissionManager()

```csharp
private MissionManager()
```

## Fields

### _instance

```csharp
private static MissionManager _instance
```

#### Field Value

**Type:** Global.MissionManager

### clearedMissions

```csharp
private List<Mission> clearedMissions
```

#### Field Value

**Type:** System.Collections.Generic.List{Mission}

### closedMissions

```csharp
private List<Mission> closedMissions
```

#### Field Value

**Type:** System.Collections.Generic.List{Mission}

### missionsInProgress

```csharp
private List<Mission> missionsInProgress
```

#### Field Value

**Type:** System.Collections.Generic.List{Mission}

### remainMissions

```csharp
private List<Mission> remainMissions
```

#### Field Value

**Type:** System.Collections.Generic.List{Mission}

## Properties

### instance

```csharp
public static MissionManager instance { get; }
```

#### Property Value

**Type:** Global.MissionManager

## Methods

### CheckMissionComplete(SefiraEnum)

```csharp
public Mission CheckMissionComplete(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Mission

### ClearMission(Mission)

```csharp
public void ClearMission(Mission m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.Mission` |  |

### CloseClearedMission(Mission)

```csharp
public void CloseClearedMission(Mission m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.Mission` |  |

### CloseClearedMission_ExceptBoss(SefiraEnum)

```csharp
public void CloseClearedMission_ExceptBoss(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### DebugMissionClear(int)

```csharp
public void DebugMissionClear(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### ExistsBossMission()

```csharp
public bool ExistsBossMission()
```

#### Returns

**Type:** System.Boolean

### ExistsBossMission(SefiraEnum)

```csharp
public bool ExistsBossMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### ExistsClearedMission(SefiraEnum)

```csharp
public bool ExistsClearedMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### ExistsFinishedBossMission()

```csharp
public bool ExistsFinishedBossMission()
```

#### Returns

**Type:** System.Boolean

### ExistsFinishedBossMission(SefiraEnum)

```csharp
public bool ExistsFinishedBossMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### GetAvailableMission(SefiraEnum)

```csharp
public Mission GetAvailableMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Mission

### GetAvailableMission(SefiraEnum, out List<string>, out bool)

```csharp
public Mission GetAvailableMission(SefiraEnum sefira, out List<string> requireTextList, out bool isBossMission)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `requireTextList` | `System.Collections.Generic.List{System.String}` |  |
| `isBossMission` | `System.Boolean` |  |

#### Returns

**Type:** Global.Mission

### GetBossMission(SefiraEnum)

```csharp
public Mission GetBossMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Mission

### GetClearedMissions()

```csharp
public List<Mission> GetClearedMissions()
```

#### Returns

**Type:** System.Collections.Generic.List{Mission}

### GetClearedOrClosedBossMissionNum()

```csharp
public int GetClearedOrClosedBossMissionNum()
```

#### Returns

**Type:** System.Int32

### GetClearedOrClosedBossMissions()

```csharp
public List<Mission> GetClearedOrClosedBossMissions()
```

#### Returns

**Type:** System.Collections.Generic.List{Mission}

### GetClearedOrClosedMissionNum(SefiraEnum)

```csharp
public int GetClearedOrClosedMissionNum(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Int32

### GetCurrentSefiraMission(SefiraEnum)

```csharp
public Mission GetCurrentSefiraMission(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Mission

### GetMissionsInProgress()

```csharp
public List<Mission> GetMissionsInProgress()
```

#### Returns

**Type:** System.Collections.Generic.List{Mission}

### GetNextMission(SefiraEnum, out List<string>, out bool)

```csharp
public Mission GetNextMission(SefiraEnum sefira, out List<string> requireTextList, out bool isBossMission)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `requireTextList` | `System.Collections.Generic.List{System.String}` |  |
| `isBossMission` | `System.Boolean` |  |

#### Returns

**Type:** Global.Mission

### GetReadyToClearMission(SefiraEnum)

```csharp
public Mission GetReadyToClearMission(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Mission

### GetReadyToClearMissions()

```csharp
public List<Mission> GetReadyToClearMissions()
```

#### Returns

**Type:** System.Collections.Generic.List{Mission}

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Init()

```csharp
public void Init()
```

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```

### ReleaseGame()

```csharp
public void ReleaseGame()
```

### RemoveTutorialMission()

```csharp
public void RemoveTutorialMission()
```

### StartMission(int)

```csharp
public void StartMission(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### StartTutorialMission()

```csharp
public void StartTutorialMission()
```
