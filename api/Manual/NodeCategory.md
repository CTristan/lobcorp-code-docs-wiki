---
uid: Manual.NodeCategory
canonical_path: /api/Manual/NodeCategory
---

# Class NodeCategory

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class NodeCategory : Category
```

uh..
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Category](/api/Manual/Category) → NodeCategory

## Inherited Members
[id](/api/Manual/Category#id), [title](/api/Manual/Category#title), [prev](/api/Manual/Category#prev), [next](/api/Manual/Category#next), [parent](/api/Manual/Category#parent), [Reload()](/api/Manual/Category#reload), [Title](/api/Manual/Category#title), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### NodeCategory(string, int, string)

```csharp
public NodeCategory(string id, int index, string spriteId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `index` | `System.Int32` |  |
| `spriteId` | `System.String` |  |

### NodeCategory(string, string)

```csharp
public NodeCategory(string id, string spriteId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `spriteId` | `System.String` |  |

## Fields

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### localizeTextFormat

```csharp
public const string localizeTextFormat = "Manual_Node_{0}"
```
#INC


#### Field Value

**Type:** System.String

### spriteId

```csharp
public string spriteId
```
#INC


#### Field Value

**Type:** System.String

### textInfo

```csharp
public NodeTextInfo textInfo
```
#INC


#### Field Value

**Type:** Manual.NodeTextInfo

## Methods

### LoadText()

```csharp
public override void LoadText()
```
#INC
#code-generated

