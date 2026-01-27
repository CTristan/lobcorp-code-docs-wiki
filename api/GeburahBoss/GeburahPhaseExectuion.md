---
uid: GeburahBoss.GeburahPhaseExectuion
canonical_path: /api/GeburahBoss/GeburahPhaseExectuion
---

# Class GeburahPhaseExectuion

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class GeburahPhaseExectuion
```
Parent class for [The Red Mist](/api/Global/Script/GeburahCoreScript)'s phases.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GeburahPhaseExectuion

## Derived
[FirstPhase](/api/GeburahBoss/FirstPhase), [FourthPhase](/api/GeburahBoss/FourthPhase), [SecondPhase](/api/GeburahBoss/SecondPhase), [ThirdPhase](/api/GeburahBoss/ThirdPhase)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahPhaseExectuion(GeburahCoreScript)

```csharp
public GeburahPhaseExectuion(GeburahCoreScript geburah)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### geburah

```csharp
public GeburahCoreScript geburah
```
#INC


#### Field Value

**Type:** Global.GeburahCoreScript

### isPrevAttack

```csharp
public bool isPrevAttack
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### FixedUpdate()

```csharp
public abstract void FixedUpdate()
```
#INC


### GetNextAction(List<UnitModel>)

```csharp
public abstract GeburahAction GetNextAction(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** GeburahBoss.GeburahAction

### GetRandomMoveNode()

```csharp
public virtual MapNode GetRandomMoveNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetRandomNode()

```csharp
public virtual MapNode GetRandomNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### OnPrevSuppressed()

```csharp
public virtual void OnPrevSuppressed()
```
#INC


### Update()

```csharp
public abstract void Update()
```
#INC

