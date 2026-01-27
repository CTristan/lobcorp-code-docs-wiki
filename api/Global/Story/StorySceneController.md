---
uid: Global.StorySceneController
canonical_path: /api/Global/Story/StorySceneController
---

# Class StorySceneController

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StorySceneController : MonoBehaviour
```

Main controller for playing stories #verify .

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → StorySceneController

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StorySceneController()

```csharp
public StorySceneController()
```

## Fields

### _clearedMissions

```csharp
private List<Mission> _clearedMissions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Mission}

### _curState

```csharp
private StorySceneController.StorySceneState _curState
```

#### Field Value

**Type:** Global.StorySceneController.StorySceneState

### _finaleSefira

```csharp
private SefiraEnum _finaleSefira
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### _firstBossMission

```csharp
private bool _firstBossMission
```
#INC


#### Field Value

**Type:** System.Boolean

### _instance

```csharp
private static StorySceneController _instance
```
#INC


#### Field Value

**Type:** Global.StorySceneController

### _isOpenedArea

```csharp
private bool _isOpenedArea
```
#INC


#### Field Value

**Type:** System.Boolean

### _missionSceneQueue

```csharp
private Queue<StorySceneController.SubStorySceneData> _missionSceneQueue
```

#### Field Value

**Type:** System.Collections.Generic.Queue{StorySceneController.SubStorySceneData}

### _newMission

```csharp
private Mission _newMission
```
#INC


#### Field Value

**Type:** Global.Mission

### _nextMissions

```csharp
private List<Mission> _nextMissions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Mission}

### _sefiraOrder

```csharp
private SefiraEnum[] _sefiraOrder
```
#INC


#### Field Value

**Type:** Global.SefiraEnum[]

### _sefiraOrderQueue

```csharp
private Queue<SefiraEnum> _sefiraOrderQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{SefiraEnum}

### bossAppearUI

```csharp
public BossMissionAppearUI bossAppearUI
```
#INC


#### Field Value

**Type:** Global.BossMissionAppearUI

### challangeModeUI

```csharp
public StoryChallengeModeUI challangeModeUI
```
#INC


#### Field Value

**Type:** Global.StoryChallengeModeUI

### fadeUI

```csharp
public StoryFadeUI fadeUI
```
#INC


#### Field Value

**Type:** Global.StoryFadeUI

### missionShader

```csharp
public GameObject missionShader
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### seedUI

```csharp
public StorySeedUI seedUI
```
#INC


#### Field Value

**Type:** Global.StorySeedUI

### storyUI

```csharp
public StoryUI storyUI
```
#INC


#### Field Value

**Type:** Global.StoryUI

## Properties

### instance

```csharp
public static StorySceneController instance { get; }
```

#### Property Value

**Type:** Global.StorySceneController

## Methods

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### ExistsSefiraMemory()

```csharp
private bool ExistsSefiraMemory()
```
#INC


#### Returns

**Type:** System.Boolean

### InitStory()

```csharp
public void InitStory()
```
#INC


### LoadMainScene()

```csharp
private void LoadMainScene()
```
#INC


### LoadStory(string)

```csharp
private void LoadStory(string storyId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `storyId` | `System.String` |  |

### LoadStoryWithFade(string)

```csharp
private void LoadStoryWithFade(string storyId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `storyId` | `System.String` |  |

### OnEndSeedUI(string)

```csharp
public void OnEndSeedUI(string angelaStory)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angelaStory` | `System.String` |  |

### OnEndStory()

```csharp
public void OnEndStory()
```
#INC


### PrintQueue(Queue<SefiraEnum>)

```csharp
private void PrintQueue(Queue<SefiraEnum> q)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `q` | `System.Collections.Generic.Queue{SefiraEnum}` |  |

### SetStoryKether(int)

```csharp
private void SetStoryKether(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

### Start()

```csharp
private void Start()
```
#INC


### TryPlayNextSubStory()

```csharp
private void TryPlayNextSubStory()
```
#INC

