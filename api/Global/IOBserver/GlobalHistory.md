---
uid: Global.GlobalHistory
canonical_path: /api/Global/IOBserver/GlobalHistory
---

# Class GlobalHistory

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalHistory : IObserver
```

Keeps track of events during the day:
- Worker panic
- Worker death
- Abnormality escape
- Ordeal start
- Trumpets
- Time elapsed

For the [results screen](/api/Global/IANimatorEventCalled/ResultScreen) and some missions.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalHistory

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GlobalHistory()

```csharp
public GlobalHistory()
```
#INC
#code-generated


## Fields

### _deadAgents

```csharp
private List<AgentModel> _deadAgents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### _endTime

```csharp
private float _endTime
```
#INC


#### Field Value

**Type:** System.Single

### _firstQuarter

```csharp
private float _firstQuarter
```
#INC


#### Field Value

**Type:** System.Single

### _histories

```csharp
private List<History> _histories
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{History}

### _instance

```csharp
private static GlobalHistory _instance
```
#INC


#### Field Value

**Type:** Global.GlobalHistory

### _ordsAndEmers

```csharp
private List<History> _ordsAndEmers
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{History}

### _secondQuarter

```csharp
private float _secondQuarter
```
#INC


#### Field Value

**Type:** System.Single

### _startTime

```csharp
private float _startTime
```
#INC


#### Field Value

**Type:** System.Single

### _thirdQuarter

```csharp
private float _thirdQuarter
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### instance

```csharp
public static GlobalHistory instance { get; }
```

#### Property Value

**Type:** Global.GlobalHistory

## Methods

### AddOrdsAndEmers(History)

```csharp
public void AddOrdsAndEmers(History history)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `history` | `Global.History` |  |

### GetCurrentTime()

```csharp
public float GetCurrentTime()
```
#INC


#### Returns

**Type:** System.Single

### GetHistory()

```csharp
public List<History> GetHistory()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{History}

### GetOrdsAndEmers()

```csharp
public List<History> GetOrdsAndEmers()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{History}

### GetResults()

```csharp
public List<Result> GetResults()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{Result}

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC

