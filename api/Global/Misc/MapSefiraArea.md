---
uid: Global.MapSefiraArea
canonical_path: /api/Global/Misc/MapSefiraArea
---

# Class MapSefiraArea

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapSefiraArea
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapSefiraArea

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapSefiraArea()

```csharp
public MapSefiraArea()
```

## Fields

### nodeList

```csharp
private List<MapNode> nodeList
```

#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### passageObjects

```csharp
private List<PassageObjectModel> passageObjects
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### sefiraName

```csharp
public string sefiraName
```

#### Field Value

**Type:** System.String

## Methods

### ActivateArea()

```csharp
public void ActivateArea()
```

### ActivateArea(string)

```csharp
public void ActivateArea(string passageGroupName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passageGroupName` | `System.String` |  |

### AddNode(MapNode)

```csharp
public void AddNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AddPassage(PassageObjectModel)

```csharp
public void AddPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### DeactivateArea()

```csharp
public void DeactivateArea()
```

### GetActivatedAreas()

```csharp
public List<string> GetActivatedAreas()
```

#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetHorror()

```csharp
public int GetHorror()
```

#### Returns

**Type:** System.Int32

### GetNodeList()

```csharp
public MapNode[] GetNodeList()
```

#### Returns

**Type:** Global.MapNode[]

### GetRoamingPassageList()

```csharp
public PassageObjectModel[] GetRoamingPassageList()
```

#### Returns

**Type:** Global.PassageObjectModel[]

### InitActivates()

```csharp
public void InitActivates()
```

### SetHorror()

```csharp
public void SetHorror()
```
