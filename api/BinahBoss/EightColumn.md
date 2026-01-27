---
uid: BinahBoss.EightColumn
canonical_path: /api/BinahBoss/EightColumn
---

# Class EightColumn

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EightColumn : BinahAction
```
[An Arbiter](/api/Global/Script/BinahCoreScript)'s 8 column attack (scary!).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss/BinahAction) → EightColumn

## Inherited Members
[binah](/api/BinahBoss/BinahAction#binah), [actionState](/api/BinahBoss/BinahAction#actionstate), [_interrupt](/api/BinahBoss/BinahAction#interrupt), [SetInterruptAction(BinahAction)](/api/BinahBoss/BinahAction#setinterruptaction-binahaction), [OnInterrupt()](/api/BinahBoss/BinahAction#oninterrupt), [EndAction()](/api/BinahBoss/BinahAction#endaction), [Interrupt()](/api/BinahBoss/BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss/BinahAction#cantakedamage), [Movable](/api/BinahBoss/BinahAction#movable), [Model](/api/BinahBoss/BinahAction#model), [AnimScript](/api/BinahBoss/BinahAction#animscript), [Animator](/api/BinahBoss/BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EightColumn(BinahCoreScript)

```csharp
public EightColumn(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### _timeLimit

```csharp
private const float _timeLimit = 60
```
#INC


#### Field Value

**Type:** System.Single

### columnOverload

```csharp
private ColumnOverload columnOverload
```
#INC


#### Field Value

**Type:** BinahBoss.ColumnOverload

### columns

```csharp
private Dictionary<BinahProjectile, Vector3> columns
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{BinahBoss.BinahProjectile,UnityEngine.Vector3}

### genCount

```csharp
private int genCount
```
#INC


#### Field Value

**Type:** System.Int32

### generationTimer

```csharp
private Timer generationTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### genFreq

```csharp
private float genFreq
```
#INC


#### Field Value

**Type:** System.Single

### Loop

```csharp
private SoundEffectPlayer Loop
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### Pivots

```csharp
private Transform[] Pivots
```
#INC


#### Field Value

**Type:** UnityEngine.Transform[]

### timeLimitTimer

```csharp
private Timer timeLimitTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### GenProjectile(Transform, out Vector3)

```csharp
private BinahProjectile GenProjectile(Transform startPos, out Vector3 velocity)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startPos` | `UnityEngine.Transform` |  |
| `velocity` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** BinahBoss.BinahProjectile

### OnAnimEventCalled(int)

```csharp
public override void OnAnimEventCalled(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public override void OnAttackEnd()
```
#INC


### OnCancel()

```csharp
public void OnCancel()
```
#INC


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


### OnGiveDamage()

```csharp
public override void OnGiveDamage()
```
#INC


### OnShoot()

```csharp
public void OnShoot()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated


### ParamInit()

```csharp
public override void ParamInit()
```
#INC

