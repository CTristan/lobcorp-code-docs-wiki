---
uid: Global.PanicOpenIsolate
canonical_path: /api/Global/Misc/PanicOpenIsolate
---

# Class PanicOpenIsolate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicOpenIsolate : PanicAction
```

Panic behaviour for [agents](/api/Global/Worker/AgentModel) which causes them to try to release abnormalities.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicOpenIsolate

## Inherited Members
[GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicOpenIsolate(AgentModel)

```csharp
public PanicOpenIsolate(AgentModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

## Fields

### _currentOpenTargetCreature

```csharp
private CreatureModel _currentOpenTargetCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### _currentTargetPassage

```csharp
private PassageObjectModel _currentTargetPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### _openActionCooltime

```csharp
private const float _openActionCooltime = 5
```
#INC


#### Field Value

**Type:** System.Single

### _openActionTimer

```csharp
private Timer _openActionTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _openTryCount

```csharp
private int _openTryCount
```
#INC


#### Field Value

**Type:** System.Int32

### _openTryMax

```csharp
private const int _openTryMax = 5
```
#INC


#### Field Value

**Type:** System.Int32

### actor

```csharp
private AgentModel actor
```
#INC


#### Field Value

**Type:** Global.AgentModel

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### GetDefenseMultiplier()

```csharp
public override float GetDefenseMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### GetMovementMultiplier()

```csharp
public override float GetMovementMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### GetTarget()

```csharp
public CreatureModel GetTarget()
```
#INC


#### Returns

**Type:** Global.CreatureModel

### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### OnAgentAnimEvent(int)

```csharp
public void OnAgentAnimEvent(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDie()

```csharp
public override void OnDie()
```
#INC


### PanicEnd()

```csharp
public override void PanicEnd()
```
#INC


### TryOpen()

```csharp
private void TryOpen()
```
#INC


### UpdateNextTarget()

```csharp
private void UpdateNextTarget()
```
#INC

