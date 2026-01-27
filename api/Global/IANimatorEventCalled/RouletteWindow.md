---
uid: Global.RouletteWindow
canonical_path: /api/Global/IANimatorEventCalled/RouletteWindow
---

# Class RouletteWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RouletteWindow : MonoBehaviour, IAnimatorEventCalled
```

The roulette that appears during [Censored](/api/Global/Misc/Censored)'s special work type and [Nameless Fetus](/api/Global/Misc/NamelessFetus)' meltdown.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RouletteWindow

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RouletteWindow()

```csharp
public RouletteWindow()
```

## Fields

### _currentCaller

```csharp
private IRouletteWindowMessage _currentCaller
```
#INC


#### Field Value

**Type:** Global.IRouletteWindowMessage

### _currentWindow

```csharp
private static RouletteWindow _currentWindow
```
#INC


#### Field Value

**Type:** Global.RouletteWindow

### _looping

```csharp
private float _looping
```
#INC


#### Field Value

**Type:** System.Single

### anchorMax

```csharp
public float anchorMax
```
#INC


#### Field Value

**Type:** System.Single

### anim

```csharp
public Animator anim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### audioSrc

```csharp
public AudioSource audioSrc
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### autoClose

```csharp
public bool autoClose
```
#INC


#### Field Value

**Type:** System.Boolean

### CameraPos

```csharp
[HideInInspector]
public Vector3 CameraPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### CancelButton

```csharp
public Button CancelButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### closeSound

```csharp
public AudioClip closeSound
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### ConfirmButton

```csharp
public Button ConfirmButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### copied

```csharp
private GameObject copied
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### copiedList

```csharp
private List<RouletteItem> copiedList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RouletteItem}

### current

```csharp
private RectTransform current
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### currentIndexDisplay_Debug

```csharp
public Text currentIndexDisplay_Debug
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### currentTarget

```csharp
public CreatureModel currentTarget
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### endTime

```csharp
public float endTime
```
#INC


#### Field Value

**Type:** System.Single

### endTimer

```csharp
private UnscaledTimer endTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### filterNormal

```csharp
public Sprite filterNormal
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### filterRenderer

```csharp
public Image filterRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### filterTransTime

```csharp
public float filterTransTime
```
#INC


#### Field Value

**Type:** System.Single

### filterTransTimer

```csharp
private UnscaledTimer filterTransTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### filterWorkerSelected

```csharp
public Sprite filterWorkerSelected
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### findingSpeed

```csharp
public Vector2 findingSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### findingTime

```csharp
public float findingTime
```
#INC


#### Field Value

**Type:** System.Single

### integrate

```csharp
public GameObject integrate
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### isFinding

```csharp
private bool isFinding
```
#INC


#### Field Value

**Type:** System.Boolean

### isOrigin

```csharp
private bool isOrigin
```
#INC


#### Field Value

**Type:** System.Boolean

### isRunning

```csharp
private bool isRunning
```
#INC


#### Field Value

**Type:** System.Boolean

### isTransBright

```csharp
private bool isTransBright
```
#INC


#### Field Value

**Type:** System.Boolean

### list

```csharp
private List<RouletteItem> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RouletteItem}

### loopRange

```csharp
public Vector2 loopRange
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### loopSpeedRange

```csharp
[Space(5)]
public Vector2 loopSpeedRange
```

#### Field Value

**Type:** UnityEngine.Vector2

### loopTimer

```csharp
private UnscaledTimer loopTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### moveElap

```csharp
private float moveElap
```
#INC


#### Field Value

**Type:** System.Single

### moveTarget

```csharp
private float moveTarget
```
#INC


#### Field Value

**Type:** System.Single

### OnInvalidPanel

```csharp
public GameObject OnInvalidPanel
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### openSound

```csharp
public AudioClip openSound
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### panel

```csharp
public RectTransform panel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### posy

```csharp
private float posy
```
#INC


#### Field Value

**Type:** System.Single

### prewarm

```csharp
[Space(5)]
public float prewarm
```

#### Field Value

**Type:** System.Single

### prewarmTimer

```csharp
private UnscaledTimer prewarmTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### raycastObject

```csharp
public GameObject raycastObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### rouletteMaskHeight

```csharp
public float rouletteMaskHeight
```
#INC


#### Field Value

**Type:** System.Single

### scrollArea

```csharp
public ScrollRect scrollArea
```
#INC


#### Field Value

**Type:** UnityEngine.UI.ScrollRect

### selectedEvent

```csharp
private RouletteWindow.OnSelectedEvent selectedEvent
```

#### Field Value

**Type:** Global.RouletteWindow.OnSelectedEvent

### selectSound

```csharp
public AudioClip selectSound
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### shooted

```csharp
private bool shooted
```
#INC


#### Field Value

**Type:** System.Boolean

### spare

```csharp
private RectTransform spare
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### speedFactor

```csharp
public float speedFactor
```
#INC


#### Field Value

**Type:** System.Single

### startedRun

```csharp
private bool startedRun
```
#INC


#### Field Value

**Type:** System.Boolean

### stopTime

```csharp
[Space(10)]
public Vector2 stopTime
```

#### Field Value

**Type:** UnityEngine.Vector2

### targetIndex

```csharp
private int targetIndex
```
#INC


#### Field Value

**Type:** System.Int32

### textItem

```csharp
public GameObject textItem
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### tickFreqDef

```csharp
public float tickFreqDef
```
#INC


#### Field Value

**Type:** System.Single

### tickFreqMin

```csharp
public float tickFreqMin
```
#INC


#### Field Value

**Type:** System.Single

### tickSound

```csharp
public AudioClip tickSound
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### tickSoundFreqScaler

```csharp
public float tickSoundFreqScaler
```
#INC


#### Field Value

**Type:** System.Single

### tickSoundTimer

```csharp
private UnscaledTimer tickSoundTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### title

```csharp
public Text title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### unitRectHeight

```csharp
[Space(5)]
public float unitRectHeight
```

#### Field Value

**Type:** System.Single

### workerlist

```csharp
private List<WorkerModel> workerlist
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

## Properties

### currentCaller

```csharp
private IRouletteWindowMessage currentCaller { get; set; }
```

#### Property Value

**Type:** Global.IRouletteWindowMessage

### currentWindow

```csharp
public static RouletteWindow currentWindow { get; }
```

#### Property Value

**Type:** Global.RouletteWindow

### looping

```csharp
private float looping { get; }
```

#### Property Value

**Type:** System.Single

### loopSpeed

```csharp
public float loopSpeed { get; }
```

#### Property Value

**Type:** System.Single

### maxIndex

```csharp
private int maxIndex { get; }
```

#### Property Value

**Type:** System.Int32

### speed

```csharp
private float speed { get; }
```

#### Property Value

**Type:** System.Single

### tickSoundFreq

```csharp
private float tickSoundFreq { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AgentReset()

```csharp
public void AgentReset()
```
#INC


### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```
#INC


### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```
#INC


### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### CallerSet(IRouletteWindowMessage)

```csharp
public void CallerSet(IRouletteWindowMessage caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.IRouletteWindowMessage` |  |

### CheckProcess()

```csharp
private void CheckProcess()
```
#INC


### CheckRaycast()

```csharp
private void CheckRaycast()
```
#INC


### CheckValidate()

```csharp
private bool CheckValidate()
```
#INC


#### Returns

**Type:** System.Boolean

### CopyForRun()

```csharp
private void CopyForRun()
```
#INC


### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### FindTarget()

```csharp
private void FindTarget()
```
#INC


### InitList()

```csharp
private void InitList()
```
#INC


### MoveToFind()

```csharp
private void MoveToFind()
```
#INC


### OnCalled()

```csharp
public void OnCalled()
```
#INC


### OnCalled(int)

```csharp
public void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickCancel()

```csharp
public void OnClickCancel()
```
#INC


### OnClickConfirm()

```csharp
public void OnClickConfirm()
```
#INC


### OnClose()

```csharp
public void OnClose()
```
#INC


### OnFilterDefault()

```csharp
public void OnFilterDefault()
```
#INC


### OnFilterSelected()

```csharp
public void OnFilterSelected()
```
#INC


### OnInvalid()

```csharp
private void OnInvalid()
```
#INC


### OnOpenWindowPrev()

```csharp
private void OnOpenWindowPrev()
```
#INC


### OnRunningEnd()

```csharp
private void OnRunningEnd()
```
#INC


### OnSelectedItemEffectEnd(RouletteItem)

```csharp
public void OnSelectedItemEffectEnd(RouletteItem item)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `Global.RouletteItem` |  |

### OnStageStart()

```csharp
private void OnStageStart()
```
#INC


### OpenWindowGlobal(CreatureModel, OnSelectedEvent)

```csharp
public void OpenWindowGlobal(CreatureModel creature, RouletteWindow.OnSelectedEvent del)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `del` | `Global.RouletteWindow.OnSelectedEvent` |  |

### OpenWindowLocal(CreatureModel, Sefira, OnSelectedEvent)

```csharp
public void OpenWindowLocal(CreatureModel creature, Sefira range, RouletteWindow.OnSelectedEvent del)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `range` | `Global.Sefira` |  |
| `del` | `Global.RouletteWindow.OnSelectedEvent` |  |

### PlaySelectSound()

```csharp
public void PlaySelectSound()
```
#INC


### RunPanel()

```csharp
private void RunPanel()
```
#INC


### SetFilterAlpha(float)

```csharp
public void SetFilterAlpha(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetLooping()

```csharp
private void SetLooping()
```
#INC


### SetTarget()

```csharp
private void SetTarget()
```
#INC


### SimpleReset()

```csharp
public void SimpleReset()
```
#INC


### SoundMake(string)

```csharp
public void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### Update()

```csharp
private void Update()
```
#INC

