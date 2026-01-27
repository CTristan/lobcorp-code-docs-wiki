---
uid: Global.PlaySpeedSettingUI
canonical_path: /api/Global/UI/PlaySpeedSettingUI
---

# Class PlaySpeedSettingUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlaySpeedSettingUI : MonoBehaviour
```

Controls changing the speed during management.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → PlaySpeedSettingUI

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PlaySpeedSettingUI()

```csharp
public PlaySpeedSettingUI()
```

## Fields

### _available

```csharp
private bool _available
```
#INC


#### Field Value

**Type:** System.Boolean

### _instance

```csharp
private static PlaySpeedSettingUI _instance
```
#INC


#### Field Value

**Type:** Global.PlaySpeedSettingUI

### blockedCaller

```csharp
private List<CreatureBase> blockedCaller
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureBase}

### blockedDictionary

```csharp
private Dictionary<PlaySpeedSettingBlockType, PlaySpeedSettingBlockedUI> blockedDictionary
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{PlaySpeedSettingBlockType,GameStatusUI.PlaySpeedSettingBlockedUI}

### blockedImage

```csharp
public Image blockedImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### BlockedUIParent

```csharp
[Header("UI Blocked")]
public Transform BlockedUIParent
```

#### Field Value

**Type:** UnityEngine.Transform

### blockEvent

```csharp
private PlaySpeedSettingUI.BlockedUIEvent blockEvent
```

#### Field Value

**Type:** Global.PlaySpeedSettingUI.BlockedUIEvent

### NormalSpeed

```csharp
public Button NormalSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### observeFilter

```csharp
public Image observeFilter
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### observeSprite

```csharp
public Sprite observeSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### OneHalfSpeed

```csharp
public Button OneHalfSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### PauseButton

```csharp
public Button PauseButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### pauseDefSprite

```csharp
public Sprite pauseDefSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### pauseFilter

```csharp
public Image pauseFilter
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### pauseImage

```csharp
public Image pauseImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### spaceCalled

```csharp
private List<PlaySpeedSettingUI.SpaceEvent> spaceCalled
```

#### Field Value

**Type:** System.Collections.Generic.List{PlaySpeedSettingUI.SpaceEvent}

### speed1Image

```csharp
public Image speed1Image
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### speed2Image

```csharp
public Image speed2Image
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### speed3Image

```csharp
public Image speed3Image
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### speedBlockMask

```csharp
public Image speedBlockMask
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### timeMultiplierEnabled

```csharp
private bool timeMultiplierEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### TwiceSpeed

```csharp
public Button TwiceSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

## Properties

### available

```csharp
public bool available { get; }
```

#### Property Value

**Type:** System.Boolean

### CanUseTimeMultiplier

```csharp
private bool CanUseTimeMultiplier { get; }
```

#### Property Value

**Type:** System.Boolean

### instance

```csharp
public static PlaySpeedSettingUI instance { get; }
```

#### Property Value

**Type:** Global.PlaySpeedSettingUI

## Methods

### AddBlockedEvent(PlaySpeedSettingBlockType, PlaySpeedSettingBlockedUI)

```csharp
public void AddBlockedEvent(PlaySpeedSettingBlockType blockType, PlaySpeedSettingBlockedUI script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `blockType` | `Global.PlaySpeedSettingBlockType` |  |
| `script` | `GameStatusUI.PlaySpeedSettingBlockedUI` |  |

### AddSpaceEvent(SpaceEvent)

```csharp
public void AddSpaceEvent(PlaySpeedSettingUI.SpaceEvent newEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newEvent` | `Global.PlaySpeedSettingUI.SpaceEvent` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### BlockImageSetActivate(bool)

```csharp
public void BlockImageSetActivate(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### BlockSetting(CreatureBase)

```csharp
public void BlockSetting(CreatureBase caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.CreatureBase` |  |

### CallBlockEvent(int)

```csharp
public void CallBlockEvent(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### CheckAction(PlaySpeedSettingBlockFunction)

```csharp
private void CheckAction(PlaySpeedSettingBlockFunction function)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

### CheckEscapeBlocked()

```csharp
private bool CheckEscapeBlocked()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckManaulBlocked()

```csharp
private bool CheckManaulBlocked()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckPlaySpeedUI()

```csharp
public bool CheckPlaySpeedUI()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckTimeMultiplierBlocked()

```csharp
private bool CheckTimeMultiplierBlocked()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckTimeStopBlocked(bool)

```csharp
private bool CheckTimeStopBlocked(bool isRelease)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isRelease` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### ClearBlockEvent()

```csharp
public void ClearBlockEvent()
```
#INC


### ForcelyPlay()

```csharp
public void ForcelyPlay()
```
#INC


### ForcleyReleaseSetting()

```csharp
public void ForcleyReleaseSetting()
```
#INC


### OnClickPause()

```csharp
public void OnClickPause()
```
#INC


### OnClickResume()

```csharp
public void OnClickResume()
```
#INC


### OnClickSpeed1()

```csharp
public void OnClickSpeed1()
```
#INC


### OnClickSpeed2()

```csharp
public void OnClickSpeed2()
```
#INC


### OnClickSpeed3()

```csharp
public void OnClickSpeed3()
```
#INC


### OnPause(PAUSECALL)

```csharp
public void OnPause(PAUSECALL caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### OnResume(PAUSECALL)

```csharp
public void OnResume(PAUSECALL caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### ReleaseSetting(CreatureBase)

```csharp
public void ReleaseSetting(CreatureBase caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.CreatureBase` |  |

### RemoveBlockedEvent(PlaySpeedSettingBlockType)

```csharp
public void RemoveBlockedEvent(PlaySpeedSettingBlockType blockType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `blockType` | `Global.PlaySpeedSettingBlockType` |  |

### RemoveSpaceEvent(SpaceEvent)

```csharp
public void RemoveSpaceEvent(PlaySpeedSettingUI.SpaceEvent targetEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetEvent` | `Global.PlaySpeedSettingUI.SpaceEvent` |  |

### SetBlockEvent(BlockedUIEvent)

```csharp
public void SetBlockEvent(PlaySpeedSettingUI.BlockedUIEvent blockEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `blockEvent` | `Global.PlaySpeedSettingUI.BlockedUIEvent` |  |

### SetNormalSpeedForcely()

```csharp
public void SetNormalSpeedForcely()
```
#INC


### SetTimeMultiplierEnable(bool)

```csharp
public void SetTimeMultiplierEnable(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateButton()

```csharp
public void UpdateButton()
```
#INC

