---
uid: GeburahBoss.GeburahIdle
canonical_path: /api/GeburahBoss/GeburahIdle
---

# Class GeburahIdle

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahIdle : GeburahAction
```

Action for [The Red Mist](/api/Global/Script/GeburahCoreScript) doing nothing (or being stunned).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → GeburahIdle

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [OnStart()](/api/GeburahBoss/GeburahAction#onstart), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahIdle(GeburahCoreScript, bool, float)

```csharp
public GeburahIdle(GeburahCoreScript geburah, bool nearClose, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `nearClose` | `System.Boolean` |  |
| `time` | `System.Single` |  |

### GeburahIdle(GeburahCoreScript, float, bool)

```csharp
public GeburahIdle(GeburahCoreScript geburah, float time, bool isGroggy = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `time` | `System.Single` |  |
| `isGroggy` | `System.Boolean` |  |

## Fields

### _isGroggy

```csharp
private bool _isGroggy
```
#INC


#### Field Value

**Type:** System.Boolean

### _nearClose

```csharp
private bool _nearClose
```
#INC


#### Field Value

**Type:** System.Boolean

### time

```csharp
private float time
```
#INC


#### Field Value

**Type:** System.Single

### timer

```csharp
private Timer timer
```
#INC


#### Field Value

**Type:** Global.Timer

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


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

