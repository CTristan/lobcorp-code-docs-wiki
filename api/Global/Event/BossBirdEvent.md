---
uid: Global.BossBirdEvent
canonical_path: /api/Global/Event/BossBirdEvent
---

# Class BossBirdEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdEvent : EventBase
```

Event for [Apocalypse Bird](/api/Global/Misc/BossBird)'s fight. Makes gates and eggs.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EventBase](/api/Global/Event/EventBase) → BossBirdEvent

## Inherited Members
[isStarted](/api/Global/Event/EventBase#isstarted), [_type](/api/Global/Event/EventBase#type), [IsStartable()](/api/Global/Event/EventBase#isstartable), [OnGameInit()](/api/Global/Event/EventBase#ongameinit), [OnDestroy()](/api/Global/Event/EventBase#ondestroy), [OnEventStart()](/api/Global/Event/EventBase#oneventstart), [EventEnd()](/api/Global/Event/EventBase#eventend), [FixedUpdate()](/api/Global/Event/EventBase#fixedupdate), [type](/api/Global/Event/EventBase#type), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBirdEvent()

```csharp
public BossBirdEvent()
```
#INC
#code-generated


## Fields

### bigEgg

```csharp
private EventCreatureModel bigEgg
```
#INC


#### Field Value

**Type:** Global.EventCreatureModel

### bigObjectID

```csharp
private const long bigObjectID = 1000351
```
#INC


#### Field Value

**Type:** System.Int64

### gateWay

```csharp
private EventCreatureModel gateWay
```
#INC


#### Field Value

**Type:** Global.EventCreatureModel

### gateWayID

```csharp
private const long gateWayID = 1000350
```
#INC


#### Field Value

**Type:** System.Int64

### longEgg

```csharp
private EventCreatureModel longEgg
```
#INC


#### Field Value

**Type:** Global.EventCreatureModel

### longObjectID

```csharp
private const long longObjectID = 1000353
```
#INC


#### Field Value

**Type:** System.Int64

### smallEgg

```csharp
private EventCreatureModel smallEgg
```
#INC


#### Field Value

**Type:** Global.EventCreatureModel

### smallObjectID

```csharp
private const long smallObjectID = 1000352
```
#INC


#### Field Value

**Type:** System.Int64

## Methods

### MakeBigEgg(MapNode)

```csharp
public EventCreatureModel MakeBigEgg(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.EventCreatureModel

### MakeGate()

```csharp
public EventCreatureModel MakeGate()
```
#INC


#### Returns

**Type:** Global.EventCreatureModel

### MakeLongEgg(MapNode)

```csharp
public EventCreatureModel MakeLongEgg(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.EventCreatureModel

### MakeSmallEgg(MapNode)

```csharp
public EventCreatureModel MakeSmallEgg(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.EventCreatureModel
