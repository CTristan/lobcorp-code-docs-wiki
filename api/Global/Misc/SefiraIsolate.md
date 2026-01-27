---
uid: Global.SefiraIsolate
canonical_path: /api/Global/Misc/SefiraIsolate
---

# Class SefiraIsolate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraIsolate
```
Represents a place in the map for a [containment unit](/api/Global/IOBserver/IsolateRoom) in some [department](/api/Global/Misc/Sefira).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraIsolate

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraIsolate()

```csharp
public SefiraIsolate()
```

## Fields

### creatureId

```csharp
public long creatureId
```
#INC


#### Field Value

**Type:** System.Int64

### exclusiveID

```csharp
public List<long> exclusiveID
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int64}

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### isUsed

```csharp
public bool isUsed
```
#INC


#### Field Value

**Type:** System.Boolean

### nodeId

```csharp
public string nodeId
```
#INC


#### Field Value

**Type:** System.String

### pos

```csharp
public IsolatePos pos
```
#INC


#### Field Value

**Type:** Global.IsolatePos

### x

```csharp
public float x
```
#INC


#### Field Value

**Type:** System.Single

### y

```csharp
public float y
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### isExclusive(long)

```csharp
public bool isExclusive(long target)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean
