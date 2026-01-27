---
uid: Global.SefiraIsolateManagement
canonical_path: /api/Global/Misc/SefiraIsolateManagement
---

# Class SefiraIsolateManagement

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraIsolateManagement
```
Manages [containment units](/api/Global/Misc/SefiraIsolate).

Provides methods to get unused rooms, get the [SefiraIsolate](/api/Global/Misc/SefiraIsolate) of a creature, and other things.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraIsolateManagement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraIsolateManagement(SefiraIsolate[])

```csharp
public SefiraIsolateManagement(SefiraIsolate[] ary)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.SefiraIsolate[]` |  |

## Fields

### _notUsed

```csharp
private List<SefiraIsolate> _notUsed
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraIsolate}

### _used

```csharp
private List<SefiraIsolate> _used
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraIsolate}

### list

```csharp
public List<SefiraIsolate> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraIsolate}

## Methods

### GenIsolateByCreatureAry(long[])

```csharp
public SefiraIsolate[] GenIsolateByCreatureAry(long[] creatureIdAry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureIdAry` | `System.Int64[]` |  |

#### Returns

**Type:** Global.SefiraIsolate[]

### GenIsolateByCreatureAryByOrder(long)

```csharp
public SefiraIsolate GenIsolateByCreatureAryByOrder(long creatureId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureId` | `System.Int64` |  |

#### Returns

**Type:** Global.SefiraIsolate

### GenIsolateByCreatureAryByOrder(long[])

```csharp
public SefiraIsolate[] GenIsolateByCreatureAryByOrder(long[] creatureIdAry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureIdAry` | `System.Int64[]` |  |

#### Returns

**Type:** Global.SefiraIsolate[]

### GenIsolateByCreatureByNodeId(long, string)

```csharp
public SefiraIsolate GenIsolateByCreatureByNodeId(long creatureId, string nodeId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureId` | `System.Int64` |  |
| `nodeId` | `System.String` |  |

#### Returns

**Type:** Global.SefiraIsolate

### GetByNodeId(string)

```csharp
public SefiraIsolate GetByNodeId(string nodeId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeId` | `System.String` |  |

#### Returns

**Type:** Global.SefiraIsolate

### GetNotUsed()

```csharp
public SefiraIsolate GetNotUsed()
```
#INC


#### Returns

**Type:** Global.SefiraIsolate

### GetNotUsedRandom(long)

```csharp
public SefiraIsolate GetNotUsedRandom(long targetId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetId` | `System.Int64` |  |

#### Returns

**Type:** Global.SefiraIsolate

### isExclusiveByIsolate(long)

```csharp
private bool isExclusiveByIsolate(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### LogRemain()

```csharp
public void LogRemain()
```
#INC

