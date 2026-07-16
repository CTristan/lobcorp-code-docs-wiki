---
title: CreatureGenerateData-ActionData
description: 
published: true
date: 2026-07-16T21:36:13.930Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:53:50.683Z
---

# Class CreatureGenerateData.ActionData
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateData.ActionData
```
Holds a delegate, `Action`, which is either [`CreatureGenerateData::OnlyAction`](/api/CreatureGenerate/CreatureGenerateData#onlyactionparams-object) or [`CreatureGenerateData::RemoveAction`](/api/CreatureGenerate/CreatureGenerateData#removeactionparams-object), for restricting abnormality selections on certain days.

See [`CreatureGenerateModel::OnlyAction`](/api/CreatureGenerate/CreatureGenerateModel#onlyactionparams-object) and [`CreatureGenerateModel::RemoveAction`](/api/CreatureGenerate/CreatureGenerateModel#removeactionparams-object) for the important implementations of this.

See also [Abnormality Extraction](/abnormality-extraction) for an overview of the abnormality extraction system.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureGenerateData.ActionData

## Constructors
### ActionData()
```csharp
public ActionData()
```
Default constructor.

## Fields
### action
```csharp
public CreatureGenerateData.Action action
```
The action to perform.

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateData.Action

### parameters
```csharp
public List<object> parameters
```
The stored list of parameters for the call to `action`.

#### Field Value
**Type:** System.Collections.Generic.List{System.Object}

### returnValue
```csharp
public object returnValue
```
Unused.

#### Field Value
**Type:** System.Object

## Methods
### Exectue()
```csharp
public void Exectue()
```
Executes `action` with the parameters `parameters`.

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







