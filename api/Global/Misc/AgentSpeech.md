---
uid: Global.AgentSpeech
canonical_path: /api/Global/Misc/AgentSpeech
---

# Class AgentSpeech

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentSpeech : MonoBehaviour
```
Represents a yapping text object for an [agent](/api/Global/Worker/AgentUnit).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentSpeech

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentSpeech()

```csharp
public AgentSpeech()
```

## Fields

### _action

```csharp
private AgentLyrics.CreatureAction _action
```
#INC


#### Field Value

**Type:** Global.AgentLyrics.CreatureAction

### _activated

```csharp
private bool _activated
```
#INC


#### Field Value

**Type:** System.Boolean

### _current

```csharp
private AgentLyrics.LyricList_old _current
```
#INC


#### Field Value

**Type:** Global.AgentLyrics.LyricList_old

### _currentAgentLyric

```csharp
private LyricTypeNew _currentAgentLyric
```
#INC


#### Field Value

**Type:** Global.LyricTypeNew

### _currentPriority

```csharp
private int _currentPriority
```
#INC


#### Field Value

**Type:** System.Int32

### _reaction

```csharp
private AgentLyrics.CreatureReaction _reaction
```
#INC


#### Field Value

**Type:** Global.AgentLyrics.CreatureReaction

### actionKey

```csharp
private string actionKey
```
#INC


#### Field Value

**Type:** System.String

### bgRectTransform

```csharp
private RectTransform bgRectTransform
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### BgSprite

```csharp
public Sprite[] BgSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### boxColors

```csharp
public Color[] boxColors
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### copy

```csharp
private string copy
```
#INC


#### Field Value

**Type:** System.String

### currentSizedelta

```csharp
private Vector2 currentSizedelta
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### dead

```csharp
private bool dead
```
#INC


#### Field Value

**Type:** System.Boolean

### elapsed

```csharp
private float elapsed
```
#INC


#### Field Value

**Type:** System.Single

### forcely

```csharp
private bool forcely
```
#INC


#### Field Value

**Type:** System.Boolean

### initialFontSize

```csharp
private int initialFontSize
```
#INC


#### Field Value

**Type:** System.Int32

### interrupt

```csharp
private bool interrupt
```
#INC


#### Field Value

**Type:** System.Boolean

### interruptElapsed

```csharp
private float interruptElapsed
```
#INC


#### Field Value

**Type:** System.Single

### interruptWait

```csharp
private float interruptWait
```
#INC


#### Field Value

**Type:** System.Single

### isEnabled

```csharp
private bool isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### maxX

```csharp
public float maxX
```
#INC


#### Field Value

**Type:** System.Single

### renderingTarget

```csharp
private Sprite renderingTarget
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### sizeY

```csharp
private float sizeY
```
#INC


#### Field Value

**Type:** System.Single

### smallSizeDelta

```csharp
private Vector2 smallSizeDelta
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### spacingX

```csharp
public float spacingX
```
#INC


#### Field Value

**Type:** System.Single

### spacingY

```csharp
public float spacingY
```
#INC


#### Field Value

**Type:** System.Single

### standard

```csharp
private TextAnchor standard
```
#INC


#### Field Value

**Type:** UnityEngine.TextAnchor

### targetModel

```csharp
private WorkerModel targetModel
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### textBackground

```csharp
public Image textBackground
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### textBox

```csharp
public Image textBox
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### textColors

```csharp
public Color[] textColors
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### textItem

```csharp
public Text textItem
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### textObject

```csharp
public RectTransform textObject
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### textRectTransform

```csharp
private RectTransform textRectTransform
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### waitTime

```csharp
private float waitTime
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### action

```csharp
public AgentLyrics.CreatureAction action { get; set; }
```

#### Property Value

**Type:** Global.AgentLyrics.CreatureAction

### Actviated

```csharp
public bool Actviated { set; }
```

#### Property Value

**Type:** System.Boolean

### current

```csharp
public AgentLyrics.LyricList_old current { get; set; }
```

#### Property Value

**Type:** Global.AgentLyrics.LyricList_old

### reaction

```csharp
public AgentLyrics.CreatureReaction reaction { get; set; }
```

#### Property Value

**Type:** Global.AgentLyrics.CreatureReaction

## Methods

### DisableText()

```csharp
public void DisableText()
```
#INC


### FixedUpdate()

```csharp
public void FixedUpdate()
```
#INC


### ForcelyShutUp()

```csharp
public void ForcelyShutUp()
```
#INC


### Init(WorkerModel)

```csharp
public void Init(WorkerModel wm)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `wm` | `Global.WorkerModel` |  |

### InterruptEnable()

```csharp
public void InterruptEnable()
```
#INC


### InterruptStop()

```csharp
public void InterruptStop()
```
#INC


### InterruptStop(float)

```csharp
public void InterruptStop(float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### OnSetCreatureAction()

```csharp
public void OnSetCreatureAction()
```
#INC


### OnSetCreatureReaction()

```csharp
public void OnSetCreatureReaction()
```
#INC


### OnSetText()

```csharp
public void OnSetText()
```
#INC


### SetForceley()

```csharp
public void SetForceley()
```
#INC


### SetSpeech(string)

```csharp
private void SetSpeech(string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### ShowAgentLyric(LyricTypeNew, string, int)

```csharp
public void ShowAgentLyric(LyricTypeNew type, string text, int priority)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricTypeNew` |  |
| `text` | `System.String` |  |
| `priority` | `System.Int32` |  |

### ShowCreatureActionLyric(CreatureAction, string)

```csharp
public void ShowCreatureActionLyric(AgentLyrics.CreatureAction creatureAction, string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureAction` | `Global.AgentLyrics.CreatureAction` |  |
| `key` | `System.String` |  |

### ShowCreatureReactionLyric(CreatureReaction)

```csharp
public void ShowCreatureReactionLyric(AgentLyrics.CreatureReaction creatureReaction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureReaction` | `Global.AgentLyrics.CreatureReaction` |  |

### showSpeech(string)

```csharp
private void showSpeech(string speech)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speech` | `System.String` |  |

### ShowSpeech_old(LyricList_old)

```csharp
public void ShowSpeech_old(AgentLyrics.LyricList_old lyric)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lyric` | `Global.AgentLyrics.LyricList_old` |  |

### Start()

```csharp
public void Start()
```
#INC
#code-generated

