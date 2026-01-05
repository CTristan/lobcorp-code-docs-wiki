# Class EventBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EventBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```

### IsStartable()

```csharp
public virtual bool IsStartable()
```

#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnEventStart()

```csharp
public virtual void OnEventStart()
```

### OnGameInit()

```csharp
public virtual void OnGameInit()
```
