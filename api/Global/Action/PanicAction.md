---
uid: Global.PanicAction
canonical_path: /api/Global/Action/PanicAction
---

# Class PanicAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicAction
```
Parent class for panicking [worker](/api/Global/Unit/WorkerUnit) behaviour.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PanicAction

## Derived
[PanicOfficer](/api/Global/Misc/PanicOfficer), [PanicOpenIsolate](/api/Global/Misc/PanicOpenIsolate), [PanicReady](/api/Global/Misc/PanicReady), [PanicRoaming](/api/Global/Misc/PanicRoaming), [PanicSuicideExecutor](/api/Global/Misc/PanicSuicideExecutor), [PanicViolence](/api/Global/Misc/PanicViolence)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicAction()

```csharp
public PanicAction()
```

## Methods

### Execute()

```csharp
public virtual void Execute()
```
#INC


### GetAttackSpeedMultiplier()

```csharp
public virtual float GetAttackSpeedMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### GetDefenseMultiplier()

```csharp
public virtual float GetDefenseMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### GetMovementMultiplier()

```csharp
public virtual float GetMovementMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### Init()

```csharp
public virtual void Init()
```
#INC
#code-generated


### OnDie()

```csharp
public virtual void OnDie()
```
#INC


### PanicEnd()

```csharp
public virtual void PanicEnd()
```
#INC

