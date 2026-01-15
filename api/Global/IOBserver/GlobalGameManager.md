---
uid: Global.GlobalGameManager
canonical_path: /api/Global/IOBserver/GlobalGameManager
---

# Class GlobalGameManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalGameManager : MonoBehaviour, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → GlobalGameManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GlobalGameManager()

```csharp
public GlobalGameManager()
```

## Fields

### _currentLanguageFont

```csharp
private static GlobalGameManager.LanguageFont _currentLanguageFont
```

#### Field Value

**Type:** Global.GlobalGameManager.LanguageFont

### _instance

```csharp
private static GlobalGameManager _instance
```

#### Field Value

**Type:** Global.GlobalGameManager

### _isPlayingTutorial

```csharp
private bool _isPlayingTutorial
```

#### Field Value

**Type:** System.Boolean

### _language

```csharp
private SystemLanguage _language
```

#### Field Value

**Type:** UnityEngine.SystemLanguage

### _tutorialPlayed

```csharp
public bool _tutorialPlayed
```

#### Field Value

**Type:** System.Boolean

### bPlayingGame

```csharp
private bool bPlayingGame
```

#### Field Value

**Type:** System.Boolean

### BuildVer

```csharp
public string BuildVer
```

#### Field Value

**Type:** System.String

### calcTime

```csharp
private bool calcTime
```

#### Field Value

**Type:** System.Boolean

### canvas

```csharp
public Canvas canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### checkPointOffset

```csharp
public const int checkPointOffset = 10000
```

#### Field Value

**Type:** System.Int32

### dlcCreatureOn

```csharp
public bool dlcCreatureOn
```

#### Field Value

**Type:** System.Boolean

### etcRemembered

```csharp
public string etcRemembered
```

#### Field Value

**Type:** System.String

### fontList

```csharp
[SerializeField]
private List<GlobalGameManager.LanguageFont> fontList
```

#### Field Value

**Type:** System.Collections.Generic.List{GlobalGameManager.LanguageFont}

### gameMode

```csharp
public GameMode gameMode
```

#### Field Value

**Type:** Global.GameMode

### isLoaded

```csharp
public bool isLoaded
```

#### Field Value

**Type:** System.Boolean

### language

```csharp
public string language
```

#### Field Value

**Type:** System.String

### lastLoaded

```csharp
public bool lastLoaded
```

#### Field Value

**Type:** System.Boolean

### loadingScene

```csharp
public string loadingScene
```

#### Field Value

**Type:** System.String

### loadingScreen

```csharp
public LoadingScreen loadingScreen
```

#### Field Value

**Type:** Global.LoadingScreen

### logCount

```csharp
private int logCount
```

#### Field Value

**Type:** System.Int32

### logMax

```csharp
private const int logMax = 10
```

#### Field Value

**Type:** System.Int32

### logOutput

```csharp
private string logOutput
```

#### Field Value

**Type:** System.String

### logStack

```csharp
private string logStack
```

#### Field Value

**Type:** System.String

### playTime

```csharp
public float playTime
```

#### Field Value

**Type:** System.Single

### preLoadedTutorialData

```csharp
[HideInInspector]
public Dictionary<string, object> preLoadedTutorialData
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### SAVE_VER

```csharp
private const string SAVE_VER = "ver1"
```

#### Field Value

**Type:** System.String

### saveEtcFileName

```csharp
private string saveEtcFileName
```

#### Field Value

**Type:** System.String

### saveFileName

```csharp
private string saveFileName
```

#### Field Value

**Type:** System.String

### saveGlobalFileName

```csharp
private string saveGlobalFileName
```

#### Field Value

**Type:** System.String

### saveState

```csharp
public string saveState
```

#### Field Value

**Type:** System.String

### saveUnlimitFileName

```csharp
private string saveUnlimitFileName
```

#### Field Value

**Type:** System.String

### saveVerName

```csharp
public const string saveVerName = "170808"
```

#### Field Value

**Type:** System.String

### sceneDataSaver

```csharp
public SceneDataSave sceneDataSaver
```

#### Field Value

**Type:** Global.SceneDataSave

### ScreenWidth

```csharp
public int ScreenWidth
```

#### Field Value

**Type:** System.Int32

### singledaySave

```csharp
public string singledaySave
```

#### Field Value

**Type:** System.String

### storySaveDir

```csharp
public string storySaveDir
```

#### Field Value

**Type:** System.String

### tutorialStep

```csharp
public int tutorialStep
```

#### Field Value

**Type:** System.Int32

### ver

```csharp
private const string ver = "170808"
```

#### Field Value

**Type:** System.String

### verPathName

```csharp
public const string verPathName = "170808"
```

#### Field Value

**Type:** System.String

## Properties

### currentLanguageFont

```csharp
public static GlobalGameManager.LanguageFont currentLanguageFont { get; }
```

#### Property Value

**Type:** Global.GlobalGameManager.LanguageFont

### instance

```csharp
public static GlobalGameManager instance { get; }
```

#### Property Value

**Type:** Global.GlobalGameManager

### isPlayingTutorial

```csharp
public bool isPlayingTutorial { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Language

```csharp
public SystemLanguage Language { get; set; }
```

#### Property Value

**Type:** UnityEngine.SystemLanguage

### logSrc

```csharp
private string logSrc { get; }
```

#### Property Value

**Type:** System.String

### stateSrc

```csharp
private string stateSrc { get; }
```

#### Property Value

**Type:** System.String

### tutorialPlayed

```csharp
public bool tutorialPlayed { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Awake()

```csharp
private void Awake()
```

### ChangeFont(string, FontType, string)

```csharp
public void ChangeFont(string language, FontType type, string fontName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `language` | `System.String` |  |
| `type` | `Global.FontType` |  |
| `fontName` | `System.String` |  |

### ChangeLanguage(SystemLanguage)

```csharp
public void ChangeLanguage(SystemLanguage value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `UnityEngine.SystemLanguage` |  |

### ExistEtcData()

```csharp
public bool ExistEtcData()
```

#### Returns

**Type:** System.Boolean

### ExistSaveData()

```csharp
public bool ExistSaveData()
```

#### Returns

**Type:** System.Boolean

### ExistUnlimitData()

```csharp
public bool ExistUnlimitData()
```

#### Returns

**Type:** System.Boolean

### GetCurrentLanguage()

```csharp
public string GetCurrentLanguage()
```

#### Returns

**Type:** System.String

### GetDayFromSaveData(Dictionary<string, object>)

```csharp
private int GetDayFromSaveData(Dictionary<string, object> dayData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dayData` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

#### Returns

**Type:** System.Int32

### GetLanguage(string)

```csharp
public SystemLanguage GetLanguage(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** UnityEngine.SystemLanguage

### GetLanguage(SystemLanguage)

```csharp
public string GetLanguage(SystemLanguage ln)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ln` | `UnityEngine.SystemLanguage` |  |

#### Returns

**Type:** System.String

### GetLanguageFont(string)

```csharp
public GlobalGameManager.LanguageFont GetLanguageFont(string language)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `language` | `System.String` |  |

#### Returns

**Type:** Global.GlobalGameManager.LanguageFont

### GetLogSrc()

```csharp
private string GetLogSrc()
```

#### Returns

**Type:** System.String

### GetSaveDayData()

```csharp
public Dictionary<string, object> GetSaveDayData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### InitHidden()

```csharp
public void InitHidden()
```

### InitStoryMode()

```csharp
public void InitStoryMode()
```

### InitTutorial(int)

```csharp
public void InitTutorial(int step)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `step` | `System.Int32` |  |

### IsPlaying()

```csharp
public bool IsPlaying()
```

#### Returns

**Type:** System.Boolean

### LateUpdate()

```csharp
private void LateUpdate()
```

### LoadCheckPointDay()

```csharp
public int LoadCheckPointDay()
```

#### Returns

**Type:** System.Int32

### LoadData(SaveType)

```csharp
public void LoadData(SaveType saveType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveType` | `Global.SaveType` |  |

### LoadData_preprocess()

```csharp
private void LoadData_preprocess()
```

### LoadDay(Dictionary<string, object>)

```csharp
private void LoadDay(Dictionary<string, object> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadEtcFile()

```csharp
public Dictionary<string, object> LoadEtcFile()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadGlobalData()

```csharp
public void LoadGlobalData()
```

### LoadSaveFile()

```csharp
public Dictionary<string, object> LoadSaveFile()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadStateData()

```csharp
public void LoadStateData()
```

### LoadUnlimitData()

```csharp
public void LoadUnlimitData()
```

### MessageHandler(string, string, LogType)

```csharp
private void MessageHandler(string logString, string stackTrace, LogType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `logString` | `System.String` |  |
| `stackTrace` | `System.String` |  |
| `type` | `UnityEngine.LogType` |  |

### OnApplicationQuit()

```csharp
private void OnApplicationQuit()
```

### OnDisable()

```csharp
private void OnDisable()
```

### OnEnable()

```csharp
private void OnEnable()
```

### OnLevelWasLoaded()

```csharp
private void OnLevelWasLoaded()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string name, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `param` | `System.Object[]` |  |

### PreLoadData()

```csharp
public int PreLoadData()
```

#### Returns

**Type:** System.Int32

### ReleaseGame()

```csharp
public void ReleaseGame()
```

### RemoveEtcData()

```csharp
public void RemoveEtcData()
```

### RemoveGlobalData()

```csharp
public void RemoveGlobalData()
```

### RemoveSaveData()

```csharp
public void RemoveSaveData()
```

### RemoveUnlimitData()

```csharp
public void RemoveUnlimitData()
```

### SaveData(bool)

```csharp
public void SaveData(bool saveCheckPoint = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveCheckPoint` | `System.Boolean` |  |

### SaveDataWithCheckPoint()

```csharp
public void SaveDataWithCheckPoint()
```

### SaveEtcData()

```csharp
public void SaveEtcData()
```

### SaveGlobalData()

```csharp
public void SaveGlobalData()
```

### SaveLogs()

```csharp
private void SaveLogs()
```

### SaveStateData()

```csharp
public void SaveStateData()
```

### SaveUnlimitData()

```csharp
public void SaveUnlimitData()
```

### SetLanguageFont()

```csharp
public void SetLanguageFont()
```

### Start()

```csharp
private void Start()
```

### StoryReturnTitle()

```csharp
public void StoryReturnTitle()
```

### TryGetGlobalData(out Dictionary<string, object>)

```csharp
public bool TryGetGlobalData(out Dictionary<string, object> dictionary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dictionary` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

#### Returns

**Type:** System.Boolean

### TrySetGlobalInventoryData(Dictionary<string, object>)

```csharp
public bool TrySetGlobalInventoryData(Dictionary<string, object> dictionary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dictionary` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

#### Returns

**Type:** System.Boolean

### Update()

```csharp
private void Update()
```
