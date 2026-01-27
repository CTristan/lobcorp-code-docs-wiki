---
uid: Global.OfficerManager
canonical_path: /api/Global/Misc/OfficerManager
---

# Class OfficerManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerManager
```
Manages the list of clerks.

Holds an ID which is incremented by one each time a new clerk is added. Also holds the first part of clerks' names.

## Methods

#### OfficerModel CreateOfficerModel(string sefira)
Creates a new clerk in the specified department (*sefira*) with the next ID.
#### private static string GetRandomName(string sefira)
Generates a name by randomly selecting the first part and appending the current clerk count to it. (Ignores *sefira*.)
#### OfficerModel CreateDebugOfficer()
Creates a default clerk, for debugging.
#### OfficerModel CreateDebugOfficer(string nodeId)
Creates a default clerk at the specified node, for debugging.

#### IList\<OfficerModel> GetOfficerList()
Returns a read-only list of clerks.
#### OfficerModel\[] GetNearOfficers(MoveableObjectNode node)
Gets a list of living officers in the same room as *node*.

#### void Clear()
Clears clerks with ClearOfficer and Init.
#### void ClearOfficer()
Notifies each clerk and disables their [MovableObjectNode](/api/Global/Misc/MovableObjectNode), then refreshes the list and calls [SefiraManager](/api/Global/IOBserver/SefiraManager) to clear its clerks.
#### void Init()
Resets the list of clerks.


#### void OnStageEnd()
Calls OnStageEnd for each clerk.
#### void OnStageRelease()
Calls OnStageRelease for each clerk, then clears the list.
#### void OnFixedUpdate()
Calls OnFixedUpdate() for each clerk.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OfficerManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OfficerManager()

```csharp
public OfficerManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static OfficerManager _instance
```
#INC


#### Field Value

**Type:** Global.OfficerManager

### agentImgRange

```csharp
private static int agentImgRange
```
#INC


#### Field Value

**Type:** System.Int32

### isLoadedActionList

```csharp
public bool isLoadedActionList
```
#INC


#### Field Value

**Type:** System.Boolean

### nameList

```csharp
public static string[] nameList
```
#INC


#### Field Value

**Type:** System.String[]

### nextInstId

```csharp
private long nextInstId
```
#INC


#### Field Value

**Type:** System.Int64

### officerList

```csharp
private List<OfficerModel> officerList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OfficerModel}

## Properties

### instance

```csharp
public static OfficerManager instance { get; }
```

#### Property Value

**Type:** Global.OfficerManager

## Methods

### Clear()

```csharp
public void Clear()
```
#INC


### ClearOfficer()

```csharp
public void ClearOfficer()
```
#INC


### CreateDebugOfficer()

```csharp
public OfficerModel CreateDebugOfficer()
```
#INC


#### Returns

**Type:** Global.OfficerModel

### CreateDebugOfficer(string)

```csharp
public OfficerModel CreateDebugOfficer(string nodeId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeId` | `System.String` |  |

#### Returns

**Type:** Global.OfficerModel

### CreateOfficerModel(string)

```csharp
public OfficerModel CreateOfficerModel(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** Global.OfficerModel

### GetNearOfficers(MovableObjectNode)

```csharp
public OfficerModel[] GetNearOfficers(MovableObjectNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.OfficerModel[]

### GetOfficerList()

```csharp
public IList<OfficerModel> GetOfficerList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{OfficerModel}

### GetRandomName(string)

```csharp
private static string GetRandomName(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** System.String

### Init()

```csharp
public void Init()
```
#INC


### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC

