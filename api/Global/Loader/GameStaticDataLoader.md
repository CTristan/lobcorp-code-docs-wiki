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

#### Field Value

**Type:** System.String

## Methods

### GetAngelaMessage(XmlNode)

```csharp
private AngelaMessage[] GetAngelaMessage(XmlNode root)
```

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

### LoadAgentNameInfoXml(string, bool)

```csharp
private List<AgentNameTypeInfo> LoadAgentNameInfoXml(string xml, bool isExternal)
```

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

### LoadCreditData()

```csharp
public static void LoadCreditData()
```

### LoadFactionData()

```csharp
public void LoadFactionData()
```

### LoadHierarchicalData()

```csharp
public void LoadHierarchicalData()
```

### LoadItemObjectData()

```csharp
private void LoadItemObjectData()
```

### LoadLyricData()

```csharp
public void LoadLyricData()
```

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

### LoadOfficerActionList()

```csharp
private void LoadOfficerActionList()
```

### LoadPanicData()

```csharp
public void LoadPanicData()
```

### LoadRandomEventInfo()

```csharp
public void LoadRandomEventInfo()
```

### LoadResearchDescData(List<ResearchItemTypeInfo>)

```csharp
public void LoadResearchDescData(List<ResearchItemTypeInfo> research)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `research` | `System.Collections.Generic.List{ResearchItemTypeInfo}` |  |

### LoadResearchItemData()

```csharp
public void LoadResearchItemData()
```

### LoadSefiraDescData()

```csharp
public void LoadSefiraDescData()
```

### LoadSefiraIsolateData()

```csharp
public void LoadSefiraIsolateData()
```

### LoadSKillData()

```csharp
public void LoadSKillData()
```

### LoadSpriteLoadingData()

```csharp
private void LoadSpriteLoadingData()
```

### LoadStageRewardData()

```csharp
public void LoadStageRewardData()
```

### LoadStaticData()

```csharp
public static void LoadStaticData()
```

### LoadTutorialData()

```csharp
public void LoadTutorialData()
```

### LoadTutorialNode(XmlNodeList, string)

```csharp
private TutorialNode[] LoadTutorialNode(XmlNodeList list, string rootSrc)
```

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

### ReloadData()

```csharp
public static void ReloadData()
```
