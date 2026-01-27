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

Main game manager.

Primarily handles enabling and initializing the right systems when loading, and managing save files.

Holds:
- Versioning info
- File names
- Current language
- Flag for enabling backer abnormalities
- Various global game state
- Active tutorial status
- [Game mode](/api/Global/Misc/GameMode)
- The Unity Canvas
- The current language font


#### Awake
Runs on game start.
- Loads saved global data with LoadStateData
- Sets the  volume
- [Sets resolution](/api/Global/Model/GameSettingModel)
- Marks itself not to be deleted on loading scenes
- Sets save file names
- [Loads static data](/api/Global/Loader/GameStaticDataLoader)
- Loads the [map](/api/Global/IOBserver/MapGraph)
- Registers itself to be notified of auto-saves
- Initializes the [AgentManager](/api/Global/IOBserver/AgentManager)
- Sets font
- Loads save data with LoadGlobalData

#### Update
Loads the title screen if in the start screen.
Edits the alpha of some canvas elements if loaded #INC .

#### LoadStateData
Loads saved global state data.
(Volumes, tooltips #inc, backer abnormality enabled-ness, language, 'logCount' #inc)
#### SaveStateData
Saves global state data.
(Volumes, tooltips #inc, backer abnormality enabled-ness, language, 'logCount' #inc)

#### LoadGlobalData
Loads global save file data.
Loads [observation data](/api/Global/IOBserver/CreatureManager), things stored in [GlobalEtcDataModel](/api/Global/Model/GlobalEtcDataModel), [researches obtained](/api/Global/Model/ResearchDataModel), [EGO owned](/api/Global/Model/InventoryModel), [missions completed](/api/Global/IOBserver/MissionManager), and [meltdowns completed](/api/Global/Misc/SefiraCharacterManager) #verify.
#### SaveGlobalData
Saves global save file data.
#### RemoveGlobalData
Removes global save file data.


#### SaveLogs
Writes the current log to file.


#### InitStoryMode
Starts a new story mode run.
- Initializes [MoneyModel](/api/Global/Model/MoneyModel)
- Clears:
	- [Departments](/api/Global/IOBserver/SefiraManager)
	- [Clerks?](/api/Global/Misc/OfficerManager)
	- [Agents](/api/Global/IOBserver/AgentManager)
	- [Abnormalities](/api/Global/IOBserver/CreatureManager)
- Initializes the [PlayerModel](/api/Global/Model/PlayerModel)
- Loads a day 1 agents from [StageRewardTypeList](/api/Global/List/StageRewardTypeList)
- Adds starting LOB

#### InitTutorial(int step)
Starts the tutorial.
Clears:
- [Observation data](/api/Global/IOBserver/CreatureManager)
- [Global data](/api/Global/Model/GlobalEtcDataModel)
- [Departments](/api/Global/IOBserver/SefiraManager)
- [Clerks](/api/Global/Misc/OfficerManager)
- [Agents](/api/Global/IOBserver/AgentManager)
- [Abnormalities](/api/Global/IOBserver/CreatureManager)
Initializes:
- [Research progress](/api/Global/Model/ResearchDataModel)
- [EGO owned](/api/Global/Model/InventoryModel)
- [Missions](/api/Global/IOBserver/MissionManager)
- [SefiraCharacterManager](/api/Global/Misc/SefiraCharacterManager) #INC 
- [LOB points](/api/Global/Model/MoneyModel)
- [Player](/api/Global/Model/PlayerModel)
Then sets the day to 0, [game mode](/api/Global/Misc/GameMode) to TUTORIAL, and starts playing.

#### InitHidden
Starts the game in the [game mode](/api/Global/Misc/GameMode) HIDDEN. #INC 


#### ReleaseGame
Exits from gameplay.
- Calls:
	- [InventoryModel](/api/Global/Model/InventoryModel) (OnReleaseGame)
	- [MissionManager](/api/Global/IOBserver/MissionManager) (ReleaseGame)
- Initializes [LOB points](/api/Global/Model/MoneyModel)
- Clears unit data in [SefiraManager](/api/Global/IOBserver/SefiraManager) #INC 
- Clears [clerks](/api/Global/Misc/OfficerManager)
- Clears [agents](/api/Global/IOBserver/AgentManager)
- Clears [abnormalities](/api/Global/IOBserver/CreatureManager)
- Initializes [PlayerModel](/api/Global/Model/PlayerModel)
- Clears [departments](/api/Global/IOBserver/SefiraManager)
- Reset [map](/api/Global/IOBserver/MapGraph)
- Calls [AgentNameList](/api/Global/List/AgentNameList) (OnInit)
- Creates a new [GameStaticDataLoader](/api/Global/Loader/GameStaticDataLoader) and loads containment unit info #INC 
- Sets some flags



#### ChangeFont
Changes the fonts based on the language with GetLanguageFont.
#### string GetLanguageFont
Chinese (both), Japanese, Vietnamese, Bulgarian, French, English, and Portuguese (both) use the same font as for English. All others have a custom font. #INC 
#### SetLanguageFont
Sets the font.
#### GetCurrentLanguage
Gets the language string. (It's public, though...)


#### MessageHandler
Logs a string and stack trace

#### OnApplicationQuit
Saves logs and global state data.
(Volumes, tooltips #inc, backer abnormality enabled-ness, language, 'logCount' #inc)

## #INC


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
#INC


#### Field Value

**Type:** Global.GlobalGameManager

### _isPlayingTutorial

```csharp
private bool _isPlayingTutorial
```
#INC


#### Field Value

**Type:** System.Boolean

### _language

```csharp
private SystemLanguage _language
```
#INC


#### Field Value

**Type:** UnityEngine.SystemLanguage

### _tutorialPlayed

```csharp
public bool _tutorialPlayed
```
#INC


#### Field Value

**Type:** System.Boolean

### bPlayingGame

```csharp
private bool bPlayingGame
```
#INC


#### Field Value

**Type:** System.Boolean

### BuildVer

```csharp
public string BuildVer
```
#INC


#### Field Value

**Type:** System.String

### calcTime

```csharp
private bool calcTime
```
#INC


#### Field Value

**Type:** System.Boolean

### canvas

```csharp
public Canvas canvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### checkPointOffset

```csharp
public const int checkPointOffset = 10000
```
#INC


#### Field Value

**Type:** System.Int32

### dlcCreatureOn

```csharp
public bool dlcCreatureOn
```
#INC


#### Field Value

**Type:** System.Boolean

### etcRemembered

```csharp
public string etcRemembered
```
#INC


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
#INC


#### Field Value

**Type:** Global.GameMode

### isLoaded

```csharp
public bool isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### language

```csharp
public string language
```
#INC


#### Field Value

**Type:** System.String

### lastLoaded

```csharp
public bool lastLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### loadingScene

```csharp
public string loadingScene
```
#INC


#### Field Value

**Type:** System.String

### loadingScreen

```csharp
public LoadingScreen loadingScreen
```
#INC


#### Field Value

**Type:** Global.LoadingScreen

### logCount

```csharp
private int logCount
```
#INC


#### Field Value

**Type:** System.Int32

### logMax

```csharp
private const int logMax = 10
```
#INC


#### Field Value

**Type:** System.Int32

### logOutput

```csharp
private string logOutput
```
#INC


#### Field Value

**Type:** System.String

### logStack

```csharp
private string logStack
```
#INC


#### Field Value

**Type:** System.String

### playTime

```csharp
public float playTime
```
#INC


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
#INC


#### Field Value

**Type:** System.String

### saveEtcFileName

```csharp
private string saveEtcFileName
```
#INC


#### Field Value

**Type:** System.String

### saveFileName

```csharp
private string saveFileName
```
#INC


#### Field Value

**Type:** System.String

### saveGlobalFileName

```csharp
private string saveGlobalFileName
```
#INC


#### Field Value

**Type:** System.String

### saveState

```csharp
public string saveState
```
#INC


#### Field Value

**Type:** System.String

### saveUnlimitFileName

```csharp
private string saveUnlimitFileName
```
#INC


#### Field Value

**Type:** System.String

### saveVerName

```csharp
public const string saveVerName = "170808"
```
#INC


#### Field Value

**Type:** System.String

### sceneDataSaver

```csharp
public SceneDataSave sceneDataSaver
```
#INC


#### Field Value

**Type:** Global.SceneDataSave

### ScreenWidth

```csharp
public int ScreenWidth
```
#INC


#### Field Value

**Type:** System.Int32

### singledaySave

```csharp
public string singledaySave
```
#INC


#### Field Value

**Type:** System.String

### storySaveDir

```csharp
public string storySaveDir
```
#INC


#### Field Value

**Type:** System.String

### tutorialStep

```csharp
public int tutorialStep
```
#INC


#### Field Value

**Type:** System.Int32

### ver

```csharp
private const string ver = "170808"
```
#INC


#### Field Value

**Type:** System.String

### verPathName

```csharp
public const string verPathName = "170808"
```
#INC


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
#INC
#code-generated


### ChangeFont(string, FontType, string)

```csharp
public void ChangeFont(string language, FontType type, string fontName)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `UnityEngine.SystemLanguage` |  |

### ExistEtcData()

```csharp
public bool ExistEtcData()
```
#INC


#### Returns

**Type:** System.Boolean

### ExistSaveData()

```csharp
public bool ExistSaveData()
```
#INC


#### Returns

**Type:** System.Boolean

### ExistUnlimitData()

```csharp
public bool ExistUnlimitData()
```
#INC


#### Returns

**Type:** System.Boolean

### GetCurrentLanguage()

```csharp
public string GetCurrentLanguage()
```
#INC


#### Returns

**Type:** System.String

### GetDayFromSaveData(Dictionary<string, object>)

```csharp
private int GetDayFromSaveData(Dictionary<string, object> dayData)
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.String

### GetSaveDayData()

```csharp
public Dictionary<string, object> GetSaveDayData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### InitHidden()

```csharp
public void InitHidden()
```
#INC


### InitStoryMode()

```csharp
public void InitStoryMode()
```
#INC


### InitTutorial(int)

```csharp
public void InitTutorial(int step)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `step` | `System.Int32` |  |

### IsPlaying()

```csharp
public bool IsPlaying()
```
#INC


#### Returns

**Type:** System.Boolean

### LateUpdate()

```csharp
private void LateUpdate()
```
#INC


### LoadCheckPointDay()

```csharp
public int LoadCheckPointDay()
```
#INC


#### Returns

**Type:** System.Int32

### LoadData(SaveType)

```csharp
public void LoadData(SaveType saveType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveType` | `Global.SaveType` |  |

### LoadData_preprocess()

```csharp
private void LoadData_preprocess()
```
#INC


### LoadDay(Dictionary<string, object>)

```csharp
private void LoadDay(Dictionary<string, object> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadEtcFile()

```csharp
public Dictionary<string, object> LoadEtcFile()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadGlobalData()

```csharp
public void LoadGlobalData()
```
#INC


### LoadSaveFile()

```csharp
public Dictionary<string, object> LoadSaveFile()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadStateData()

```csharp
public void LoadStateData()
```
#INC


### LoadUnlimitData()

```csharp
public void LoadUnlimitData()
```
#INC


### MessageHandler(string, string, LogType)

```csharp
private void MessageHandler(string logString, string stackTrace, LogType type)
```
#INC


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
#INC


### OnDisable()

```csharp
private void OnDisable()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### OnLevelWasLoaded()

```csharp
private void OnLevelWasLoaded()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string name, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `param` | `System.Object[]` |  |

### PreLoadData()

```csharp
public int PreLoadData()
```
#INC


#### Returns

**Type:** System.Int32

### ReleaseGame()

```csharp
public void ReleaseGame()
```
#INC


### RemoveEtcData()

```csharp
public void RemoveEtcData()
```
#INC


### RemoveGlobalData()

```csharp
public void RemoveGlobalData()
```
#INC


### RemoveSaveData()

```csharp
public void RemoveSaveData()
```
#INC


### RemoveUnlimitData()

```csharp
public void RemoveUnlimitData()
```
#INC


### SaveData(bool)

```csharp
public void SaveData(bool saveCheckPoint = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveCheckPoint` | `System.Boolean` |  |

### SaveDataWithCheckPoint()

```csharp
public void SaveDataWithCheckPoint()
```
#INC


### SaveEtcData()

```csharp
public void SaveEtcData()
```
#INC


### SaveGlobalData()

```csharp
public void SaveGlobalData()
```
#INC


### SaveLogs()

```csharp
private void SaveLogs()
```
#INC


### SaveStateData()

```csharp
public void SaveStateData()
```
#INC


### SaveUnlimitData()

```csharp
public void SaveUnlimitData()
```
#INC


### SetLanguageFont()

```csharp
public void SetLanguageFont()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### StoryReturnTitle()

```csharp
public void StoryReturnTitle()
```
#INC


### TryGetGlobalData(out Dictionary<string, object>)

```csharp
public bool TryGetGlobalData(out Dictionary<string, object> dictionary)
```
#INC


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
#INC


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
#INC

