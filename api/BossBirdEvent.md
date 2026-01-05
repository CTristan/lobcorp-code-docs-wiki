# Class BossBirdEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdEvent : EventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EventBase](/api/EventBase) → BossBirdEvent

## Inherited Members
[isStarted](/api/EventBase#isstarted), [_type](/api/EventBase#type), [IsStartable()](/api/EventBase#isstartable), [OnGameInit()](/api/EventBase#ongameinit), [OnDestroy()](/api/EventBase#ondestroy), [OnEventStart()](/api/EventBase#oneventstart), [EventEnd()](/api/EventBase#eventend), [FixedUpdate()](/api/EventBase#fixedupdate), [type](/api/EventBase#type), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BossBirdEvent()

```csharp
public BossBirdEvent()
```

## Methods

### MakeBigEgg(MapNode)

```csharp
public EventCreatureModel MakeBigEgg(MapNode node)
```

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

#### Returns

**Type:** Global.EventCreatureModel

### MakeLongEgg(MapNode)

```csharp
public EventCreatureModel MakeLongEgg(MapNode node)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.EventCreatureModel
