# Class AgentUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentUnit : WorkerUnit, IOverlapOnclick, IMouseOnSelectListener, IMouseOnPointListener, IMouseOnDragListener, IMouseCommandTarget
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [WorkerUnit](/api/WorkerUnit) → AgentUnit

## Inherited Members
[workerModel](/api/WorkerUnit#workermodel), [spineRenderer](/api/WorkerUnit#spinerenderer), [_inCamera](/api/WorkerUnit#incamera), [uiRoot](/api/WorkerUnit#uiroot), [animRoot](/api/WorkerUnit#animroot), [clickArea](/api/WorkerUnit#clickarea), [shadow](/api/WorkerUnit#shadow), [animEventHandler](/api/WorkerUnit#animeventhandler), [spriteSetter](/api/WorkerUnit#spritesetter), [weaponSetter](/api/WorkerUnit#weaponsetter), [_animController](/api/WorkerUnit#animcontroller), [showSpeech](/api/WorkerUnit#showspeech), [barrierParent](/api/WorkerUnit#barrierparent), [blockRotation](/api/WorkerUnit#blockrotation), [blockMoving](/api/WorkerUnit#blockmoving), [zValue](/api/WorkerUnit#zvalue), [recoilPosition](/api/WorkerUnit#recoilposition), [uiActivated](/api/WorkerUnit#uiactivated), [effectAttached](/api/WorkerUnit#effectattached), [animChanger](/api/WorkerUnit#animchanger), [bufUI](/api/WorkerUnit#bufui), [_animChangeReady](/api/WorkerUnit#animchangeready), [_animChanged](/api/WorkerUnit#animchanged), [_animChangeTimer](/api/WorkerUnit#animchangetimer), [SetDefaultZValue(float)](/api/WorkerUnit#setdefaultzvalue-float), [ResetZValue()](/api/WorkerUnit#resetzvalue), [UpdateDirection()](/api/WorkerUnit#updatedirection), [UpdateViewPosition()](/api/WorkerUnit#updateviewposition), [UpdateAnimatorChange()](/api/WorkerUnit#updateanimatorchange), [ChangeAnimatorForcely(string, bool, bool)](/api/WorkerUnit#changeanimatorforcely-string-bool-bool), [ChangeAnimatorDefault()](/api/WorkerUnit#changeanimatordefault), [LateUpdate()](/api/WorkerUnit#lateupdate), [Attack(int, float)](/api/WorkerUnit#attack-int-float), [EndAttack()](/api/WorkerUnit#endattack), [SetWorkerFaceType(WorkerFaceType)](/api/WorkerUnit#setworkerfacetype-workerfacetype), [SetDeadType(DeadType)](/api/WorkerUnit#setdeadtype-deadtype), [SetPanic(bool)](/api/WorkerUnit#setpanic-bool), [AttachUI(GameObject)](/api/WorkerUnit#attachui-gameobject), [DisableUI()](/api/WorkerUnit#disableui), [DisableShadow()](/api/WorkerUnit#disableshadow), [SetClickArea(bool)](/api/WorkerUnit#setclickarea-bool), [GetHairTransform()](/api/WorkerUnit#gethairtransform), [GetBodyTransform()](/api/WorkerUnit#getbodytransform), [MakeCreatureEffectToHead(long)](/api/WorkerUnit#makecreatureeffecttohead-long), [AddUnitBuf(UnitBuf, Sprite)](/api/WorkerUnit#addunitbuf-unitbuf-sprite), [AddUnitBuf(UnitBuf, BufRenderer, bool)](/api/WorkerUnit#addunitbuf-unitbuf-bufrenderer-bool), [RemoveUnitBuf(UnitBuf)](/api/WorkerUnit#removeunitbuf-unitbuf), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentUnit()

```csharp
public AgentUnit()
```

## Fields

### agentUI

```csharp
public AgentUI agentUI
```

#### Field Value

**Type:** InGameUI.AgentUI

### changer

```csharp
public AgentSpriteChanger changer
```

#### Field Value

**Type:** WorkerSpine.AgentSpriteChanger

### clicked

```csharp
public bool clicked
```

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

#### Field Value

**Type:** Global.AgentContinueUI

### isMovingByMannually

```csharp
public bool isMovingByMannually
```

#### Field Value

**Type:** System.Boolean

### model

```csharp
public AgentModel model
```

#### Field Value

**Type:** Global.AgentModel

### selectedIcon

```csharp
public SpriteRenderer selectedIcon
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### speech_cooltime

```csharp
public float speech_cooltime
```

#### Field Value

**Type:** System.Single

### speech_frequency

```csharp
public float speech_frequency
```

#### Field Value

**Type:** System.Single

### speech_percentage

```csharp
public int speech_percentage
```

#### Field Value

**Type:** System.Int32

### speechText

```csharp
public Text speechText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ui

```csharp
public AgentUnitUI ui
```

#### Field Value

**Type:** Global.AgentUnitUI

## Methods

### AppearNote()

```csharp
public void AppearNote()
```

### BlockMove()

```csharp
public void BlockMove()
```

### CancelWeapon()

```csharp
public void CancelWeapon()
```

### CharRecoilInput(int)

```csharp
public void CharRecoilInput(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### ClearEffect()

```csharp
public void ClearEffect()
```

### DisappearNote()

```csharp
public void DisappearNote()
```

### EndWork()

```csharp
public void EndWork()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### FlipPuppetNode(bool)

```csharp
public void FlipPuppetNode(bool isLeft)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isLeft` | `System.Boolean` |  |

### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```

#### Returns

**Type:** Global.IMouseCommandTargetModel

### HasPointListener()

```csharp
public bool HasPointListener()
```

#### Returns

**Type:** System.Boolean

### IsDragSelectable()

```csharp
public bool IsDragSelectable()
```

#### Returns

**Type:** System.Boolean

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
public GameObject MakeCreatureEffect(CreatureModel model, bool addlist)
```

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

### MannualMovingCall(Vector3)

```csharp
public bool MannualMovingCall(Vector3 pos)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### OnChangeArmor()

```csharp
public void OnChangeArmor()
```

### OnChangeKitCreature()

```csharp
public void OnChangeKitCreature()
```

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

### OnEnter()

```csharp
public void OnEnter()
```

### OnEnterDragArea()

```csharp
public void OnEnterDragArea()
```

### OnExit()

```csharp
public void OnExit()
```

### OnExitDragArea()

```csharp
public void OnExitDragArea()
```

### OnLateInit()

```csharp
public void OnLateInit()
```

### OnOverlayDisabled()

```csharp
public void OnOverlayDisabled()
```

### OnOverlayEnabled()

```csharp
public void OnOverlayEnabled()
```

### OnPointEnter()

```csharp
public void OnPointEnter()
```

### OnPointExit()

```csharp
public void OnPointExit()
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

### OpenStatusWindow()

```csharp
public void OpenStatusWindow()
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

### ReleaseMove()

```csharp
public void ReleaseMove()
```

### RemoveShadow()

```csharp
public override void RemoveShadow()
```

### RevealShadow()

```csharp
public void RevealShadow()
```

### SelectIconDisable()

```csharp
public void SelectIconDisable()
```

### SelectIconForcelyEnable()

```csharp
public void SelectIconForcelyEnable()
```

### SetAgentAnimatorModel()

```csharp
public void SetAgentAnimatorModel()
```

### SetGiftModel(EGOgiftModel, bool)

```csharp
public void SetGiftModel(EGOgiftModel model, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetSelectIconColor()

```csharp
public void SetSelectIconColor()
```

### SetWorkNote(int)

```csharp
public void SetWorkNote(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### ShutUp()

```csharp
public override void ShutUp()
```

### SpeechDefaultLyric()

```csharp
public void SpeechDefaultLyric()
```

### SpeechDefaultLyricForce()

```csharp
public void SpeechDefaultLyricForce()
```

### SpeechHorrorLyric(int)

```csharp
public void SpeechHorrorLyric(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SpeechOtherdeadLyric(int, string)

```csharp
public void SpeechOtherdeadLyric(int level, string param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `param` | `System.String` |  |

### SpeechOtherpanicLyric(int, string)

```csharp
public void SpeechOtherpanicLyric(int level, string param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `param` | `System.String` |  |

### SpeechSet(bool)

```csharp
public void SpeechSet(bool isClick)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isClick` | `System.Boolean` |  |

### StageStartCheck()

```csharp
public void StageStartCheck()
```

### Start()

```csharp
public void Start()
```

### StartWork()

```csharp
public void StartWork()
```

### UIRecoilInput(int, int)

```csharp
public void UIRecoilInput(int level, int target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `target` | `System.Int32` |  |

### UpdateAnimationQuality()

```csharp
protected override void UpdateAnimationQuality()
```

### UpdateGiftModel()

```csharp
public void UpdateGiftModel()
```

### UpdateHair()

```csharp
public void UpdateHair()
```
