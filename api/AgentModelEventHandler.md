# Class AgentModelEventHandler

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentModelEventHandler
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentModelEventHandler

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentModelEventHandler()

```csharp
public AgentModelEventHandler()
```

## Methods

### AddEvent(AgentEventEnum, AgentEventListenerDelegate)

```csharp
public void AddEvent(AgentEventEnum e, AgentEventListenerDelegate func)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AgentEventEnum` |  |
| `func` | `Global.AgentEventListenerDelegate` |  |

### CallEvent(AgentEventEnum, params object[])

```csharp
public void CallEvent(AgentEventEnum e, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AgentEventEnum` |  |
| `param` | `System.Object[]` |  |

### OnStageRelease()

```csharp
public void OnStageRelease()
```
