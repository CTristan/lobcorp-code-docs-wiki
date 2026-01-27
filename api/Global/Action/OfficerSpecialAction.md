---
uid: Global.OfficerSpecialAction
canonical_path: /api/Global/Action/OfficerSpecialAction
---

# Class OfficerSpecialAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerSpecialAction
```
Not used.

Holds information for a [clerk](/api/Global/Worker/OfficerUnit) to move around.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OfficerSpecialAction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OfficerSpecialAction(int, string, int, string)

```csharp
public OfficerSpecialAction(int id, string nodeid, int animVal, string animParam)
```
Creates a new clerk action with the given parameters.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `nodeid` | `System.String` |  |
| `animVal` | `System.Int32` |  |
| `animParam` | `System.String` |  |

## Fields

### animParam

```csharp
public string animParam
```
#INC


#### Field Value

**Type:** System.String

### animVal

```csharp
public int animVal
```
#INC


#### Field Value

**Type:** System.Int32

### excutedPos

```csharp
private MapNode excutedPos
```
#INC


#### Field Value

**Type:** Global.MapNode

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### nodeId

```csharp
public string nodeId
```
#INC


#### Field Value

**Type:** System.String

### posData

```csharp
public List<OfficerSpecialAction.PosData> posData
```

#### Field Value

**Type:** System.Collections.Generic.List{OfficerSpecialAction.PosData}

### shouldMove

```csharp
public bool shouldMove
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### GetNode()

```csharp
public MapNode GetNode()
```
Gets the target node of this action and sets the position data to its position.


#### Returns

**Type:** Global.MapNode

### GetPos()

```csharp
public OfficerSpecialAction.PosData GetPos()
```

#### Returns

**Type:** Global.OfficerSpecialAction.PosData
