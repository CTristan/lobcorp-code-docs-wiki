---
uid: Global.Uncontrollable_ViscusSnake
canonical_path: /api/Global/UncontrollableAction/UncontrollableViscusSnake
---

# Class Uncontrollable_ViscusSnake

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_ViscusSnake : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_ViscusSnake

## Inherited Members
[OnDestroy()](/api/Global/Action/UncontrollableAction#ondestroy), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_ViscusSnake(WorkerModel, ViscusSnake, GameObject)

```csharp
public Uncontrollable_ViscusSnake(WorkerModel model, ViscusSnake snake, GameObject faceEffect)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `snake` | `Global.ViscusSnake` |  |
| `faceEffect` | `UnityEngine.GameObject` |  |

## Fields

### _armEffect

```csharp
private const string _armEffect = "Effect/Creature/ViscusSnake/ViscusAppear_Arm"
```

#### Field Value

**Type:** System.String

### _attackDist

```csharp
private const float _attackDist = 3
```

#### Field Value

**Type:** System.Single

### _currentDestMovable

```csharp
private MovableObjectNode _currentDestMovable
```

#### Field Value

**Type:** Global.MovableObjectNode

### _currentDestNode

```csharp
private MapNode _currentDestNode
```

#### Field Value

**Type:** Global.MapNode

### _headEffect

```csharp
private const string _headEffect = "Effect/Creature/ViscusSnake/ViscusAppear_Head"
```

#### Field Value

**Type:** System.String

### _init

```csharp
private bool _init
```

#### Field Value

**Type:** System.Boolean

### _isAttacking

```csharp
private bool _isAttacking
```

#### Field Value

**Type:** System.Boolean

### _recognizeDist

```csharp
private const float _recognizeDist = 5
```

#### Field Value

**Type:** System.Single

### animator

```csharp
private Animator animator
```

#### Field Value

**Type:** UnityEngine.Animator

### currentTarget

```csharp
private UnitModel currentTarget
```

#### Field Value

**Type:** Global.UnitModel

### damageInfo

```csharp
private static DamageInfo damageInfo
```

#### Field Value

**Type:** Global.DamageInfo

### faceEffect

```csharp
private GameObject faceEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### gasEffect

```csharp
private ParticleSystem gasEffect
```

#### Field Value

**Type:** UnityEngine.ParticleSystem

### model

```csharp
private WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### snake

```csharp
private ViscusSnake snake
```

#### Field Value

**Type:** Global.ViscusSnake

## Properties

### AttackDist

```csharp
private float AttackDist { get; }
```

#### Property Value

**Type:** System.Single

### CurrentScale

```csharp
private float CurrentScale { get; }
```

#### Property Value

**Type:** System.Single

### Movable

```csharp
private MovableObjectNode Movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

### RecognizeDist

```csharp
private float RecognizeDist { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### CheckCurrentTarget()

```csharp
private bool CheckCurrentTarget()
```

#### Returns

**Type:** System.Boolean

### CheckMovingState()

```csharp
private void CheckMovingState()
```

### Execute()

```csharp
public override void Execute()
```

### GetNearTarget(PassageObjectModel, out UnitModel)

```csharp
private bool GetNearTarget(PassageObjectModel passage, out UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public override void Init()
```

### IsIdleAnimation()

```csharp
private bool IsIdleAnimation()
```

#### Returns

**Type:** System.Boolean

### IsInitEnded()

```csharp
private bool IsInitEnded()
```

#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float, out UnitDirection)

```csharp
private bool IsInRange(UnitModel unit, float distValue, out UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |
| `distValue` | `System.Single` |  |
| `dir` | `Global.UnitDirection` |  |

#### Returns

**Type:** System.Boolean

### LoseTarget()

```csharp
private void LoseTarget()
```

### MakeChaseMovement(MovableObjectNode)

```csharp
private void MakeChaseMovement(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

### MakeRandomMovement()

```csharp
private void MakeRandomMovement()
```

### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnClick()

```csharp
public override void OnClick()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnEndInititalAnim()

```csharp
public void OnEndInititalAnim()
```

### OnGiveDamage()

```csharp
public void OnGiveDamage()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### SetParticle(ParticleSystem)

```csharp
public void SetParticle(ParticleSystem ps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ps` | `UnityEngine.ParticleSystem` |  |

### StartAttack()

```csharp
private void StartAttack()
```

### StopMoving(bool)

```csharp
private void StopMoving(bool nodeClear = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeClear` | `System.Boolean` |  |
