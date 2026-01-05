# Class MapGraph

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapGraph : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapGraph

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MapGraph()

```csharp
public MapGraph()
```

## Properties

### instance

```csharp
public static MapGraph instance { get; }
```

#### Property Value

**Type:** Global.MapGraph

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ActivateArea(string)

```csharp
public void ActivateArea(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### ActivateArea(string, string)

```csharp
public void ActivateArea(string name, string passageGroupName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `passageGroupName` | `System.String` |  |

### DeactivateAll()

```csharp
public void DeactivateAll()
```

### DeactivateArea(string)

```csharp
public void DeactivateArea(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### GetActivatedAreaList()

```csharp
public Dictionary<string, List<string>> GetActivatedAreaList()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}}

### GetAdditionalSefira(Sefira)

```csharp
public MapNode[] GetAdditionalSefira(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.MapNode[]

### GetAdditionalSefira(string)

```csharp
public MapNode[] GetAdditionalSefira(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode[]

### GetCreatureRoamingPoint()

```csharp
public MapNode GetCreatureRoamingPoint()
```

#### Returns

**Type:** Global.MapNode

### GetElevatorPassageList()

```csharp
public ElevatorPassageModel[] GetElevatorPassageList()
```

#### Returns

**Type:** Global.ElevatorPassageModel[]

### GetGraphEdges()

```csharp
public MapEdge[] GetGraphEdges()
```

#### Returns

**Type:** Global.MapEdge[]

### GetGraphNodes()

```csharp
public MapNode[] GetGraphNodes()
```

#### Returns

**Type:** Global.MapNode[]

### GetNodeById(string)

```csharp
public MapNode GetNodeById(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.MapNode

### GetPassageListByRabbitGroup(string)

```csharp
public List<PassageObjectModel> GetPassageListByRabbitGroup(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetPassageObjectList()

```csharp
public PassageObjectModel[] GetPassageObjectList()
```

#### Returns

**Type:** Global.PassageObjectModel[]

### GetRoamingNodeByRandom()

```csharp
public MapNode GetRoamingNodeByRandom()
```

#### Returns

**Type:** Global.MapNode

### GetRoamingNodeByRandom(string)

```csharp
public MapNode GetRoamingNodeByRandom(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode

### GetSefiraAllNodes(string)

```csharp
public MapNode[] GetSefiraAllNodes(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode[]

### GetSefiraAndDeptByRandom(string)

```csharp
public MapNode GetSefiraAndDeptByRandom(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode

### GetSefiraMovableNodeByRandom(string)

```csharp
public MovableObjectNode GetSefiraMovableNodeByRandom(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MovableObjectNode

### GetSefiraNodes(Sefira)

```csharp
public MapNode[] GetSefiraNodes(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.MapNode[]

### GetSefiraNodes(string)

```csharp
public MapNode[] GetSefiraNodes(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode[]

### GetSefiraPassage(string)

```csharp
public PassageObjectModel GetSefiraPassage(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.PassageObjectModel

### GetSefiraPassagePointNode(string)

```csharp
public MapNode[] GetSefiraPassagePointNode(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode[]

### GetSepiraNodeByRandom(string)

```csharp
public MapNode GetSepiraNodeByRandom(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** Global.MapNode

### LoadMap()

```csharp
public void LoadMap()
```

### LoadMap(XmlNode, XmlNode)

```csharp
public void LoadMap(XmlNode nodeRoot, XmlNode edgeRoot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Xml.XmlNode` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |

### LoadModMap(Dictionary<string, XmlNode>, XmlNode)

```csharp
public void LoadModMap(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |

### LoadModMap_Add(Dictionary<string, XmlNode>, XmlNode, XmlDocument)

```csharp
public void LoadModMap_Add(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot, XmlDocument mxml)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### LoadModMap_Replace(Dictionary<string, XmlNode>, XmlNode, XmlDocument)

```csharp
public void LoadModMap_Replace(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot, XmlDocument mxml)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### OnNotice(string, params object[])

```csharp
public void OnNotice(string name, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `param` | `System.Object[]` |  |

### RegisterPassage(PassageObjectModel)

```csharp
public void RegisterPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### Reset()

```csharp
public void Reset()
```
