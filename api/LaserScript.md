# Class LaserScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(SpriteRenderer), typeof(LineRenderer))]
public class LaserScript : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → LaserScript

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### LaserScript()

```csharp
public LaserScript()
```

## Fields

### animChanged

```csharp
protected bool animChanged
```

#### Field Value

**Type:** System.Boolean

### animDelay

```csharp
public float animDelay
```

#### Field Value

**Type:** System.Single

### attackEndItemSpacing

```csharp
public Vector2 attackEndItemSpacing
```

#### Field Value

**Type:** UnityEngine.Vector2

### casterModel

```csharp
protected UnitModel casterModel
```

#### Field Value

**Type:** Global.UnitModel

### currentAttackMainTarget

```csharp
protected UnitModel currentAttackMainTarget
```

#### Field Value

**Type:** Global.UnitModel

### currentDirection

```csharp
protected UnitDirection currentDirection
```

#### Field Value

**Type:** Global.UnitDirection

### delayAttack

```csharp
public float delayAttack
```

#### Field Value

**Type:** System.Single

### elap

```csharp
protected float elap
```

#### Field Value

**Type:** System.Single

### endCall

```csharp
public LaserScript.EndCall endCall
```

#### Field Value

**Type:** Global.LaserScript.EndCall

### endNode

```csharp
protected MapNode endNode
```

#### Field Value

**Type:** Global.MapNode

### endNodeAttacked

```csharp
protected bool endNodeAttacked
```

#### Field Value

**Type:** System.Boolean

### endSpriteRenderer

```csharp
public SpriteRenderer endSpriteRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### fps

```csharp
[Range(1, 30)]
public int fps
```

#### Field Value

**Type:** System.Int32

### isAttackSuccessed

```csharp
protected bool isAttackSuccessed
```

#### Field Value

**Type:** System.Boolean

### laserDisplay

```csharp
public float laserDisplay
```

#### Field Value

**Type:** System.Single

### laserSprites

```csharp
public LaserScript.LaserSprite laserSprites
```

#### Field Value

**Type:** Global.LaserScript.LaserSprite

### line

```csharp
[SerializeField]
protected LineRenderer line
```

#### Field Value

**Type:** UnityEngine.LineRenderer

### prewarmElap

```csharp
protected float prewarmElap
```

#### Field Value

**Type:** System.Single

### prewarmEnded

```csharp
protected bool prewarmEnded
```

#### Field Value

**Type:** System.Boolean

### prewarmTime

```csharp
public float prewarmTime
```

#### Field Value

**Type:** System.Single

### rangedTargetList

```csharp
protected List<UnitModel> rangedTargetList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### referenceSpriteRenderer

```csharp
protected SpriteRenderer referenceSpriteRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### sameTargetElap

```csharp
protected float sameTargetElap
```

#### Field Value

**Type:** System.Single

### sameTargetTimer

```csharp
public float sameTargetTimer
```

#### Field Value

**Type:** System.Single

### spriteElap

```csharp
protected float spriteElap
```

#### Field Value

**Type:** System.Single

### spriteIndex

```csharp
protected int spriteIndex
```

#### Field Value

**Type:** System.Int32

### startEffect

```csharp
public GameObject startEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### startSpriteRenderer

```csharp
public SpriteRenderer startSpriteRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### targetCollapsed

```csharp
public LaserScript.TargetCollapsed targetCollapsed
```

#### Field Value

**Type:** Global.LaserScript.TargetCollapsed

## Properties

### _isEnabled

```csharp
protected bool _isEnabled { get; set; }
```

#### Property Value

**Type:** System.Boolean

### currentPassage

```csharp
protected PassageObjectModel currentPassage { get; }
```

#### Property Value

**Type:** Global.PassageObjectModel

### endPos

```csharp
protected Transform endPos { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

### isEnabled

```csharp
public bool isEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

### movable

```csharp
protected MovableObjectNode movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

### startPos

```csharp
protected Transform startPos { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### Awake()

```csharp
public virtual void Awake()
```

### CheckRange(MovableObjectNode, float, UnitDirection, ref List<UnitModel>, out bool)

```csharp
public virtual bool CheckRange(MovableObjectNode movable, float hitStd, UnitDirection dir, ref List<UnitModel> targetSaved, out bool innerBlock)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |
| `hitStd` | `System.Single` |  |
| `dir` | `Global.UnitDirection` |  |
| `targetSaved` | `System.Collections.Generic.List{UnitModel}` |  |
| `innerBlock` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### DelegateInit(EndCall, TargetCollapsed)

```csharp
public virtual void DelegateInit(LaserScript.EndCall endCall, LaserScript.TargetCollapsed targetCollapsed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `endCall` | `Global.LaserScript.EndCall` |  |
| `targetCollapsed` | `Global.LaserScript.TargetCollapsed` |  |

### DisableLaser()

```csharp
public virtual void DisableLaser()
```

### EnableLaser(List<UnitModel>)

```csharp
public virtual bool EnableLaser(List<UnitModel> targetList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetList` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** System.Boolean

### HitScan(out bool)

```csharp
public UnitModel HitScan(out bool hasInner)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hasInner` | `System.Boolean` |  |

#### Returns

**Type:** Global.UnitModel

### Init(UnitModel)

```csharp
public virtual void Init(UnitModel caster)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caster` | `Global.UnitModel` |  |

### InitSprite()

```csharp
public virtual void InitSprite()
```

### IsEnabled()

```csharp
public bool IsEnabled()
```

#### Returns

**Type:** System.Boolean

### OnCreatureTargetSuppressed(CreatureModel)

```csharp
public virtual void OnCreatureTargetSuppressed(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnWorkerTargetDead(WorkerModel)

```csharp
public virtual void OnWorkerTargetDead(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### ReadyLine()

```csharp
public virtual void ReadyLine()
```

### SetItemPos(Vector3, Vector2)

```csharp
public virtual void SetItemPos(Vector3 end, Vector2 endSpace)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `end` | `UnityEngine.Vector3` |  |
| `endSpace` | `UnityEngine.Vector2` |  |

### SetLaserSprite()

```csharp
public virtual void SetLaserSprite()
```

### SetSprite(int)

```csharp
public virtual void SetSprite(int spriteIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteIndex` | `System.Int32` |  |

### SetStartParent(Transform)

```csharp
public virtual void SetStartParent(Transform t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Transform` |  |

### Shoot(UnitModel)

```csharp
public virtual void Shoot(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### Update()

```csharp
public virtual void Update()
```
