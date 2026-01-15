---
uid: Global.BossBirdAnim.RangeAttackController
canonical_path: /api/Global/Misc/BossBirdAnimRangeAttackController
---

# Class BossBirdAnim.RangeAttackController

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdAnim.RangeAttackController
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BossBirdAnim.RangeAttackController

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RangeAttackController()

```csharp
public RangeAttackController()
```

## Fields

### currentLifeTime

```csharp
private float currentLifeTime
```

#### Field Value

**Type:** System.Single

### currentTargetPos

```csharp
private Vector2 currentTargetPos
```

#### Field Value

**Type:** UnityEngine.Vector2

### data

```csharp
private List<BossBird.LaserAttackTargetData> data
```

#### Field Value

**Type:** System.Collections.Generic.List{BossBird.LaserAttackTargetData}

### enableEvent

```csharp
private BossBirdAnim.RangeAttackController.OnAllEnabled enableEvent
```

#### Field Value

**Type:** Global.BossBirdAnim.RangeAttackController.OnAllEnabled

### enableTimer

```csharp
private Timer enableTimer
```

#### Field Value

**Type:** Global.Timer

### enableTimeRandRange

```csharp
public Vector2 enableTimeRandRange
```

#### Field Value

**Type:** UnityEngine.Vector2

### index

```csharp
private int index
```

#### Field Value

**Type:** System.Int32

### laserCurve

```csharp
public List<AnimationCurve> laserCurve
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.AnimationCurve}

### mode

```csharp
public BossBird.LaserMode mode
```

#### Field Value

**Type:** Global.BossBird.LaserMode

### particles

```csharp
public List<LaserParticleEffect> particles
```

#### Field Value

**Type:** System.Collections.Generic.List{LaserParticleEffect}

### rootGameObject

```csharp
public GameObject rootGameObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### script

```csharp
private BossBird script
```

#### Field Value

**Type:** Global.BossBird

## Methods

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### Init()

```csharp
public void Init()
```

### Reset()

```csharp
public void Reset()
```

### SetAllEnable(OnAllEnabled)

```csharp
public void SetAllEnable(BossBirdAnim.RangeAttackController.OnAllEnabled e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.BossBirdAnim.RangeAttackController.OnAllEnabled` |  |

### SetScript(BossBird)

```csharp
public void SetScript(BossBird script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossBird` |  |

### Shoot(float, List<LaserAttackTargetData>)

```csharp
public void Shoot(float time, List<BossBird.LaserAttackTargetData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `data` | `System.Collections.Generic.List{BossBird.LaserAttackTargetData}` |  |

### Shoot(float, Vector2)

```csharp
public void Shoot(float time, Vector2 currentTargetPos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `currentTargetPos` | `UnityEngine.Vector2` |  |

### StartRandEnable()

```csharp
private void StartRandEnable()
```

### StartShooting()

```csharp
private void StartShooting()
```
