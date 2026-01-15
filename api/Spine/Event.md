---
uid: Spine.Event
canonical_path: /api/Spine/Event
---

# Class Event

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Event
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Event

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Event(float, EventData)

```csharp
public Event(float time, EventData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `data` | `Spine.EventData` |  |

## Fields

### data

```csharp
internal readonly EventData data
```

#### Field Value

**Type:** Spine.EventData

### floatValue

```csharp
internal float floatValue
```

#### Field Value

**Type:** System.Single

### intValue

```csharp
internal int intValue
```

#### Field Value

**Type:** System.Int32

### stringValue

```csharp
internal string stringValue
```

#### Field Value

**Type:** System.String

### time

```csharp
internal readonly float time
```

#### Field Value

**Type:** System.Single

## Properties

### Data

```csharp
public EventData Data { get; }
```

#### Property Value

**Type:** Spine.EventData

### Float

```csharp
public float Float { get; set; }
```

#### Property Value

**Type:** System.Single

### Int

```csharp
public int Int { get; set; }
```

#### Property Value

**Type:** System.Int32

### String

```csharp
public string String { get; set; }
```

#### Property Value

**Type:** System.String

### Time

```csharp
public float Time { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
