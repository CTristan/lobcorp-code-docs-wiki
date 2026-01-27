---
uid: Global.AgentPortrait
canonical_path: /api/Global/Misc/AgentPortrait
---

# Class AgentPortrait

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentPortrait
```
Holds an [agent](/api/Global/Worker/AgentUnit) and their sprite data.

Seems to be used by prefabs for some UI components.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentPortrait

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentPortrait()

```csharp
public AgentPortrait()
```

## Fields

### agent

```csharp
public AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### spriteData

```csharp
public AgentSpriteData spriteData
```
#INC


#### Field Value

**Type:** Global.AgentSpriteData

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
