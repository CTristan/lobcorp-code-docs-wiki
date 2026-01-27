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
Stores an time and event type for an event in the work day.

These events can be:
- Worker panic
- Worker death
- Abnormality escape
- Ordeal start
- Trumpet start

See also [GlobalHistory](/api/Global/IOBserver/GlobalHistory).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → History

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### History(string, params object[])

```csharp
public History(string notice, params object[] param)
```
#INC
#code-generated


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
#INC


#### Field Value

**Type:** System.Single

### _targetCreature

```csharp
private CreatureModel _targetCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### _targetEvent

```csharp
private RandomEventBase _targetEvent
```
#INC


#### Field Value

**Type:** Global.RandomEventBase

### _targetLevel

```csharp
private EmergencyLevel _targetLevel
```
#INC


#### Field Value

**Type:** Global.EmergencyLevel

### _targetWorker

```csharp
private AgentModel _targetWorker
```
#INC


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
#INC


#### Field Value

**Type:** System.Boolean

### suppressedTime

```csharp
public float suppressedTime
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### GetCreature()

```csharp
public CreatureModel GetCreature()
```
#INC


#### Returns

**Type:** Global.CreatureModel

### GetEmergency()

```csharp
public EmergencyLevel GetEmergency()
```
#INC


#### Returns

**Type:** Global.EmergencyLevel

### GetEvent()

```csharp
public RandomEventBase GetEvent()
```
#INC


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
#INC


#### Returns

**Type:** System.Single

### GetWorker()

```csharp
public AgentModel GetWorker()
```
#INC


#### Returns

**Type:** Global.AgentModel
