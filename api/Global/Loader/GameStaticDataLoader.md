---
uid: Global.GameStaticDataLoader
canonical_path: /api/Global/Loader/GameStaticDataLoader
---

# Class GameStaticDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameStaticDataLoader
```
Loads a bunch of external static data, such as:

- [Font](/api/Global/Loader/ExternalFontDataLoader)
- [Localized text](/api/Global/Loader/LocalizeTextDataLoader)
- [Story data](/api/Global/Loader/StoryDataLoader)
- [Equipment data](/api/Global/Loader/EquipmentDataLoader)
- [Agent titles](/api/Global/Loader/AgentTitleDataLoader)
- [Missions](/api/Global/List/MissionTypeList)
- [Skill data](/api/Global/List/SkillTypeList) #INC 
- [Abnormality data](/api/Global/Loader/CreatureDataLoader)
- [Rabbit data](/api/Global/Loader/RabbitDataLoader)
- Lyrics (see [AgentLyrics](/api/Global/Misc/AgentLyrics), [CreatureLyrics](/api/Global/Misc/CreatureLyrics))
- [Research data](/api/Global/List/ResearchItemTypeList)
- [Sefira yapping](/api/Global/Misc/Conversation)
- [Angela yapping](/api/Global/Misc/AngelaConversation)
- [Clerk special actions](/api/Global/List/OfficerSpecialActionList) #inc
- [Agent names](/api/Global/List/AgentNameList)
- [Stage reward info](/api/Global/List/StageRewardTypeList)
- Containment unit locations? See [SefiraManager](/api/Global/IOBserver/SefiraManager) #INC 
- [Sprites](/api/Global/Misc/SpriteLoadManager)
- [Panic Data](/api/Global/List/PanicDataList) #inc
- [Hierarchical data](/api/Global/Misc/HierarchicalDataManager) #INC 
- [Faction](/api/Global/List/FactionTypeList) membership
- [Item objects](/api/Global/Misc/ItemObjectManager) (unused)
- [Random events](/api/Global/IOBserver/RandomEventManager) (unused)
- [Worker Spine data](/api/WorkerSpine/WorkerSpineAnimatorManager)

#inc (double check that these don't need to be linked to more loaders)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GameStaticDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GameStaticDataLoader()

```csharp
public GameStaticDataLoader()
```

## Fields

### __mg_cache0

```csharp
private static Comparison<CreditItem> __mg_cache0
```

#### Field Value

**Type:** System.Comparison{Credit.CreditItem}

### currentLn

```csharp
private static string currentLn
```
#INC


#### Field Value

**Type:** System.String

## Methods

### GetAngelaMessage(XmlNode)

```csharp
private AngelaMessage[] GetAngelaMessage(XmlNode root)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `root` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.AngelaMessage[]

### GetBooleanData(string)

```csharp
private bool GetBooleanData(string b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### GetLyricType(int)

```csharp
private LyricType GetLyricType(int type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

#### Returns

**Type:** Global.LyricType

### GetOfficerLookingDir(string)

```csharp
private LOOKINGDIR GetOfficerLookingDir(string dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `System.String` |  |

#### Returns

**Type:** Global.LOOKINGDIR

### LoadAgentNameData()

```csharp
public void LoadAgentNameData()
```
#INC


### LoadAgentNameInfoXml(string, bool)

```csharp
private List<AgentNameTypeInfo> LoadAgentNameInfoXml(string xml, bool isExternal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xml` | `System.String` |  |
| `isExternal` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### LoadAgentNameXml(string, bool)

```csharp
private List<AgentName> LoadAgentNameXml(string xml, bool isExternal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xml` | `System.String` |  |
| `isExternal` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentName}

### LoadAngelaDescData()

```csharp
public void LoadAngelaDescData()
```
#INC


### LoadCreditData()

```csharp
public static void LoadCreditData()
```
#INC


### LoadFactionData()

```csharp
public void LoadFactionData()
```
#INC


### LoadHierarchicalData()

```csharp
public void LoadHierarchicalData()
```
#INC


### LoadItemObjectData()

```csharp
private void LoadItemObjectData()
```
#INC


### LoadLyricData()

```csharp
public void LoadLyricData()
```
#INC


### LoadModIsolate(Dictionary<string, XmlNode>)

```csharp
public void LoadModIsolate(Dictionary<string, XmlNode> nodeRoot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |

### LoadModIsolate_Add(Dictionary<string, XmlNode>, XmlDocument)

```csharp
public void LoadModIsolate_Add(Dictionary<string, XmlNode> nodeRoot, XmlDocument mxml)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### LoadModIsolate_Replace(Dictionary<string, XmlNode>, XmlDocument)

```csharp
public void LoadModIsolate_Replace(Dictionary<string, XmlNode> nodeRoot, XmlDocument mxml)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### LoadNewLyricData()

```csharp
public void LoadNewLyricData()
```
#INC


### LoadOfficerActionList()

```csharp
private void LoadOfficerActionList()
```
#INC


### LoadPanicData()

```csharp
public void LoadPanicData()
```
#INC


### LoadRandomEventInfo()

```csharp
public void LoadRandomEventInfo()
```
#INC


### LoadResearchDescData(List<ResearchItemTypeInfo>)

```csharp
public void LoadResearchDescData(List<ResearchItemTypeInfo> research)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `research` | `System.Collections.Generic.List{ResearchItemTypeInfo}` |  |

### LoadResearchItemData()

```csharp
public void LoadResearchItemData()
```
#INC


### LoadSefiraDescData()

```csharp
public void LoadSefiraDescData()
```
#INC


### LoadSefiraIsolateData()

```csharp
public void LoadSefiraIsolateData()
```
#INC


### LoadSKillData()

```csharp
public void LoadSKillData()
```
#INC


### LoadSpriteLoadingData()

```csharp
private void LoadSpriteLoadingData()
```
#INC


### LoadStageRewardData()

```csharp
public void LoadStageRewardData()
```
#INC


### LoadStaticData()

```csharp
public static void LoadStaticData()
```
#INC
#code-generated


### LoadTutorialData()

```csharp
public void LoadTutorialData()
```
#INC


### LoadTutorialNode(XmlNodeList, string)

```csharp
private TutorialNode[] LoadTutorialNode(XmlNodeList list, string rootSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Xml.XmlNodeList` |  |
| `rootSrc` | `System.String` |  |

#### Returns

**Type:** Legacy.TutorialNode[]

### LoadUniqueCreditInfo(string)

```csharp
private List<UniqueCreditAgentInfo> LoadUniqueCreditInfo(string xml)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xml` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{UniqueCreditAgentInfo}

### LoadWorkerSpineData()

```csharp
public void LoadWorkerSpineData()
```
#INC


### ReloadData()

```csharp
public static void ReloadData()
```
#INC

