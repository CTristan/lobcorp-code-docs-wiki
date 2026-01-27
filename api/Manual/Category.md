---
uid: Manual.Category
canonical_path: /api/Manual/Category
---

# Class Category

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Category
```
Sections on the left of the manual?


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Category

## Derived
[MainCategory](/api/Manual/MainCategory), [NodeCategory](/api/Manual/NodeCategory), [SubCategory](/api/Manual/SubCategory)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Category(string)

```csharp
public Category(string id)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

## Fields

### id

```csharp
public string id
```
#INC


#### Field Value

**Type:** System.String

### next

```csharp
public Category next
```
#INC


#### Field Value

**Type:** Manual.Category

### parent

```csharp
public Category parent
```
#INC


#### Field Value

**Type:** Manual.Category

### prev

```csharp
public Category prev
```
#INC


#### Field Value

**Type:** Manual.Category

### title

```csharp
protected string title
```
#INC


#### Field Value

**Type:** System.String

## Properties

### Title

```csharp
public virtual string Title { get; }
```

#### Property Value

**Type:** System.String

## Methods

### LoadText()

```csharp
public virtual void LoadText()
```
#INC


### Reload()

```csharp
public void Reload()
```
#INC

