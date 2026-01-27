---
uid: BinahBoss.BinahPhaseExecution
canonical_path: /api/BinahBoss/BinahPhaseExecution
---

# Class BinahPhaseExecution

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class BinahPhaseExecution
```
Parent class for [An Arbiter](/api/Global/Script/BinahCoreScript)'s phases during [Binah's core suppression](/api/Global/Misc/BinahBossBase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahPhaseExecution

## Derived
[FirstPhase](/api/BinahBoss/FirstPhase), [SecondPhase](/api/BinahBoss/SecondPhase), [ThirdPhase](/api/BinahBoss/ThirdPhase)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahPhaseExecution(BinahCoreScript)

```csharp
public BinahPhaseExecution(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### binah

```csharp
public BinahCoreScript binah
```
#INC


#### Field Value

**Type:** Global.BinahCoreScript

### overloadActivated

```csharp
public bool overloadActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### overloadTimer

```csharp
public Timer overloadTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### overloadTypeList

```csharp
public List<OverloadType> overloadTypeList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OverloadType}

## Properties

### BinahHasOverload

```csharp
public bool BinahHasOverload { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### FixedUpdate()

```csharp
public abstract void FixedUpdate()
```
#INC


### GetNextAction(List<UnitModel>)

```csharp
public abstract BinahAction GetNextAction(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** BinahBoss.BinahAction

### GetOverloadType()

```csharp
public virtual OverloadType GetOverloadType()
```
#INC


#### Returns

**Type:** Global.OverloadType

### HaltOverload()

```csharp
public virtual void HaltOverload()
```
#INC


### OnOverloadEnd()

```csharp
public virtual void OnOverloadEnd()
```
#INC


### OnPrevSuppressed()

```csharp
public abstract void OnPrevSuppressed()
```
#INC


### StartTimer(float)

```csharp
public virtual void StartTimer(float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### ToString()

```csharp
public override string ToString()
```
#INC
#code-generated


#### Returns

**Type:** System.String

### Update()

```csharp
public abstract void Update()
```
#INC

