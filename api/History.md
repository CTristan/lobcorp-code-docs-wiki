# Class History

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class History
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → History

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
