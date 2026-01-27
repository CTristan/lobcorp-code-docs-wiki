---
uid: GeburahBoss.MoveNodeAction
canonical_path: /api/GeburahBoss/MoveNodeAction
---

# Class MoveNodeAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveNodeAction : GeburahAction
```
Action where [The Red Mist](/api/Global/Script/GeburahCoreScript) moves.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → MoveNodeAction

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [ParamInit()](/api/GeburahBoss/GeburahAction#paraminit), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoveNodeAction(GeburahCoreScript, MapNode)

```csharp
public MoveNodeAction(GeburahCoreScript geburah, MapNode destNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `destNode` | `Global.MapNode` |  |

## Fields

### _isSamePassage

```csharp
private bool _isSamePassage
```
#INC


#### Field Value

**Type:** System.Boolean

### _nearTargetDetected

```csharp
private GeburahAction _nearTargetDetected
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahAction

### destNode

```csharp
private MapNode destNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### ignoreNearTargets

```csharp
private bool ignoreNearTargets
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnExecute()

```csharp
public override void OnExecute()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated


### SetNearTargetDetected(GeburahAction)

```csharp
public void SetNearTargetDetected(GeburahAction action)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GeburahBoss.GeburahAction` |  |
