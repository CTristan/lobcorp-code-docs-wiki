---
uid: Global.AgentModelEventHandler
canonical_path: /api/Global/Misc/AgentModelEventHandler
---

# Class AgentModelEventHandler

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentModelEventHandler
```
Maintains a list of [agent](/api/Global/Worker/AgentUnit) events (see [AgentEventEnum](/api/Global/Misc/AgentEventEnum)) and listeners to be called when they happen.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentModelEventHandler

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentModelEventHandler()

```csharp
public AgentModelEventHandler()
```

## Fields

### listenerList

```csharp
private Dictionary<AgentEventEnum, List<AgentEventListenerDelegate>> listenerList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{AgentEventEnum,System.Collections.Generic.List{AgentEventListenerDelegate}}

## Methods

### AddEvent(AgentEventEnum, AgentEventListenerDelegate)

```csharp
public void AddEvent(AgentEventEnum e, AgentEventListenerDelegate func)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AgentEventEnum` |  |
| `func` | `Global.AgentEventListenerDelegate` |  |

### CallEvent(AgentEventEnum, params object[])

```csharp
public void CallEvent(AgentEventEnum e, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AgentEventEnum` |  |
| `param` | `System.Object[]` |  |

### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC

