---
uid: Manual.MainCategory
canonical_path: /api/Manual/MainCategory
---

# Class MainCategory

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MainCategory : Category
```

Entries on the left with subcategories. Maybe.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Category](/api/Manual/Category) → MainCategory

## Inherited Members
[id](/api/Manual/Category#id), [title](/api/Manual/Category#title), [prev](/api/Manual/Category#prev), [next](/api/Manual/Category#next), [parent](/api/Manual/Category#parent), [Reload()](/api/Manual/Category#reload), [Title](/api/Manual/Category#title), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MainCategory(string, int)

```csharp
public MainCategory(string id, int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `index` | `System.Int32` |  |

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
public const string localizeTextFormat = "Manual_MainCategory_{0}"
```
#INC


#### Field Value

**Type:** System.String

### subCategories

```csharp
public List<SubCategory> subCategories
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Manual.SubCategory}

## Methods

### LoadText()

```csharp
public override void LoadText()
```
#INC
#code-generated

