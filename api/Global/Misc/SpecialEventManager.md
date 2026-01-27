---
uid: Global.SpecialEventManager
canonical_path: /api/Global/Misc/SpecialEventManager
---

# Class SpecialEventManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpecialEventManager
```
Manages the activation of special events and creating [event creatures](/api/Global/Creature/EventCreatureModel) during them. The only special event is [Apocalypse Bird's event](/api/Global/Event/BossBirdEvent).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpecialEventManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpecialEventManager()

```csharp
public SpecialEventManager()
```

## Fields

### _instance

```csharp
private static SpecialEventManager _instance
```
#INC


#### Field Value

**Type:** Global.SpecialEventManager

### activatedEvents

```csharp
private List<EventBase> activatedEvents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EventBase}

### eventCreatureList

```csharp
private List<EventCreatureModel> eventCreatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EventCreatureModel}

### eventlist

```csharp
private List<EventBase> eventlist
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EventBase}

### nextInstId

```csharp
private int nextInstId
```
#INC


#### Field Value

**Type:** System.Int32

### removedEvents

```csharp
private List<EventBase> removedEvents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EventBase}

## Properties

### instance

```csharp
public static SpecialEventManager instance { get; }
```

#### Property Value

**Type:** Global.SpecialEventManager

## Methods

### ActivateEvent(EventBase)

```csharp
public bool ActivateEvent(EventBase _event)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_event` | `Global.EventBase` |  |

#### Returns

**Type:** System.Boolean

### AddCreature(long, MapNode, EventBase)

```csharp
public EventCreatureModel AddCreature(long metadataId, MapNode pos, EventBase eventBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `pos` | `Global.MapNode` |  |
| `eventBase` | `Global.EventBase` |  |

#### Returns

**Type:** Global.EventCreatureModel

### BuildCreature(EventCreatureModel, long)

```csharp
private void BuildCreature(EventCreatureModel model, long metadataId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EventCreatureModel` |  |
| `metadataId` | `System.Int64` |  |

### CheckEventContains(EventType, out EventBase)

```csharp
public bool CheckEventContains(EventBase.EventType type, out EventBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.EventBase.EventType` |  |
| `script` | `Global.EventBase` |  |

#### Returns

**Type:** System.Boolean

### ClearCreatures()

```csharp
public void ClearCreatures()
```
#INC


### GetEventCreatureList()

```csharp
public EventCreatureModel[] GetEventCreatureList()
```
#INC


#### Returns

**Type:** Global.EventCreatureModel[]

### OnEventEnd(EventBase)

```csharp
public void OnEventEnd(EventBase _event)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_event` | `Global.EventBase` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGameInit()

```csharp
public void OnGameInit()
```
#INC
#code-generated


### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC

