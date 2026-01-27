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
A list of [rooms](/api/Global/Model/PassageObjectModel) and [nodes](/api/Global/Misc/MapNode) for a given department.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapSefiraArea

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapSefiraArea()

```csharp
public MapSefiraArea()
```
#INC
#code-generated


## Fields

### nodeList

```csharp
private List<MapNode> nodeList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### passageObjects

```csharp
private List<PassageObjectModel> passageObjects
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### sefiraName

```csharp
public string sefiraName
```
#INC


#### Field Value

**Type:** System.String

## Methods

### ActivateArea()

```csharp
public void ActivateArea()
```
#INC


### ActivateArea(string)

```csharp
public void ActivateArea(string passageGroupName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passageGroupName` | `System.String` |  |

### AddNode(MapNode)

```csharp
public void AddNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AddPassage(PassageObjectModel)

```csharp
public void AddPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### DeactivateArea()

```csharp
public void DeactivateArea()
```
#INC


### GetActivatedAreas()

```csharp
public List<string> GetActivatedAreas()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetHorror()

```csharp
public int GetHorror()
```
#INC


#### Returns

**Type:** System.Int32

### GetNodeList()

```csharp
public MapNode[] GetNodeList()
```
#INC


#### Returns

**Type:** Global.MapNode[]

### GetRoamingPassageList()

```csharp
public PassageObjectModel[] GetRoamingPassageList()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel[]

### InitActivates()

```csharp
public void InitActivates()
```
#INC


### SetHorror()

```csharp
public void SetHorror()
```
#INC

