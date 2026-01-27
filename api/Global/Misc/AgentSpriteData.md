---
uid: Global.AgentSpriteData
canonical_path: /api/Global/Misc/AgentSpriteData
---

# Class AgentSpriteData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentSpriteData
```
Stores sprite information about an [agent](/api/Global/Worker/AgentUnit).

Used by [AgentPortrait](/api/Global/Misc/AgentPortrait)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentSpriteData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentSpriteData()

```csharp
public AgentSpriteData()
```

## Fields

### agent

```csharp
public AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### Sets

```csharp
public WorkerSpriteSet Sets
```
#INC


#### Field Value

**Type:** Global.WorkerSpriteSet

## Properties

### Face

```csharp
public Sprite Face { get; }
```

#### Property Value

**Type:** UnityEngine.Sprite

### Hair

```csharp
public Sprite Hair { get; }
```

#### Property Value

**Type:** UnityEngine.Sprite

## Methods

### Init(AgentModel)

```csharp
public void Init(AgentModel agent)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
