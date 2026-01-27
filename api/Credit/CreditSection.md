---
uid: Credit.CreditSection
canonical_path: /api/Credit/CreditSection
---

# Class CreditSection

**Namespace:** [Credit](/api/Credit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreditSection
```
#INC


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreditSection

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreditSection()

```csharp
public CreditSection()
```

## Fields

### list

```csharp
public List<CreditItem> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Credit.CreditItem}

### SectionName

```csharp
public string SectionName
```
#INC


#### Field Value

**Type:** System.String

### sectionType

```csharp
public CreditSectionType sectionType
```
#INC


#### Field Value

**Type:** Credit.CreditSectionType

## Methods

### BuildText(ref StringBuilder)

```csharp
public void BuildText(ref StringBuilder builder)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `builder` | `System.Text.StringBuilder` |  |
