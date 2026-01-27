---
uid: Global.CreatureUnit
canonical_path: /api/Global/Unit/CreatureUnit
---

# Class CreatureUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureUnit : MonoBehaviour, IMouseOnSelectListener, IMouseCommandTarget
```

An abnormality or ordeal as it appears in-game (in particular, when breaching).
See also [CreatureModel](/api/Global/Model/CreatureModel) for abnormalities more generally and [CreatureBase](/api/Global/Creature/CreatureBase) for their scripts.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreatureUnit

## Derived
[ChildCreatureUnit](/api/Global/Creature/ChildCreatureUnit)

## Implements
[IMouseOnSelectListener](/api/Global/Misc/IMouseOnSelectListener), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureUnit()

```csharp
public CreatureUnit()
```

## Fields

### _unitMouseEventTarget

```csharp
public UnitMouseEventTarget _unitMouseEventTarget
```
#INC


#### Field Value

**Type:** Global.UnitMouseEventTarget

### animTarget

```csharp
public CreatureAnimScript animTarget
```
#INC


#### Field Value

**Type:** Global.CreatureAnimScript

### cameraSensingArea

```csharp
public Image cameraSensingArea
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### casting

```csharp
public CreatureUnit.SliderColorSet casting
```

#### Field Value

**Type:** Global.CreatureUnit.SliderColorSet

### castingSlider

```csharp
public Slider castingSlider
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Slider

### currentCreatureCanvas

```csharp
public Canvas currentCreatureCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### currentSliderColor

```csharp
private CreatureUnit.SliderColorSet currentSliderColor
```

#### Field Value

**Type:** Global.CreatureUnit.SliderColorSet

### debugText

```csharp
[Header("Debug")]
public Text debugText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### defaultMouseTarget

```csharp
public UnitMouseEventTarget defaultMouseTarget
```
#INC


#### Field Value

**Type:** Global.UnitMouseEventTarget

### defHp

```csharp
[Space(10)]
public CreatureUnit.SliderColorSet defHp
```

#### Field Value

**Type:** Global.CreatureUnit.SliderColorSet

### directionScaleFactor

```csharp
protected Vector3 directionScaleFactor
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### escapeCreatureName

```csharp
public Text escapeCreatureName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### escapeRisk

```csharp
public Text escapeRisk
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### escapeUIRoot

```csharp
[Header("UI")]
public GameObject escapeUIRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### hpBg

```csharp
public Image hpBg
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### hpFill

```csharp
public Image hpFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### hpSlider

```csharp
public Slider hpSlider
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Slider

### model

```csharp
public CreatureModel model
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### oldScale

```csharp
private Vector2 oldScale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### oldState

```csharp
protected CreatureState oldState
```
#INC


#### Field Value

**Type:** Global.CreatureState

### returnObject

```csharp
public GameObject returnObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### returnSpriteRenderer

```csharp
public SpriteRenderer returnSpriteRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### room

```csharp
public IsolateRoom room
```
#INC


#### Field Value

**Type:** Global.IsolateRoom

### scaleFactor

```csharp
protected Vector3 scaleFactor
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### scaleSetting

```csharp
public bool scaleSetting
```
#INC


#### Field Value

**Type:** System.Boolean

### speech

```csharp
public CreatureSpeech speech
```
#INC


#### Field Value

**Type:** Global.CreatureSpeech

### viewPosition

```csharp
protected Vector3 viewPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### visible

```csharp
protected bool visible
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### Awake()

```csharp
public virtual void Awake()
```
#INC


### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```
#INC


#### Returns

**Type:** Global.IMouseCommandTargetModel

### GetScaleFactor()

```csharp
public Vector3 GetScaleFactor()
```
#INC


#### Returns

**Type:** UnityEngine.Vector3

### IsSelectable()

```csharp
public bool IsSelectable()
```
#INC


#### Returns

**Type:** System.Boolean

### LateUpdate()

```csharp
public virtual void LateUpdate()
```
#INC


### OnChangeState()

```csharp
public virtual void OnChangeState()
```
#INC


### OnClickByRoom(PointerEventData)

```csharp
public void OnClickByRoom(PointerEventData pData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnClickCollectionFunc()

```csharp
public void OnClickCollectionFunc()
```
#INC


### OnClicked()

```csharp
public void OnClicked()
```
#INC


### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnSelect()

```csharp
public void OnSelect()
```
#INC


### OnUnselect()

```csharp
public void OnUnselect()
```
#INC


### PlaySound(string)

```csharp
public SoundEffectPlayer PlaySound(string soundKey)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySound(string, AudioRolloffMode)

```csharp
public SoundEffectPlayer PlaySound(string soundKey, AudioRolloffMode mode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |
| `mode` | `UnityEngine.AudioRolloffMode` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySound(string, float)

```csharp
public SoundEffectPlayer PlaySound(string soundKey, float volume)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |
| `volume` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySoundLoop(string)

```csharp
public SoundEffectPlayer PlaySoundLoop(string soundKey)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySoundLoop(string, float)

```csharp
public SoundEffectPlayer PlaySoundLoop(string soundKey, float volume)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |
| `volume` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### PlaySoundMono(string)

```csharp
public SoundEffectPlayer PlaySoundMono(string soundKey)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundKey` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### ReleaseFog()

```csharp
public void ReleaseFog()
```
#INC


### ResetAnimatorTransform()

```csharp
public void ResetAnimatorTransform()
```
#INC


### SetRoomFog(float)

```csharp
public void SetRoomFog(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetRoomFog(float, float)

```csharp
public void SetRoomFog(float alpha, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |
| `time` | `System.Single` |  |

### SetScaleFactor(float, float, float)

```csharp
public void SetScaleFactor(float x, float y, float z)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |
| `z` | `System.Single` |  |

### SetSliderColor(SliderColorSet)

```csharp
public void SetSliderColor(CreatureUnit.SliderColorSet set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `Global.CreatureUnit.SliderColorSet` |  |

### SpecialSkill()

```csharp
public void SpecialSkill()
```
#INC


### Start()

```csharp
public virtual void Start()
```
#INC


### TempUpdateViewPos()

```csharp
public void TempUpdateViewPos()
```
#INC


### Update()

```csharp
public virtual void Update()
```
#INC


### UpdateDirection()

```csharp
protected virtual void UpdateDirection()
```
#INC


### UpdateScale()

```csharp
protected virtual void UpdateScale()
```
#INC


### UpdateViewPosition()

```csharp
protected virtual void UpdateViewPosition()
```
#INC

