---
uid: BinahBoss.BinahOverload
canonical_path: /api/BinahBoss/BinahOverload
---

# Class BinahOverload

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahOverload : IObserver
```
Parent class for [Binah](/api/Global/Misc/BinahBossBase)'s special meltdowns


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahOverload

## Derived
[BlackFogOverload](/api/BinahBoss/BlackFogOverload), [ColumnOverload](/api/BinahBoss/ColumnOverload), [GoldenOverload](/api/BinahBoss/GoldenOverload), [WaveOverload](/api/BinahBoss/WaveOverload)

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahOverload(BinahCoreScript, OverloadType)

```csharp
public BinahOverload(BinahCoreScript binah, OverloadType type)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `type` | `Global.OverloadType` |  |

## Fields

### _defenseInfo

```csharp
private DefenseInfo _defenseInfo
```
#INC


#### Field Value

**Type:** Global.DefenseInfo

### binah

```csharp
public BinahCoreScript binah
```
#INC


#### Field Value

**Type:** Global.BinahCoreScript

### BinahAttachedEffect

```csharp
public GameObject BinahAttachedEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### FailureAction

```csharp
public BinahAction FailureAction
```
#INC


#### Field Value

**Type:** BinahBoss.BinahAction

### IsolatePercent

```csharp
public float IsolatePercent
```
#INC


#### Field Value

**Type:** System.Single

### overloadedCreatures

```csharp
public List<CreatureModel> overloadedCreatures
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### overloadType

```csharp
public OverloadType overloadType
```
#INC


#### Field Value

**Type:** Global.OverloadType

### ProbReductionValue

```csharp
public int ProbReductionValue
```
#INC


#### Field Value

**Type:** System.Int32

### SuccessAction

```csharp
public BinahAction SuccessAction
```
#INC


#### Field Value

**Type:** BinahBoss.BinahAction

### TimeLimit

```csharp
public float TimeLimit
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Animator

```csharp
public Animator Animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### AnimScript

```csharp
public BinahCoreAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.BinahCoreAnim

### DefenseInfo

```csharp
public DefenseInfo DefenseInfo { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

### Model

```csharp
public CreatureModel Model { get; }
```

#### Property Value

**Type:** Global.CreatureModel

### Movable

```csharp
public MovableObjectNode Movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

## Methods

### CastOverload()

```csharp
public virtual void CastOverload()
```
#INC


### GetCreatureCount()

```csharp
public int GetCreatureCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetOverloadTargetCount(BinahOverload)

```csharp
public static int GetOverloadTargetCount(BinahOverload overload)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overload` | `BinahBoss.BinahOverload` |  |

#### Returns

**Type:** System.Int32

### Interrupt()

```csharp
public virtual void Interrupt()
```
#INC


### LoadBinahAttachedEffect(string)

```csharp
public virtual GameObject LoadBinahAttachedEffect(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnExecute()

```csharp
public virtual void OnExecute()
```
#INC


### OnFail()

```csharp
public virtual void OnFail()
```
#INC


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

### OnParticleArrived(CreatureModel)

```csharp
public virtual void OnParticleArrived(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnReducedCreature(CreatureModel)

```csharp
public virtual void OnReducedCreature(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnSuccess()

```csharp
public virtual void OnSuccess()
```
#INC

