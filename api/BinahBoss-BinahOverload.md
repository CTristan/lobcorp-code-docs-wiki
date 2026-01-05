# Class BinahOverload

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahOverload : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahOverload

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahOverload(BinahCoreScript, OverloadType)

```csharp
public BinahOverload(BinahCoreScript binah, OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `type` | `Global.OverloadType` |  |

## Fields

### binah

```csharp
public BinahCoreScript binah
```

#### Field Value

**Type:** Global.BinahCoreScript

### BinahAttachedEffect

```csharp
public GameObject BinahAttachedEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### FailureAction

```csharp
public BinahAction FailureAction
```

#### Field Value

**Type:** BinahBoss.BinahAction

### IsolatePercent

```csharp
public float IsolatePercent
```

#### Field Value

**Type:** System.Single

### overloadedCreatures

```csharp
public List<CreatureModel> overloadedCreatures
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### overloadType

```csharp
public OverloadType overloadType
```

#### Field Value

**Type:** Global.OverloadType

### ProbReductionValue

```csharp
public int ProbReductionValue
```

#### Field Value

**Type:** System.Int32

### SuccessAction

```csharp
public BinahAction SuccessAction
```

#### Field Value

**Type:** BinahBoss.BinahAction

### TimeLimit

```csharp
public float TimeLimit
```

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

### GetCreatureCount()

```csharp
public int GetCreatureCount()
```

#### Returns

**Type:** System.Int32

### GetOverloadTargetCount(BinahOverload)

```csharp
public static int GetOverloadTargetCount(BinahOverload overload)
```

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

### LoadBinahAttachedEffect(string)

```csharp
public virtual GameObject LoadBinahAttachedEffect(string src)
```

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

### OnExecute()

```csharp
public virtual void OnExecute()
```

### OnFail()

```csharp
public virtual void OnFail()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnParticleArrived(CreatureModel)

```csharp
public virtual void OnParticleArrived(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnReducedCreature(CreatureModel)

```csharp
public virtual void OnReducedCreature(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnSuccess()

```csharp
public virtual void OnSuccess()
```
