---
uid: Global.EventBase
canonical_path: /api/Global/Event/EventBase
---

# Class EventBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EventBase
```
Base for events except there's only [Apocalypse Bird](/api/Global/Misc/BossBird).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EventBase

## Derived
[BossBirdEvent](/api/Global/Event/BossBirdEvent)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EventBase()

```csharp
public EventBase()
```

## Fields

### _type

```csharp
protected EventBase.EventType _type
```

#### Field Value

**Type:** Global.EventBase.EventType

### isStarted

```csharp
public bool isStarted
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### type

```csharp
public EventBase.EventType type { get; }
```

#### Property Value

**Type:** Global.EventBase.EventType

## Methods

### EventEnd()

```csharp
public virtual void EventEnd()
```
#INC


### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### IsStartable()

```csharp
public virtual bool IsStartable()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnEventStart()

```csharp
public virtual void OnEventStart()
```
#INC


### OnGameInit()

```csharp
public virtual void OnGameInit()
```
#INC

