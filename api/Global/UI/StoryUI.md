---
uid: Global.StoryUI
canonical_path: /api/Global/UI/StoryUI
---

# Class StoryUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryUI : MonoBehaviour
```

Main UI for displaying everything during stories.

In charge of playing back the commands.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → StoryUI

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryUI()

```csharp
public StoryUI()
```

## Fields

### _bInit

```csharp
private bool _bInit
```
#INC


#### Field Value

**Type:** System.Boolean

### _characters

```csharp
private Dictionary<string, StoryUI.CharacterVar> _characters
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,StoryUI.CharacterVar}

### _cmdStack

```csharp
private Stack<StoryScriptCommandData> _cmdStack
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Stack{StoryScriptCommandData}

### _commandTable

```csharp
private Dictionary<Type, StoryUI.CommandFunc> _commandTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Type,StoryUI.CommandFunc}

### _curCmd

```csharp
private StoryScriptCommandData _curCmd
```
#INC


#### Field Value

**Type:** Global.StoryScriptCommandData

### _currentCameraFilter

```csharp
private MonoBehaviour _currentCameraFilter
```
#INC


#### Field Value

**Type:** UnityEngine.MonoBehaviour

### _currentCameraFilterTable

```csharp
private Dictionary<StoryScriptCameraFilter, MonoBehaviour> _currentCameraFilterTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{StoryScriptCameraFilter,UnityEngine.MonoBehaviour}

### _currentUICameraFilter

```csharp
private MonoBehaviour _currentUICameraFilter
```
#INC


#### Field Value

**Type:** UnityEngine.MonoBehaviour

### _currentUICameraFilterTable

```csharp
private Dictionary<StoryScriptCameraFilter, MonoBehaviour> _currentUICameraFilterTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{StoryScriptCameraFilter,UnityEngine.MonoBehaviour}

### _filterAddTable

```csharp
private Dictionary<StoryScriptCameraFilter, StoryUI.AddFilterFunc> _filterAddTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{StoryScriptCameraFilter,StoryUI.AddFilterFunc}

### _filterTable

```csharp
private Dictionary<StoryScriptCameraFilter, StoryUI.CallbackFunc> _filterTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{StoryScriptCameraFilter,StoryUI.CallbackFunc}

### _isPlayingVideo

```csharp
private bool _isPlayingVideo
```
#INC


#### Field Value

**Type:** System.Boolean

### _skipping

```csharp
private bool _skipping
```
#INC


#### Field Value

**Type:** System.Boolean

### _speakLogs

```csharp
private List<StoryUI.SpeakLog> _speakLogs
```

#### Field Value

**Type:** System.Collections.Generic.List{StoryUI.SpeakLog}

### _storyEndCallback

```csharp
private StoryUI.StoryEndFunc _storyEndCallback
```

#### Field Value

**Type:** Global.StoryUI.StoryEndFunc

### _uiActive

```csharp
private bool _uiActive
```
#INC


#### Field Value

**Type:** System.Boolean

### _waitTimer

```csharp
private float _waitTimer
```
#INC


#### Field Value

**Type:** System.Single

### backgroundEffecter

```csharp
public StoryCGFadeEffecter backgroundEffecter
```
#INC


#### Field Value

**Type:** Global.StoryCGFadeEffecter

### CGCanvas

```csharp
public StoryCGCanvas CGCanvas
```
#INC


#### Field Value

**Type:** Global.StoryCGCanvas

### dayCount

```csharp
public Text dayCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### dayUIRoot

```csharp
public GameObject dayUIRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### dialogueUI

```csharp
public StoryDialogueUI dialogueUI
```
#INC


#### Field Value

**Type:** Global.StoryDialogueUI

### endingCanvas

```csharp
public PostEndingCanvas endingCanvas
```
#INC


#### Field Value

**Type:** Global.PostEndingCanvas

### frontCGEffecter

```csharp
public StoryCGFadeEffecter frontCGEffecter
```
#INC


#### Field Value

**Type:** Global.StoryCGFadeEffecter

### optionUI

```csharp
public StoryOptionUI optionUI
```
#INC


#### Field Value

**Type:** Global.StoryOptionUI

### sefiraInfoUI

```csharp
public StorySefiraInfoUI sefiraInfoUI
```
#INC


#### Field Value

**Type:** Global.StorySefiraInfoUI

### selectionUI

```csharp
public StorySelectionUI selectionUI
```
#INC


#### Field Value

**Type:** Global.StorySelectionUI

### settingWindow

```csharp
public SettingWindow settingWindow
```
#INC


#### Field Value

**Type:** Global.SettingWindow

### speakLogUI

```csharp
public StorySpeakLogUI speakLogUI
```
#INC


#### Field Value

**Type:** Global.StorySpeakLogUI

### standingCGRootUI

```csharp
public StoryStandingCGRootUI standingCGRootUI
```
#INC


#### Field Value

**Type:** Global.StoryStandingCGRootUI

### storyCanvas

```csharp
public Canvas storyCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### storyClick

```csharp
public AudioClipPlayer storyClick
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### StoryClick

```csharp
private string StoryClick
```
#INC


#### Field Value

**Type:** System.String

## Properties

### initialized

```csharp
public bool initialized { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Add_3d_computer(StoryFilterParameter)

```csharp
private void Add_3d_computer(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Atmosphere_Rain(StoryFilterParameter)

```csharp
private void Add_Atmosphere_Rain(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_atmosphere_rain_pro(StoryFilterParameter)

```csharp
private void Add_atmosphere_rain_pro(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Blizzard(StoryFilterParameter)

```csharp
private void Add_Blizzard(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Blur_Blurry(StoryFilterParameter)

```csharp
private void Add_Blur_Blurry(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Blur_Focus(StoryFilterParameter)

```csharp
private void Add_Blur_Focus(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Broken_Screen(StoryFilterParameter)

```csharp
private void Add_Broken_Screen(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Dream(StoryFilterParameter)

```csharp
private void Add_Distortion_Dream(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Dream2(StoryFilterParameter)

```csharp
private void Add_Distortion_Dream2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Flag(StoryFilterParameter)

```csharp
private void Add_Distortion_Flag(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Heat(StoryFilterParameter)

```csharp
private void Add_Distortion_Heat(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Noise(StoryFilterParameter)

```csharp
private void Add_Distortion_Noise(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Distortion_Shockwave(StoryFilterParameter)

```csharp
private void Add_Distortion_Shockwave(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_distortion_water_drop(StoryFilterParameter)

```csharp
private void Add_distortion_water_drop(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_earthquake(StoryFilterParameter)

```csharp
private void Add_earthquake(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_earthquake2(StoryFilterParameter)

```csharp
private void Add_earthquake2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_AAA_super_computer(StoryFilterParameter)

```csharp
private void Add_Filter_AAA_super_computer(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_AAA_super_hexagon(StoryFilterParameter)

```csharp
private void Add_Filter_AAA_super_hexagon(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_AAA_water_drop(StoryFilterParameter)

```csharp
private void Add_Filter_AAA_water_drop(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Blood(StoryFilterParameter)

```csharp
private void Add_Filter_Blood(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Blood_Hit(StoryFilterParameter)

```csharp
private void Add_Filter_Blood_Hit(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Blur_bloom(StoryFilterParameter)

```csharp
private void Add_Filter_Blur_bloom(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Blur_tilt_shift(StoryFilterParameter)

```csharp
private void Add_Filter_Blur_tilt_shift(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Color_sepia(StoryFilterParameter)

```csharp
private void Add_Filter_Color_sepia(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Grayscale(StoryFilterParameter)

```csharp
private void Add_Filter_Grayscale(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_TV_distort(StoryFilterParameter)

```csharp
private void Add_Filter_TV_distort(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_TV_distort_fade(StoryFilterParameter)

```csharp
private void Add_Filter_TV_distort_fade(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_TV_oldMovie_2(StoryFilterParameter)

```csharp
private void Add_Filter_TV_oldMovie_2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_TV_tiles(StoryFilterParameter)

```csharp
private void Add_Filter_TV_tiles(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Filter_Vision_Rainbow(StoryFilterParameter)

```csharp
private void Add_Filter_Vision_Rainbow(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fire_Gradient(StoryFilterParameter)

```csharp
private void Add_Fire_Gradient(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fx_Drunk(StoryFilterParameter)

```csharp
private void Add_Fx_Drunk(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fx_Drunk2(StoryFilterParameter)

```csharp
private void Add_Fx_Drunk2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fx_Drunk3(StoryFilterParameter)

```csharp
private void Add_Fx_Drunk3(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fx_Drunk4(StoryFilterParameter)

```csharp
private void Add_Fx_Drunk4(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Fx_Glitch3(StoryFilterParameter)

```csharp
private void Add_Fx_Glitch3(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Glitch_Mozaic(StoryFilterParameter)

```csharp
private void Add_Glitch_Mozaic(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Light_Water(StoryFilterParameter)

```csharp
private void Add_Light_Water(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_matrix(StoryFilterParameter)

```csharp
private void Add_matrix(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_nightvision3(StoryFilterParameter)

```csharp
private void Add_nightvision3(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_noise_tv1(StoryFilterParameter)

```csharp
private void Add_noise_tv1(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_noise_tv2(StoryFilterParameter)

```csharp
private void Add_noise_tv2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_noise_tv3(StoryFilterParameter)

```csharp
private void Add_noise_tv3(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Noise_Tv_2(StoryFilterParameter)

```csharp
private void Add_Noise_Tv_2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_super_computer1(StoryFilterParameter)

```csharp
private void Add_super_computer1(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_tv_arcade2(StoryFilterParameter)

```csharp
private void Add_tv_arcade2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_tv_artefact1(StoryFilterParameter)

```csharp
private void Add_tv_artefact1(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_tv_artefact2(StoryFilterParameter)

```csharp
private void Add_tv_artefact2(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Tv_Broken_Glass(StoryFilterParameter)

```csharp
private void Add_Tv_Broken_Glass(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Tv_Compression(StoryFilterParameter)

```csharp
private void Add_Tv_Compression(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Tv_Noise(StoryFilterParameter)

```csharp
private void Add_Tv_Noise(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Tv_Rewind(StoryFilterParameter)

```csharp
private void Add_Tv_Rewind(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Tv_Vhs(StoryFilterParameter)

```csharp
private void Add_Tv_Vhs(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_TV_Vignetting(StoryFilterParameter)

```csharp
private void Add_TV_Vignetting(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Add_Wing(StoryFilterParameter)

```csharp
private void Add_Wing(StoryFilterParameter param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |

### Clear()

```csharp
public void Clear()
```
#INC


### ClearCharacter()

```csharp
public void ClearCharacter()
```
#INC


### Command_add_filter(StoryScriptCommandEventEnum)

```csharp
private bool Command_add_filter(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_background(StoryScriptCommandEventEnum)

```csharp
private bool Command_background(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_bgm(StoryScriptCommandEventEnum)

```csharp
private bool Command_bgm(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_call(StoryScriptCommandEventEnum)

```csharp
private bool Command_call(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_camera_filter(StoryScriptCommandEventEnum)

```csharp
private bool Command_camera_filter(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_cg(StoryScriptCommandEventEnum)

```csharp
private bool Command_cg(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_character(StoryScriptCommandEventEnum)

```csharp
private bool Command_character(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_dialogue_box(StoryScriptCommandEventEnum)

```csharp
private bool Command_dialogue_box(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_disappear(StoryScriptCommandEventEnum)

```csharp
private bool Command_disappear(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_ending(StoryScriptCommandEventEnum)

```csharp
private bool Command_ending(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_hide_exdiag(StoryScriptCommandEventEnum)

```csharp
private bool Command_hide_exdiag(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_hide_option(StoryScriptCommandEventEnum)

```csharp
private bool Command_hide_option(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_hide_ui(StoryScriptCommandEventEnum)

```csharp
private bool Command_hide_ui(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_if(StoryScriptCommandEventEnum)

```csharp
private bool Command_if(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_list(StoryScriptCommandEventEnum)

```csharp
private bool Command_list(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_move_background(StoryScriptCommandEventEnum)

```csharp
private bool Command_move_background(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_move_cg(StoryScriptCommandEventEnum)

```csharp
private bool Command_move_cg(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_position(StoryScriptCommandEventEnum)

```csharp
private bool Command_position(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_remove_cg(StoryScriptCommandEventEnum)

```csharp
private bool Command_remove_cg(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_remove_filter(StoryScriptCommandEventEnum)

```csharp
private bool Command_remove_filter(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_return_title(StoryScriptCommandEventEnum)

```csharp
private bool Command_return_title(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_select(StoryScriptCommandEventEnum)

```csharp
private bool Command_select(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_set_anim(StoryScriptCommandEventEnum)

```csharp
private bool Command_set_anim(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_show_exdiag(StoryScriptCommandEventEnum)

```csharp
private bool Command_show_exdiag(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_show_ui(StoryScriptCommandEventEnum)

```csharp
private bool Command_show_ui(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_sound(StoryScriptCommandEventEnum)

```csharp
private bool Command_sound(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_speak(StoryScriptCommandEventEnum)

```csharp
private bool Command_speak(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_var_set(StoryScriptCommandEventEnum)

```csharp
private bool Command_var_set(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_var_set_random(StoryScriptCommandEventEnum)

```csharp
private bool Command_var_set_random(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### Command_wait(StoryScriptCommandEventEnum)

```csharp
private bool Command_wait(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns

**Type:** System.Boolean

### End()

```csharp
public void End()
```
#INC


### Filter_Color_sepia()

```csharp
private void Filter_Color_sepia()
```
#INC


### Filter_Grayscale()

```csharp
private void Filter_Grayscale()
```
#INC


### Filter_none()

```csharp
private void Filter_none()
```
#INC


### Filter_TV_distort()

```csharp
private void Filter_TV_distort()
```
#INC


### Filter_TV_tiles()

```csharp
private void Filter_TV_tiles()
```
#INC


### FixedUpdate()

```csharp
private void FixedUpdate()
```
#INC


### GetConstantValue(StoryScriptValue)

```csharp
private int GetConstantValue(StoryScriptValue v)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `Global.StoryScriptValue` |  |

#### Returns

**Type:** System.Int32

### HideOption()

```csharp
private void HideOption()
```
#INC


### HideUI()

```csharp
private void HideUI()
```
#INC


### Init()

```csharp
public void Init()
```
#INC
#code-generated


### InitCommandTable()

```csharp
private void InitCommandTable()
```
#INC


### InitFilterTable()

```csharp
private void InitFilterTable()
```
#INC


### IsSkipping()

```csharp
private bool IsSkipping()
```
#INC


#### Returns

**Type:** System.Boolean

### LoadNextLine()

```csharp
public void LoadNextLine()
```
#INC


### LoadStory(params string[])

```csharp
public void LoadStory(params string[] ids)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.String[]` |  |

### OnClickDialogue()

```csharp
public void OnClickDialogue()
```
#INC


### OnClickLogClose()

```csharp
public void OnClickLogClose()
```
#INC


### OnClickLogOpen()

```csharp
public void OnClickLogOpen()
```
#INC


### OnClickSkip()

```csharp
public void OnClickSkip()
```
#INC


### OnSelectSelection(int)

```csharp
public void OnSelectSelection(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### ProcessCommandEvent(StoryScriptCommandEventEnum)

```csharp
public void ProcessCommandEvent(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

### ProcessDialogue()

```csharp
public void ProcessDialogue()
```
#INC


### PushCommandList(List<StoryScriptCommandData>)

```csharp
private void PushCommandList(List<StoryScriptCommandData> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{StoryScriptCommandData}` |  |

### SetEndCallback(StoryEndFunc)

```csharp
public void SetEndCallback(StoryUI.StoryEndFunc callback)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `callback` | `Global.StoryUI.StoryEndFunc` |  |

### ShowUI()

```csharp
private void ShowUI()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

