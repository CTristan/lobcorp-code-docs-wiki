---
uid: GeburahBoss.MovementInfo
canonical_path: /api/GeburahBoss/MovementInfo
---

# Class MovementInfo

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MovementInfo
```
Info for a leg of [The Red Mist](/api/Global/Misc/GeburahBossBase)'s [Gold Rush](/api/GeburahBoss/GreedyTelepeort) and [Phase 4 Gold Rush](/api/GeburahBoss/GreedyThrow) attacks.

Contains start and end locations, the current passage #inc, animators for starting and ending, and whether this is the first or last leg #inc.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MovementInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MovementInfo(PassageObjectModel)

```csharp
public MovementInfo(PassageObjectModel passage)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

## Fields

### _endAnimator

```csharp
public Animator _endAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### _isInitial

```csharp
public bool _isInitial
```
#INC


#### Field Value

**Type:** System.Boolean

### _isLast

```csharp
public bool _isLast
```
#INC


#### Field Value

**Type:** System.Boolean

### _startAnimator

```csharp
public Animator _startAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### direction

```csharp
public UnitDirection direction
```
#INC


#### Field Value

**Type:** Global.UnitDirection

### end

```csharp
public MapNode end
```
#INC


#### Field Value

**Type:** Global.MapNode

### passage

```csharp
public PassageObjectModel passage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### start

```csharp
public MapNode start
```
#INC


#### Field Value

**Type:** Global.MapNode
