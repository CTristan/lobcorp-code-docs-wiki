---
uid: GeburahBoss.GreedyTelepeort
canonical_path: /api/GeburahBoss/GreedyTelepeort
---

# Class GreedyTelepeort

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GreedyTelepeort : GeburahAction
```

[The Red Mist](/api/Global/Script/GeburahCoreScript)'s action for the Gold Rush attack.
(First and third phases.)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → GreedyTelepeort

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GreedyTelepeort(GeburahCoreScript, int)

```csharp
public GreedyTelepeort(GeburahCoreScript geburah, int passageCount)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `passageCount` | `System.Int32` |  |

## Fields

### _damageSoundTimer

```csharp
private Timer _damageSoundTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _delayTimer

```csharp
private Timer _delayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### animClipTime

```csharp
private const float animClipTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### buf

```csharp
private MovementBuf buf
```
#INC


#### Field Value

**Type:** GeburahBoss.MovementBuf

### currentInfo

```csharp
private MovementInfo currentInfo
```
#INC


#### Field Value

**Type:** GeburahBoss.MovementInfo

### damaged

```csharp
private List<UnitModel> damaged
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### damageInfo

```csharp
public static DamageInfo damageInfo
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### moveCount

```csharp
private int moveCount
```
#INC


#### Field Value

**Type:** System.Int32

### moveMax

```csharp
private int moveMax
```
#INC


#### Field Value

**Type:** System.Int32

### movementInfo

```csharp
private Queue<MovementInfo> movementInfo
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{GeburahBoss.MovementInfo}

### movementInfoList

```csharp
private List<MovementInfo> movementInfoList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{GeburahBoss.MovementInfo}

### PassageCount

```csharp
private int PassageCount
```
#INC


#### Field Value

**Type:** System.Int32

### portalAnim

```csharp
private List<Animator> portalAnim
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Animator}

### speedFactor

```csharp
private float speedFactor
```
#INC


#### Field Value

**Type:** System.Single

### speedValue

```csharp
public const float speedValue = 32
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Freq

```csharp
private float Freq { get; }
```

#### Property Value

**Type:** System.Single

### isRunning

```csharp
private bool isRunning { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ExecuteNextInfo()

```csharp
private void ExecuteNextInfo()
```
#INC


### MakePortal(Vector3)

```csharp
public Animator MakePortal(Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Animator

### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnExecute()

```csharp
public override void OnExecute()
```
#INC


### OnGiveDamage()

```csharp
public void OnGiveDamage()
```
#INC


### OnReadyForRun(MovementInfo)

```csharp
private void OnReadyForRun(MovementInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `GeburahBoss.MovementInfo` |  |

### OnStart()

```csharp
public override void OnStart()
```
#INC


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

