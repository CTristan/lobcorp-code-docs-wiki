---
uid: Global.CreatureDataLoader
canonical_path: /api/Global/Loader/CreatureDataLoader
---

# Class CreatureDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureDataLoader
```
Loads abnormality information from various XML files.

Requires that equipment is loaded first. (See [EquipmentDataLoader](/api/Global/Loader/EquipmentDataLoader))

Loads stats, the animation handler, risk level, observation data, creature scripts, portraits, child creature data, sounds, and probably other things, too.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureDataLoader()

```csharp
public CreatureDataLoader()
```

## Fields

### currentLn

```csharp
public string currentLn
```

#### Field Value

**Type:** System.String

### documentSrcFormat

```csharp
public string documentSrcFormat
```

#### Field Value

**Type:** System.String

## Methods

### ConvertToDamageInfo(XmlNode)

```csharp
public static DamageInfo ConvertToDamageInfo(XmlNode damageNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.DamageInfo

### ConvertToRWBP(string)

```csharp
public static RwbpType ConvertToRWBP(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** Global.RwbpType

### GetBooleanData(string)

```csharp
public bool GetBooleanData(string b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### GetCreatureDataList(XmlNodeList, string, bool)

```csharp
public CreatureTypeInfo.CreatureDataList GetCreatureDataList(XmlNodeList nodes, string itemName, bool isInt)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodes` | `System.Xml.XmlNodeList` |  |
| `itemName` | `System.String` |  |
| `isInt` | `System.Boolean` |  |

#### Returns

**Type:** Global.CreatureTypeInfo.CreatureDataList

### GetCreatureEventCallTime(string)

```csharp
public CreatureEventCallTime GetCreatureEventCallTime(string time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.String` |  |

#### Returns

**Type:** Global.CreatureEventCallTime

### Load()

```csharp
public void Load()
```
#INC


### LoadChildMeta(string, ref List<CreatureSpecialSkillTipTable>, ref Dictionary<long, int>, bool)

```csharp
public CreatureTypeInfo LoadChildMeta(string src, ref List<CreatureSpecialSkillTipTable> creatureSpecialSkillTipList, ref Dictionary<long, int> specialTipSizeLib, bool isMod)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `creatureSpecialSkillTipList` | `System.Collections.Generic.List{CreatureSpecialSkillTipTable}` |  |
| `specialTipSizeLib` | `System.Collections.Generic.Dictionary{System.Int64,System.Int32}` |  |
| `isMod` | `System.Boolean` |  |

#### Returns

**Type:** Global.CreatureTypeInfo

### LoadCollectionIntegerItem(XmlNode, ref int)

```csharp
public int LoadCollectionIntegerItem(XmlNode node, ref int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `System.Xml.XmlNode` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### LoadCollectionItem(XmlNode, string, ref int)

```csharp
public string LoadCollectionItem(XmlNode collection, string target, ref int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Xml.XmlNode` |  |
| `target` | `System.String` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.String

### LoadCollectionStringItem(XmlNode, ref int)

```csharp
public string LoadCollectionStringItem(XmlNode node, ref int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `System.Xml.XmlNode` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.String

### LoadCreatureCollectionInfo(XmlNode, CreatureTypeInfo)

```csharp
public void LoadCreatureCollectionInfo(XmlNode collection, CreatureTypeInfo model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Xml.XmlNode` |  |
| `model` | `Global.CreatureTypeInfo` |  |

### LoadCreatureStat(XmlNode, XmlNode, CreatureTypeInfo)

```csharp
private void LoadCreatureStat(XmlNode stat, XmlNode statCreature, CreatureTypeInfo model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stat` | `System.Xml.XmlNode` |  |
| `statCreature` | `System.Xml.XmlNode` |  |
| `model` | `Global.CreatureTypeInfo` |  |

### LoadCreatureTypeInfo(XmlDocument, ref List<CreatureSpecialSkillTipTable>, ref Dictionary<long, int>, out ChildCreatureData)

```csharp
public CreatureTypeInfo LoadCreatureTypeInfo(XmlDocument doc, ref List<CreatureSpecialSkillTipTable> creatureSpecialSkillTipList, ref Dictionary<long, int> specialTipSizeLib, out ChildCreatureData childData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `doc` | `System.Xml.XmlDocument` |  |
| `creatureSpecialSkillTipList` | `System.Collections.Generic.List{CreatureSpecialSkillTipTable}` |  |
| `specialTipSizeLib` | `System.Collections.Generic.Dictionary{System.Int64,System.Int32}` |  |
| `childData` | `Global.ChildCreatureData` |  |

#### Returns

**Type:** Global.CreatureTypeInfo

### LoadDoc(string, string, bool)

```csharp
public XmlDocument LoadDoc(string src, string currentLn, bool IsMod = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `currentLn` | `System.String` |  |
| `IsMod` | `System.Boolean` |  |

#### Returns

**Type:** System.Xml.XmlDocument

### Loading(XmlNodeList, List<CreatureTypeInfo>, List<CreatureSpecialSkillTipTable>, Dictionary<long, int>, bool)

```csharp
public void Loading(XmlNodeList xmlNodeList, List<CreatureTypeInfo> list, List<CreatureSpecialSkillTipTable> list2, Dictionary<long, int> specialTipSize, bool isMod = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xmlNodeList` | `System.Xml.XmlNodeList` |  |
| `list` | `System.Collections.Generic.List{CreatureTypeInfo}` |  |
| `list2` | `System.Collections.Generic.List{CreatureSpecialSkillTipTable}` |  |
| `specialTipSize` | `System.Collections.Generic.Dictionary{System.Int64,System.Int32}` |  |
| `isMod` | `System.Boolean` |  |

### LoadSkillTrigger(XmlNode, CreatureTypeInfo)

```csharp
public void LoadSkillTrigger(XmlNode triggerRoot, CreatureTypeInfo typeinfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triggerRoot` | `System.Xml.XmlNode` |  |
| `typeinfo` | `Global.CreatureTypeInfo` |  |

### ReLoad()

```csharp
public void ReLoad()
```

### SkillTriggerClearEvent(XmlNode)

```csharp
public SkillTrigger.ClearEvent SkillTriggerClearEvent(XmlNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.SkillTrigger.ClearEvent
