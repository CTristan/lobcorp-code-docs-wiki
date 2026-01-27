---
uid: Global.OfficerUnit
canonical_path: /api/Global/Worker/OfficerUnit
---

# Class OfficerUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerUnit : WorkerUnit, IMouseOnSelectListener, IMouseCommandTarget
```

Represents a [clerk](/api/Global/Worker/OfficerModel) in-game.

Reminder that clerks don't matter. Mostly.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [WorkerUnit](/api/Global/Unit/WorkerUnit) → OfficerUnit

## Implements
[IMouseOnSelectListener](/api/Global/Misc/IMouseOnSelectListener), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget)

## Inherited Members
[workerModel](/api/Global/Unit/WorkerUnit#workermodel), [spineRenderer](/api/Global/Unit/WorkerUnit#spinerenderer), [_inCamera](/api/Global/Unit/WorkerUnit#incamera), [uiRoot](/api/Global/Unit/WorkerUnit#uiroot), [animRoot](/api/Global/Unit/WorkerUnit#animroot), [clickArea](/api/Global/Unit/WorkerUnit#clickarea), [shadow](/api/Global/Unit/WorkerUnit#shadow), [animEventHandler](/api/Global/Unit/WorkerUnit#animeventhandler), [spriteSetter](/api/Global/Unit/WorkerUnit#spritesetter), [weaponSetter](/api/Global/Unit/WorkerUnit#weaponsetter), [_animController](/api/Global/Unit/WorkerUnit#animcontroller), [showSpeech](/api/Global/Unit/WorkerUnit#showspeech), [barrierParent](/api/Global/Unit/WorkerUnit#barrierparent), [blockRotation](/api/Global/Unit/WorkerUnit#blockrotation), [blockMoving](/api/Global/Unit/WorkerUnit#blockmoving), [zValueDefault](/api/Global/Unit/WorkerUnit#zvaluedefault), [zValue](/api/Global/Unit/WorkerUnit#zvalue), [recoilPosition](/api/Global/Unit/WorkerUnit#recoilposition), [uiActivated](/api/Global/Unit/WorkerUnit#uiactivated), [effectAttached](/api/Global/Unit/WorkerUnit#effectattached), [animChanger](/api/Global/Unit/WorkerUnit#animchanger), [bufUI](/api/Global/Unit/WorkerUnit#bufui), [_animChangeReady](/api/Global/Unit/WorkerUnit#animchangeready), [_animChanged](/api/Global/Unit/WorkerUnit#animchanged), [_animChangeTimer](/api/Global/Unit/WorkerUnit#animchangetimer), [SetDefaultZValue(float)](/api/Global/Unit/WorkerUnit#setdefaultzvalue-float), [ResetZValue()](/api/Global/Unit/WorkerUnit#resetzvalue), [UpdateDirection()](/api/Global/Unit/WorkerUnit#updatedirection), [UpdateViewPosition()](/api/Global/Unit/WorkerUnit#updateviewposition), [UpdateCheckInCamera(Vector3)](/api/Global/Unit/WorkerUnit#updatecheckincamera-vector3), [UpdateAnimatorChange()](/api/Global/Unit/WorkerUnit#updateanimatorchange), [ChangeAnimatorForcely(string, bool, bool)](/api/Global/Unit/WorkerUnit#changeanimatorforcely-string-bool-bool), [ChangeAnimatorDefault()](/api/Global/Unit/WorkerUnit#changeanimatordefault), [LateUpdate()](/api/Global/Unit/WorkerUnit#lateupdate), [Attack(int, float)](/api/Global/Unit/WorkerUnit#attack-int-float), [EndAttack()](/api/Global/Unit/WorkerUnit#endattack), [SetWorkerFaceType(WorkerFaceType)](/api/Global/Unit/WorkerUnit#setworkerfacetype-workerfacetype), [SetDeadType(DeadType)](/api/Global/Unit/WorkerUnit#setdeadtype-deadtype), [AttachUI(GameObject)](/api/Global/Unit/WorkerUnit#attachui-gameobject), [DisableUI()](/api/Global/Unit/WorkerUnit#disableui), [DisableShadow()](/api/Global/Unit/WorkerUnit#disableshadow), [SetClickArea(bool)](/api/Global/Unit/WorkerUnit#setclickarea-bool), [GetHairTransform()](/api/Global/Unit/WorkerUnit#gethairtransform), [GetBodyTransform()](/api/Global/Unit/WorkerUnit#getbodytransform), [MakeCreatureEffectToHead(long)](/api/Global/Unit/WorkerUnit#makecreatureeffecttohead-long), [AddUnitBuf(UnitBuf, Sprite)](/api/Global/Unit/WorkerUnit#addunitbuf-unitbuf-sprite), [AddUnitBuf(UnitBuf, BufRenderer, bool)](/api/Global/Unit/WorkerUnit#addunitbuf-unitbuf-bufrenderer-bool), [RemoveUnitBuf(UnitBuf)](/api/Global/Unit/WorkerUnit#removeunitbuf-unitbuf), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


#### Field Value

**Type:** System.Single

### changeState

```csharp
private bool changeState
```
#INC


#### Field Value

**Type:** System.Boolean

### currentBool

```csharp
private string currentBool
```
#INC


#### Field Value

**Type:** System.String

### isMovingByMannually

```csharp
public bool isMovingByMannually
```
#INC


#### Field Value

**Type:** System.Boolean

### isMovingStarted

```csharp
private bool isMovingStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### memoObject

```csharp
public GameObject memoObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### model

```csharp
public OfficerModel model
```
#INC


#### Field Value

**Type:** Global.OfficerModel

### officerAttackedAnimator

```csharp
public GameObject officerAttackedAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### oldPuppetAnimController

```csharp
private RuntimeAnimatorController oldPuppetAnimController
```
#INC


#### Field Value

**Type:** UnityEngine.RuntimeAnimatorController

### puppetAnimHasMoveCheck

```csharp
private bool puppetAnimHasMoveCheck
```
#INC


#### Field Value

**Type:** System.Boolean

### sounds

```csharp
public Dictionary<string, SoundEffectPlayer> sounds
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SoundEffectPlayer}

### tempZval

```csharp
public float tempZval
```
#INC


#### Field Value

**Type:** System.Single

### ui

```csharp
public OfficerUnitUI ui
```
#INC


#### Field Value

**Type:** Global.OfficerUnitUI

### uiOpened

```csharp
private bool uiOpened
```
#INC


#### Field Value

**Type:** System.Boolean

### waitTimer

```csharp
private float waitTimer
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### Awake()

```csharp
private void Awake()
```
#INC


### CancelWeapon()

```csharp
public void CancelWeapon()
```
#INC


### CheckMannualMovingEnd()

```csharp
public bool CheckMannualMovingEnd()
```
#INC


#### Returns

**Type:** System.Boolean

### ClearEffect()

```csharp
public void ClearEffect()
```
#INC


### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```
#INC


#### Returns

**Type:** Global.IMouseCommandTargetModel

### IsSelectable()

```csharp
public bool IsSelectable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeCreatureEffect(CreatureModel)

```csharp
public GameObject MakeCreatureEffect(CreatureModel model)
```
#INC


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
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `t` | `UnityEngine.Transform` |  |

### MannualMoving(Vector3, bool, bool, bool, bool, bool, float)

```csharp
private IEnumerator MannualMoving(Vector3 pos, bool block, bool moveZ, bool moveAnim, bool scaling, bool small, float unitWaitTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `block` | `System.Boolean` |  |
| `moveZ` | `System.Boolean` |  |
| `moveAnim` | `System.Boolean` |  |
| `scaling` | `System.Boolean` |  |
| `small` | `System.Boolean` |  |
| `unitWaitTime` | `System.Single` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### MannualMovingCall(Vector3, bool, bool, bool, bool, bool, float)

```csharp
public bool MannualMovingCall(Vector3 pos, bool blockMov, bool moveZ, bool moveAnim, bool scailing, bool small, float unitWaitTime)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### MannualMovingWithTime(Vector3, bool, float)

```csharp
private IEnumerator MannualMovingWithTime(Vector3 pos, bool blockMoving, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `blockMoving` | `System.Boolean` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### OnChangeWeapon()

```csharp
public void OnChangeWeapon()
```
#INC


### OnClick()

```csharp
public void OnClick()
```
#INC


### OnDie()

```csharp
public void OnDie()
```
#INC


### OnResurrect()

```csharp
public void OnResurrect()
```
#INC


### OnSelect()

```csharp
public void OnSelect()
```
#INC


### OnSuicide()

```csharp
public void OnSuicide()
```
#INC


### OnUnselect()

```csharp
public void OnUnselect()
```
#INC


### PlaySound(string, string, bool)

```csharp
public SoundEffectPlayer PlaySound(string src, string key, bool isLoop)
```
#INC


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
#INC


### ReleaseUpdatePosition()

```csharp
public void ReleaseUpdatePosition()
```
#INC


### RemoveShadow()

```csharp
public override void RemoveShadow()
```
#INC


### RevealShadow()

```csharp
public void RevealShadow()
```
#INC


### SetModel(OfficerModel)

```csharp
public void SetModel(OfficerModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OfficerModel` |  |

### SetPanic(bool)

```csharp
public override void SetPanic(bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### ShutUp()

```csharp
public override void ShutUp()
```
#INC


### Start()

```csharp
public void Start()
```
#INC


### StopSound(string)

```csharp
public void StopSound(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### Update()

```csharp
private void Update()
```
#INC


### UpdateAnimationQuality()

```csharp
protected override void UpdateAnimationQuality()
```
#INC

