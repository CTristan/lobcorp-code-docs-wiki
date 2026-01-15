---
uid: Global.History
canonical_path: /api/Global/Misc/History
---

# Class History

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class History
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → History

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### History(string, params object[])

```csharp
public History(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

## Fields

### _inputTime

```csharp
private float _inputTime
```

#### Field Value

**Type:** System.Single

### _targetCreature

```csharp
private CreatureModel _targetCreature
```

#### Field Value

**Type:** Global.CreatureModel

### _targetEvent

```csharp
private RandomEventBase _targetEvent
```

#### Field Value

**Type:** Global.RandomEventBase

### _targetLevel

```csharp
private EmergencyLevel _targetLevel
```

#### Field Value

**Type:** Global.EmergencyLevel

### _targetWorker

```csharp
private AgentModel _targetWorker
```

#### Field Value

**Type:** Global.AgentModel

### _type

```csharp
private History.HistoryType _type
```

#### Field Value

**Type:** Global.History.HistoryType

### isSuppressed

```csharp
public bool isSuppressed
```

#### Field Value

**Type:** System.Boolean

### suppressedTime

```csharp
public float suppressedTime
```

#### Field Value

**Type:** System.Single

## Methods

### GetCreature()

```csharp
public CreatureModel GetCreature()
```

#### Returns

**Type:** Global.CreatureModel

### GetEmergency()

```csharp
public EmergencyLevel GetEmergency()
```

#### Returns

**Type:** Global.EmergencyLevel

### GetEvent()

```csharp
public RandomEventBase GetEvent()
```

#### Returns

**Type:** Global.RandomEventBase

### GetHistoryType()

```csharp
public History.HistoryType GetHistoryType()
```

#### Returns

**Type:** Global.History.HistoryType

### GetTime()

```csharp
public float GetTime()
```

#### Returns

**Type:** System.Single

### GetWorker()

```csharp
public AgentModel GetWorker()
```

#### Returns

**Type:** Global.AgentModel
