# Class OfficerUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerUnit : WorkerUnit, IMouseOnSelectListener, IMouseCommandTarget
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [WorkerUnit](/api/WorkerUnit) → OfficerUnit

## Inherited Members
[workerModel](/api/WorkerUnit#workermodel), [spineRenderer](/api/WorkerUnit#spinerenderer), [_inCamera](/api/WorkerUnit#incamera), [uiRoot](/api/WorkerUnit#uiroot), [animRoot](/api/WorkerUnit#animroot), [clickArea](/api/WorkerUnit#clickarea), [shadow](/api/WorkerUnit#shadow), [animEventHandler](/api/WorkerUnit#animeventhandler), [spriteSetter](/api/WorkerUnit#spritesetter), [weaponSetter](/api/WorkerUnit#weaponsetter), [_animController](/api/WorkerUnit#animcontroller), [showSpeech](/api/WorkerUnit#showspeech), [barrierParent](/api/WorkerUnit#barrierparent), [blockRotation](/api/WorkerUnit#blockrotation), [blockMoving](/api/WorkerUnit#blockmoving), [zValue](/api/WorkerUnit#zvalue), [recoilPosition](/api/WorkerUnit#recoilposition), [uiActivated](/api/WorkerUnit#uiactivated), [effectAttached](/api/WorkerUnit#effectattached), [animChanger](/api/WorkerUnit#animchanger), [bufUI](/api/WorkerUnit#bufui), [_animChangeReady](/api/WorkerUnit#animchangeready), [_animChanged](/api/WorkerUnit#animchanged), [_animChangeTimer](/api/WorkerUnit#animchangetimer), [SetDefaultZValue(float)](/api/WorkerUnit#setdefaultzvalue-float), [ResetZValue()](/api/WorkerUnit#resetzvalue), [UpdateDirection()](/api/WorkerUnit#updatedirection), [UpdateViewPosition()](/api/WorkerUnit#updateviewposition), [UpdateAnimatorChange()](/api/WorkerUnit#updateanimatorchange), [ChangeAnimatorForcely(string, bool, bool)](/api/WorkerUnit#changeanimatorforcely-string-bool-bool), [ChangeAnimatorDefault()](/api/WorkerUnit#changeanimatordefault), [LateUpdate()](/api/WorkerUnit#lateupdate), [Attack(int, float)](/api/WorkerUnit#attack-int-float), [EndAttack()](/api/WorkerUnit#endattack), [SetWorkerFaceType(WorkerFaceType)](/api/WorkerUnit#setworkerfacetype-workerfacetype), [SetDeadType(DeadType)](/api/WorkerUnit#setdeadtype-deadtype), [AttachUI(GameObject)](/api/WorkerUnit#attachui-gameobject), [DisableUI()](/api/WorkerUnit#disableui), [DisableShadow()](/api/WorkerUnit#disableshadow), [SetClickArea(bool)](/api/WorkerUnit#setclickarea-bool), [GetHairTransform()](/api/WorkerUnit#gethairtransform), [GetBodyTransform()](/api/WorkerUnit#getbodytransform), [MakeCreatureEffectToHead(long)](/api/WorkerUnit#makecreatureeffecttohead-long), [AddUnitBuf(UnitBuf, Sprite)](/api/WorkerUnit#addunitbuf-unitbuf-sprite), [AddUnitBuf(UnitBuf, BufRenderer, bool)](/api/WorkerUnit#addunitbuf-unitbuf-bufrenderer-bool), [RemoveUnitBuf(UnitBuf)](/api/WorkerUnit#removeunitbuf-unitbuf), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OfficerUnit()

```csharp
public OfficerUnit()
```

## Fields

### backZVal

```csharp
public const float backZVal = 0
```

#### Field Value

**Type:** System.Single

### isMovingByMannually

```csharp
public bool isMovingByMannually
```

#### Field Value

**Type:** System.Boolean

### memoObject

```csharp
public GameObject memoObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### model

```csharp
public OfficerModel model
```

#### Field Value

**Type:** Global.OfficerModel

### officerAttackedAnimator

```csharp
public GameObject officerAttackedAnimator
```

#### Field Value

**Type:** UnityEngine.GameObject

### sounds

```csharp
public Dictionary<string, SoundEffectPlayer> sounds
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SoundEffectPlayer}

### tempZval

```csharp
public float tempZval
```

#### Field Value

**Type:** System.Single

### ui

```csharp
public OfficerUnitUI ui
```

#### Field Value

**Type:** Global.OfficerUnitUI

## Methods

### CancelWeapon()

```csharp
public void CancelWeapon()
```

### CheckMannualMovingEnd()

```csharp
public bool CheckMannualMovingEnd()
```

#### Returns

**Type:** System.Boolean

### ClearEffect()

```csharp
public void ClearEffect()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```

#### Returns

**Type:** Global.IMouseCommandTargetModel

### IsSelectable()

```csharp
public bool IsSelectable()
```

#### Returns

**Type:** System.Boolean

### MakeCreatureEffect(CreatureModel)

```csharp
public GameObject MakeCreatureEffect(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffect(CreatureModel, bool)

```csharp
public GameObject MakeCreatureEffect(CreatureModel model, bool attach)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `attach` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffect(long)

```csharp
public GameObject MakeCreatureEffect(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectAttach(string, Transform)

```csharp
public void MakeEffectAttach(string src, Transform t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `t` | `UnityEngine.Transform` |  |

### MannualMovingCall(Vector3, bool, bool, bool, bool, bool, float)

```csharp
public bool MannualMovingCall(Vector3 pos, bool blockMov, bool moveZ, bool moveAnim, bool scailing, bool small, float unitWaitTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `blockMov` | `System.Boolean` |  |
| `moveZ` | `System.Boolean` |  |
| `moveAnim` | `System.Boolean` |  |
| `scailing` | `System.Boolean` |  |
| `small` | `System.Boolean` |  |
| `unitWaitTime` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### MannualMovingCallWithTime(Vector3, float)

```csharp
public bool MannualMovingCallWithTime(Vector3 pos, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### OnChangeWeapon()

```csharp
public void OnChangeWeapon()
```

### OnClick()

```csharp
public void OnClick()
```

### OnDie()

```csharp
public void OnDie()
```

### OnResurrect()

```csharp
public void OnResurrect()
```

### OnSelect()

```csharp
public void OnSelect()
```

### OnSuicide()

```csharp
public void OnSuicide()
```

### OnUnselect()

```csharp
public void OnUnselect()
```

### PlaySound(string, string, bool)

```csharp
public SoundEffectPlayer PlaySound(string src, string key, bool isLoop)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `key` | `System.String` |  |
| `isLoop` | `System.Boolean` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PrepareWeapon()

```csharp
public void PrepareWeapon()
```

### ReleaseUpdatePosition()

```csharp
public void ReleaseUpdatePosition()
```

### RemoveShadow()

```csharp
public override void RemoveShadow()
```

### RevealShadow()

```csharp
public void RevealShadow()
```

### SetModel(OfficerModel)

```csharp
public void SetModel(OfficerModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OfficerModel` |  |

### SetPanic(bool)

```csharp
public override void SetPanic(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### ShutUp()

```csharp
public override void ShutUp()
```

### Start()

```csharp
public void Start()
```

### StopSound(string)

```csharp
public void StopSound(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### UpdateAnimationQuality()

```csharp
protected override void UpdateAnimationQuality()
```
