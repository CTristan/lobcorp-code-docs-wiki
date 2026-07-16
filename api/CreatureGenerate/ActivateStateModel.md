---
title: ActivateStateModel
description: 
published: true
date: 2026-07-16T20:53:48.419Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:11.402Z
---

# Class ActivateStateModel
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ActivateStateModel
```

Stores the state of an abnormality for extraction, including flags indicating whether it is currently in the facility, has been removed for this extraction, and is a tool abnormality.

See [Abnormality Extraction](/abnormality-extraction).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ActivateStateModel

## Constructors
### ActivateStateModel()
```csharp
public ActivateStateModel()
```
Default constructor.

## Fields
### id
```csharp
public long id
```
The ID of the represented abnormality.

#### Field Value
**Type:** System.Int64

### isKit
```csharp
public bool isKit
```
Flag which is true when this is a tool abnormality.

#### Field Value
**Type:** System.Boolean

### isRemoved
```csharp
public bool isRemoved
```
Flag which is true when this abnormality is banned for this day.

#### Field Value
**Type:** System.Boolean

### isUsed
```csharp
public bool isUsed
```
Flag which is true when this abnormality is in the facility or in the queue. Note that days without data incorrectly ignore this condition.

#### Field Value
**Type:** System.Boolean

### riskLevel
```csharp
public RiskLevel riskLevel
```
The risk level of the represented abnormality. Not used.

#### Field Value
**Type:** Global.RiskLevel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









