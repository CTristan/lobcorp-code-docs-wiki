---
uid: Global.AgentUnit
canonical_path: /api/Global/Worker/AgentUnit
---

# Class AgentUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentUnit : WorkerUnit, IOverlapOnclick, IMouseOnSelectListener, IMouseOnPointListener, IMouseOnDragListener, IMouseCommandTarget
```

An agent, as they appear in-game. Managed by [AgentLayer](/api/Global/IOBserver/AgentLayer).

Can be clicked on, renders the agent, controls panicking behavior, controls yapping, sets some animation things, controls shadows, weapon draw and sheathe, movement, sounds, death, some effects, and work notes(?). #inc

See also [AgentModel](/api/Global/Worker/AgentModel) for how agents are stored more internally.


### Unused
SpeechSet #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [WorkerUnit](/api/Global/Unit/WorkerUnit) → AgentUnit

## Implements
[IOverlapOnclick](/api/Global/Misc/IOverlapOnclick), [IMouseOnSelectListener](/api/Global/Misc/IMouseOnSelectListener), [IMouseOnPointListener](/api/Global/Misc/IMouseOnPointListener), [IMouseOnDragListener](/api/Global/Misc/IMouseOnDragListener), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget)

## Inherited Members
[workerModel](/api/Global/Unit/WorkerUnit#workermodel), [spineRenderer](/api/Global/Unit/WorkerUnit#spinerenderer), [_inCamera](/api/Global/Unit/WorkerUnit#incamera), [uiRoot](/api/Global/Unit/WorkerUnit#uiroot), [animRoot](/api/Global/Unit/WorkerUnit#animroot), [clickArea](/api/Global/Unit/WorkerUnit#clickarea), [shadow](/api/Global/Unit/WorkerUnit#shadow), [animEventHandler](/api/Global/Unit/WorkerUnit#animeventhandler), [spriteSetter](/api/Global/Unit/WorkerUnit#spritesetter), [weaponSetter](/api/Global/Unit/WorkerUnit#weaponsetter), [_animController](/api/Global/Unit/WorkerUnit#animcontroller), [showSpeech](/api/Global/Unit/WorkerUnit#showspeech), [barrierParent](/api/Global/Unit/WorkerUnit#barrierparent), [blockRotation](/api/Global/Unit/WorkerUnit#blockrotation), [blockMoving](/api/Global/Unit/WorkerUnit#blockmoving), [zValueDefault](/api/Global/Unit/WorkerUnit#zvaluedefault), [zValue](/api/Global/Unit/WorkerUnit#zvalue), [recoilPosition](/api/Global/Unit/WorkerUnit#recoilposition), [uiActivated](/api/Global/Unit/WorkerUnit#uiactivated), [effectAttached](/api/Global/Unit/WorkerUnit#effectattached), [animChanger](/api/Global/Unit/WorkerUnit#animchanger), [bufUI](/api/Global/Unit/WorkerUnit#bufui), [_animChangeReady](/api/Global/Unit/WorkerUnit#animchangeready), [_animChanged](/api/Global/Unit/WorkerUnit#animchanged), [_animChangeTimer](/api/Global/Unit/WorkerUnit#animchangetimer), [SetDefaultZValue(float)](/api/Global/Unit/WorkerUnit#setdefaultzvalue-float), [ResetZValue()](/api/Global/Unit/WorkerUnit#resetzvalue), [UpdateDirection()](/api/Global/Unit/WorkerUnit#updatedirection), [UpdateViewPosition()](/api/Global/Unit/WorkerUnit#updateviewposition), [UpdateCheckInCamera(Vector3)](/api/Global/Unit/WorkerUnit#updatecheckincamera-vector3), [UpdateAnimatorChange()](/api/Global/Unit/WorkerUnit#updateanimatorchange), [ChangeAnimatorForcely(string, bool, bool)](/api/Global/Unit/WorkerUnit#changeanimatorforcely-string-bool-bool), [ChangeAnimatorDefault()](/api/Global/Unit/WorkerUnit#changeanimatordefault), [LateUpdate()](/api/Global/Unit/WorkerUnit#lateupdate), [Attack(int, float)](/api/Global/Unit/WorkerUnit#attack-int-float), [EndAttack()](/api/Global/Unit/WorkerUnit#endattack), [SetWorkerFaceType(WorkerFaceType)](/api/Global/Unit/WorkerUnit#setworkerfacetype-workerfacetype), [SetDeadType(DeadType)](/api/Global/Unit/WorkerUnit#setdeadtype-deadtype), [SetPanic(bool)](/api/Global/Unit/WorkerUnit#setpanic-bool), [AttachUI(GameObject)](/api/Global/Unit/WorkerUnit#attachui-gameobject), [DisableUI()](/api/Global/Unit/WorkerUnit#disableui), [DisableShadow()](/api/Global/Unit/WorkerUnit#disableshadow), [SetClickArea(bool)](/api/Global/Unit/WorkerUnit#setclickarea-bool), [GetHairTransform()](/api/Global/Unit/WorkerUnit#gethairtransform), [GetBodyTransform()](/api/Global/Unit/WorkerUnit#getbodytransform), [MakeCreatureEffectToHead(long)](/api/Global/Unit/WorkerUnit#makecreatureeffecttohead-long), [AddUnitBuf(UnitBuf, Sprite)](/api/Global/Unit/WorkerUnit#addunitbuf-unitbuf-sprite), [AddUnitBuf(UnitBuf, BufRenderer, bool)](/api/Global/Unit/WorkerUnit#addunitbuf-unitbuf-bufrenderer-bool), [RemoveUnitBuf(UnitBuf)](/api/Global/Unit/WorkerUnit#removeunitbuf-unitbuf), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentUnit()

```csharp
public AgentUnit()
```

## Fields

### _selected

```csharp
private bool _selected
```
#INC


#### Field Value

**Type:** System.Boolean

### agentUI

```csharp
public AgentUI agentUI
```
#INC


#### Field Value

**Type:** InGameUI.AgentUI

### changer

```csharp
public AgentSpriteChanger changer
```
#INC


#### Field Value

**Type:** WorkerSpine.AgentSpriteChanger

### clicked

```csharp
public bool clicked
```
#INC


#### Field Value

**Type:** System.Boolean

### colors

```csharp
public AgentUnit.SelectedColors colors
```

#### Field Value

**Type:** Global.AgentUnit.SelectedColors

### continueUI

```csharp
public AgentContinueUI continueUI
```
#INC


#### Field Value

**Type:** Global.AgentContinueUI

### dead

```csharp
private bool dead
```
#INC


#### Field Value

**Type:** System.Boolean

### isModifiedPuppetScale

```csharp
private bool isModifiedPuppetScale
```
#INC


#### Field Value

**Type:** System.Boolean

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

### lateInit

```csharp
private bool lateInit
```
#INC


#### Field Value

**Type:** System.Boolean

### managing

```csharp
private bool managing
```
#INC


#### Field Value

**Type:** System.Boolean

### model

```csharp
public AgentModel model
```
#INC


#### Field Value

**Type:** Global.AgentModel

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

### selectedIcon

```csharp
public SpriteRenderer selectedIcon
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### selectIconState

```csharp
private bool selectIconState
```
#INC


#### Field Value

**Type:** System.Boolean

### speech_cooltime

```csharp
public float speech_cooltime
```
#INC


#### Field Value

**Type:** System.Single

### speech_ealpsed

```csharp
private float speech_ealpsed
```
#INC


#### Field Value

**Type:** System.Single

### speech_enable

```csharp
private bool speech_enable
```
#INC


#### Field Value

**Type:** System.Boolean

### speech_force

```csharp
private bool speech_force
```
#INC


#### Field Value

**Type:** System.Boolean

### speech_force_elapsed

```csharp
private float speech_force_elapsed
```
#INC


#### Field Value

**Type:** System.Single

### speech_frequency

```csharp
public float speech_frequency
```
#INC


#### Field Value

**Type:** System.Single

### speech_percentage

```csharp
public int speech_percentage
```
#INC


#### Field Value

**Type:** System.Int32

### speechText

```csharp
public Text speechText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ui

```csharp
public AgentUnitUI ui
```
#INC


#### Field Value

**Type:** Global.AgentUnitUI

## Methods

### AppearNote()

```csharp
public void AppearNote()
```
#INC


### Awake()

```csharp
private void Awake()
```
#INC


### BlockMove()

```csharp
public void BlockMove()
```
#INC


### CancelWeapon()

```csharp
public void CancelWeapon()
```
#INC


### CharRecoil(Queue<Vector3>, RecoilEffect)

```csharp
private IEnumerator CharRecoil(Queue<Vector3> queue, RecoilEffect recoil)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `queue` | `System.Collections.Generic.Queue{UnityEngine.Vector3}` |  |
| `recoil` | `Global.RecoilEffect` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### CharRecoilInput(int)

```csharp
public void CharRecoilInput(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### ClearEffect()

```csharp
public void ClearEffect()
```
#INC


### DisappearNote()

```csharp
public void DisappearNote()
```
#INC


### EndWork()

```csharp
public void EndWork()
```
#INC


### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### FlipPuppetNode(bool)

```csharp
public void FlipPuppetNode(bool isLeft)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isLeft` | `System.Boolean` |  |

### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```
#INC


#### Returns

**Type:** Global.IMouseCommandTargetModel

### HasPointListener()

```csharp
public bool HasPointListener()
```
#INC


#### Returns

**Type:** System.Boolean

### IsDragSelectable()

```csharp
public bool IsDragSelectable()
```
#INC


#### Returns

**Type:** System.Boolean

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
public GameObject MakeCreatureEffect(CreatureModel model, bool addlist)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `addlist` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffect(long)

```csharp
public GameObject MakeCreatureEffect(long modelID)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `modelID` | `System.Int64` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectAttach(string, Transform)

```csharp
public GameObject MakeEffectAttach(string src, Transform pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Transform` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectAttach(string, Transform, bool)

```csharp
public GameObject MakeEffectAttach(string src, Transform pos, bool addedList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Transform` |  |
| `addedList` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### ManagingCreature()

```csharp
public void ManagingCreature()
```
#INC


### MannualMoving(Vector3, bool)

```csharp
private IEnumerator MannualMoving(Vector3 pos, bool blockMoving)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `blockMoving` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### MannualMoving(Vector3, bool, float)

```csharp
private IEnumerator MannualMoving(Vector3 pos, bool blockMoving, float unitWaitTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `blockMoving` | `System.Boolean` |  |
| `unitWaitTime` | `System.Single` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### MannualMovingCall(Vector3)

```csharp
public bool MannualMovingCall(Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** System.Boolean

### MannualMovingCall(Vector3, float)

```csharp
public bool MannualMovingCall(Vector3 pos, float unitWaitTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
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

### OnChangeArmor()

```csharp
public void OnChangeArmor()
```
#INC


### OnChangeKitCreature()

```csharp
public void OnChangeKitCreature()
```
#INC


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


### OnEnter()

```csharp
public void OnEnter()
```
#INC


### OnEnterDragArea()

```csharp
public void OnEnterDragArea()
```
#INC


### OnExit()

```csharp
public void OnExit()
```
#INC


### OnExitDragArea()

```csharp
public void OnExitDragArea()
```
#INC


### OnLateInit()

```csharp
public void OnLateInit()
```
#INC


### OnOverlayDisabled()

```csharp
public void OnOverlayDisabled()
```
#INC


### OnOverlayEnabled()

```csharp
public void OnOverlayEnabled()
```
#INC


### OnPointEnter()

```csharp
public void OnPointEnter()
```
#INC


### OnPointExit()

```csharp
public void OnPointExit()
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


### OpenStatusWindow()

```csharp
public void OpenStatusWindow()
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


### ReleaseMove()

```csharp
public void ReleaseMove()
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


### SelectIconDisable()

```csharp
public void SelectIconDisable()
```
#INC


### SelectIconForcelyEnable()

```csharp
public void SelectIconForcelyEnable()
```
#INC


### SetAgentAnimatorModel()

```csharp
public void SetAgentAnimatorModel()
```
#INC


### SetGiftModel(EGOgiftModel, bool)

```csharp
public void SetGiftModel(EGOgiftModel model, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetSelectIconColor()

```csharp
public void SetSelectIconColor()
```
#INC


### SetSlider()

```csharp
private void SetSlider()
```
#INC


### SetWorkNote(int)

```csharp
public void SetWorkNote(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### ShutUp()

```csharp
public override void ShutUp()
```
#INC


### SpeechDefaultLyric()

```csharp
public void SpeechDefaultLyric()
```
#INC


### SpeechDefaultLyricForce()

```csharp
public void SpeechDefaultLyricForce()
```
#INC


### SpeechHorrorLyric(int)

```csharp
public void SpeechHorrorLyric(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SpeechOtherdeadLyric(int, string)

```csharp
public void SpeechOtherdeadLyric(int level, string param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `param` | `System.String` |  |

### SpeechOtherpanicLyric(int, string)

```csharp
public void SpeechOtherpanicLyric(int level, string param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `param` | `System.String` |  |

### SpeechSet(bool)

```csharp
public void SpeechSet(bool isClick)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isClick` | `System.Boolean` |  |

### StageStartCheck()

```csharp
public void StageStartCheck()
```
#INC


### Start()

```csharp
public void Start()
```
#INC


### StartWork()

```csharp
public void StartWork()
```
#INC


### UIRecoil(Queue<Vector3>, RecoilEffectUI)

```csharp
private IEnumerator UIRecoil(Queue<Vector3> queue, RecoilEffectUI recoil)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `queue` | `System.Collections.Generic.Queue{UnityEngine.Vector3}` |  |
| `recoil` | `Global.RecoilEffectUI` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### UIRecoilInput(int, int)

```csharp
public void UIRecoilInput(int level, int target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `target` | `System.Int32` |  |

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


### UpdateGiftModel()

```csharp
public void UpdateGiftModel()
```
#INC


### UpdateHair()

```csharp
public void UpdateHair()
```
#INC

