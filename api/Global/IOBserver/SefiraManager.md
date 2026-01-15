---
uid: Global.SefiraManager
canonical_path: /api/Global/IOBserver/SefiraManager
---

# Class SefiraManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraManager()

```csharp
private SefiraManager()
```

## Fields

### _GenNodeSefiraTable

```csharp
private Dictionary<string, SefiraEnum> _GenNodeSefiraTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SefiraEnum}

### _instance

```csharp
private static SefiraManager _instance
```

#### Field Value

**Type:** Global.SefiraManager

### _sefiraDic

```csharp
private Dictionary<SefiraEnum, Sefira> _sefiraDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,Sefira}

### activatedSefira

```csharp
private List<Sefira> activatedSefira
```

#### Field Value

**Type:** System.Collections.Generic.List{Sefira}

### isLoadedOfficerSpecialAction

```csharp
public bool isLoadedOfficerSpecialAction
```

#### Field Value

**Type:** System.Boolean

### isLoadedSefiaIsolateData

```csharp
public bool isLoadedSefiaIsolateData
```

#### Field Value

**Type:** System.Boolean

### SefiraCharacterSpritePosfix

```csharp
public const string SefiraCharacterSpritePosfix = "_portrait"
```

#### Field Value

**Type:** System.String

### SefiraCharacterSpritePrefix

```csharp
public const string SefiraCharacterSpritePrefix = "Sprites/Sefira/Character/"
```

#### Field Value

**Type:** System.String

### sefiraIndexMax

```csharp
public int sefiraIndexMax
```

#### Field Value

**Type:** System.Int32

### sefiraList

```csharp
public List<Sefira> sefiraList
```

#### Field Value

**Type:** System.Collections.Generic.List{Sefira}

## Properties

### instance

```csharp
public static SefiraManager instance { get; }
```

#### Property Value

**Type:** Global.SefiraManager

## Methods

### AddActivatedSefira(Sefira)

```csharp
public void AddActivatedSefira(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

### AddCreature(long, SefiraIsolate, string)

```csharp
private CreatureModel AddCreature(long metadataId, SefiraIsolate sefiraIsolateData, string sefiraNum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `sefiraIsolateData` | `Global.SefiraIsolate` |  |
| `sefiraNum` | `System.String` |  |

#### Returns

**Type:** Global.CreatureModel

### AddCreature(long[], Sefira)

```csharp
private void AddCreature(long[] list, Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Int64[]` |  |
| `sefira` | `Global.Sefira` |  |

### AddCreature_Debug(SefiraEnum)

```csharp
private void AddCreature_Debug(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### CheckEscapedState()

```csharp
public bool CheckEscapedState()
```

#### Returns

**Type:** System.Boolean

### CheckGameState()

```csharp
private void CheckGameState()
```

### Clear()

```csharp
public void Clear()
```

### ClearOfficer()

```csharp
public void ClearOfficer()
```

### ClearUnitData()

```csharp
public void ClearUnitData()
```

### DisabledSefira(Sefira)

```csharp
public void DisabledSefira(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

### GameOverCheck()

```csharp
public bool GameOverCheck()
```

#### Returns

**Type:** System.Boolean

### GetActivatedSefiras()

```csharp
public Sefira[] GetActivatedSefiras()
```

#### Returns

**Type:** Global.Sefira[]

### GetCreatureGenerationList(int)

```csharp
private long[] GetCreatureGenerationList(int openLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `openLevel` | `System.Int32` |  |

#### Returns

**Type:** System.Int64[]

### GetCreatureGenerationList(SefiraEnum, int)

```csharp
private long[] GetCreatureGenerationList(SefiraEnum sefiraEnum, int openLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |
| `openLevel` | `System.Int32` |  |

#### Returns

**Type:** System.Int64[]

### GetEscapedCreatures()

```csharp
public List<CreatureModel> GetEscapedCreatures()
```

#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### GetOfficerAliveLevel(SefiraEnum)

```csharp
public int GetOfficerAliveLevel(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Int32

### GetOpendSefiraList()

```csharp
public Sefira[] GetOpendSefiraList()
```

#### Returns

**Type:** Global.Sefira[]

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSefira(int)

```csharp
public Sefira GetSefira(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.Sefira

### GetSefira(SefiraEnum)

```csharp
public Sefira GetSefira(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.Sefira

### GetSefira(string)

```csharp
public Sefira GetSefira(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** Global.Sefira

### GetSefiraByGenNodeId(string, out Sefira)

```csharp
public bool GetSefiraByGenNodeId(string id, out Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** System.Boolean

### GetSefiraLevel(SefiraEnum)

```csharp
public SefiraLevel GetSefiraLevel(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.SefiraLevel

### GetSefiraOpenLevel(SefiraEnum)

```csharp
public int GetSefiraOpenLevel(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
private void Init()
```

### IsOpened(SefiraEnum)

```csharp
public bool IsOpened(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### IsOpened(string)

```csharp
public bool IsOpened(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadSefiraSprite(SefiraEnum)

```csharp
public Sprite LoadSefiraSprite(SefiraEnum targetSefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetSefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** UnityEngine.Sprite

### MakeTutorialCreature()

```csharp
public void MakeTutorialCreature()
```

### OnFixedUpdate()

```csharp
private void OnFixedUpdate()
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

### OnStageStart_first()

```csharp
public void OnStageStart_first()
```

### OpenSefira(SefiraEnum)

```csharp
public void OpenSefira(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### OpenSefiraWithCreature(SefiraEnum)

```csharp
public void OpenSefiraWithCreature(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### OpenSefiraWithCreatureDebug(SefiraEnum)

```csharp
public void OpenSefiraWithCreatureDebug(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### ResetPassageData()

```csharp
public void ResetPassageData()
```

### SefiraIsolateLoad(Dictionary<string, SefiraEnum>)

```csharp
public void SefiraIsolateLoad(Dictionary<string, SefiraEnum> table)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `table` | `System.Collections.Generic.Dictionary{System.String,SefiraEnum}` |  |

### StartValidateCheck(ref Sefira)

```csharp
public bool StartValidateCheck(ref Sefira notallocated)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notallocated` | `Global.Sefira` |  |

#### Returns

**Type:** System.Boolean
