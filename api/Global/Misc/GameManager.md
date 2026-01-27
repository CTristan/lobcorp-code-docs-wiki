---
uid: Global.GameManager
canonical_path: /api/Global/Misc/GameManager
---

# Class GameManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameManager : MonoBehaviour
```

Broadly, the main script for the gameplay parts of the game #inc.

#### Start / InitGame -- Continue / New Game #inc
Starts the game. Plays story mode if needed, then initializes other managers:
- [CreatureManager](/api/Global/IOBserver/CreatureManager)
- [OrdealManager](/api/Global/Misc/OrdealManager)
- [SpecialEventManager](/api/Global/Misc/SpecialEventManager)
- [RandomEventManager](/api/Global/IOBserver/RandomEventManager)
- [OverlayManager](/api/Legacy/OverlayManager)
Also resets the map if starting from day 1.

#### StartStage -- Gameplay Start #inc
When the game starts (i.e. after continuing or finishing the new game story scene #inc), calls:
- [SefiraBossManager](/api/Global/IOBserver/SefiraBossManager)
- [DeployUI](/api/Global/UI/DeployUI)
- [BgmManager](/api/Global/IOBserver/BgmManager)
- [EnergyModel](/api/Global/IOBserver/EnergyModel)
- [UIEffectManager](/api/Global/Misc/UIEffectManager)
- [GameStatusUI](/api/GameStatusUI)
- [MissionManager](/api/Global/IOBserver/MissionManager)

#### StartGame -- Management Start
Starts management phase.
Loads Keter effects if needed, then:
- Calls (OnStageStart):
	- [CameraMover](/api/Global/Camera/Mover/CameraMover)
	- [SefiraManager](/api/Global/IOBserver/SefiraManager) (OnStageStart_first)
	- [AgentManager](/api/Global/IOBserver/AgentManager)
	- [RabbitManager](/api/Global/Misc/RabbitManager)
	- [RandomEventManager](/api/Global/IOBserver/RandomEventManager)
	- [CreatureManager](/api/Global/IOBserver/CreatureManager)
	- [OrdealManager](/api/Global/Misc/OrdealManager)
	- [GlobalHistory](/api/Global/IOBserver/GlobalHistory)
	- [MissionUI](/api/Global/IOBserver/MissionUI)
- Resets play speed in [GameStatusUI](/api/GameStatusUI)
- Starts each [Sefira](/api/Global/Misc/Sefira) opened (OnStageStart)
- Moves all [clerks](/api/Global/Misc/OfficerManager) to their department and starts their default actions
- Calls (OnStageStart):
	- [AgentLayer](/api/Global/IOBserver/AgentLayer)
	- [OfficerLayer](/api/Global/IOBserver/OfficerLayer)
	- [BgmManager](/api/Global/IOBserver/BgmManager) (OnManagementStart)
	- [SefiraBossManager](/api/Global/IOBserver/SefiraBossManager)
	- [CreatureOverloadManager](/api/Global/Creature/CreatureOverloadManager)
	- [GlobalBulletManager](/api/GlobalBullet/GlobalBulletManager)
- Notifies all observers which listen for stage start

#### EndGame -- Management End
Ends the management phase.
- Calls (OnStageEnd):
	- [RabbitManager](/api/Global/Misc/RabbitManager)
	- [CreatureManager](/api/Global/IOBserver/CreatureManager)
	- [OfficerManager](/api/Global/Misc/OfficerManager)
	- [AgentManager](/api/Global/IOBserver/AgentManager)
	- [RandomEventManager](/api/Global/IOBserver/RandomEventManager)
	- [SefiraBossManager](/api/Global/IOBserver/SefiraBossManager)
	- [CursorManager](/api/Global/Misc/CursorManager)
- Removes some timers #inc

#### Release -- Gameplay End
Releases the game (e.g. exiting to title / quitting #inc)
- Resets the camera to default
- Calls (OnStageRelease)
	- [RabbitManager](/api/Global/Misc/RabbitManager)
	- [CreatureManager](/api/Global/IOBserver/CreatureManager)
	- [SpecialEventManager](/api/Global/Misc/SpecialEventManager)
	- [OrdealManager](/api/Global/Misc/OrdealManager)
	- [OfficerManager](/api/Global/Misc/OfficerManager)
	- [AgentManager](/api/Global/IOBserver/AgentManager)
	- [PlayerModel](/api/Global/Model/PlayerModel)'s emergency controller
	- [BgmManager](/api/Global/IOBserver/BgmManager)
- Saves the overlay state #inc [OverlayManager](/api/Legacy/OverlayManager) (SaveState)
- Calls [GlobalBulletManager](/api/GlobalBullet/GlobalBulletManager)'s OnStageRelease
- Notifies observers of OnReleaseGameManager


#### ReturnToIntro
Returns to the intro before the title screen. Maybe. #INC 
- Resets time
- Ends management (EndGame)
- Releases game, I guess (Release)
- Calls [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager)'s ReleaseGame #INC 
- Loads the intro


#### ReturnToTitle
Returns to the title screen.
- Resets time
- Sets appropriate volume for [BgmManager](/api/Global/IOBserver/BgmManager)
- Ends management (EndGame)
- Release game, I guess (Release)
- Calls [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager)'s ReleaseGame #INC 
- Calls [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager)'s LoadGlobalData #INC 
- Sets the loading screen to default
- Loads the title screen via [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager)

#### ReturnToCheckPoint
Rewinds to a memory repository day
- Resets time
- Ends management (EndGame)
- Releases game, I guess? (Release)
- Sets volume
- Via GlobalGameManager:
	- Saves persistent data (SaveGlobalData) #INC 
	- Loads from checkpoint (LoadData)
- Initializes [CreatureGenerateInfoManager](/api/CreatureGenerate/CreatureGenerateInfoManager)
- Sets loading screen
- Loads main game via [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager)


#### MoveToCredit
Rolls credits #INC 


#### RestartGame
Restarts the day


#### ExitGame
Quits application


### Time
#### UpdateGameSpeed
Updates game speed (e.g. for boss events which set it, or after being updated by the play speed UI)

#### SetPlaySpeedForcely
(For boss events) force sets time speed

#### Pause
pauses and updates game speed

#### Resume
resumes and updates game speed

#### SetPlaySpeed
Sets the play speed and updates time

#### TutorialPause
pauses

#### TutorialResume
resumes


### section 3

#### FixedUpdate
Calls FixedUpdateProccess
If the game is not paused, call fixed updates for:
- [RabbitManager](/api/Global/Misc/RabbitManager)
- [CreatureManager](/api/Global/IOBserver/CreatureManager)
- [SpecialEventManager](/api/Global/Misc/SpecialEventManager)
- [OrdealManager](/api/Global/Misc/OrdealManager)
- [OfficerManager](/api/Global/Misc/OfficerManager)
- [AgentManager](/api/Global/IOBserver/AgentManager)
- [RandomEventManager](/api/Global/IOBserver/RandomEventManager)
- [GlobalBulletManager](/api/GlobalBullet/GlobalBulletManager)
- Every observer of FixedUpdate

#### FixedUpdateProccess
- Updates elapsed time for trumpets and ends if needed

#### SuccessStage
For when the energy quota is met

#### RevertSuccess
For when the energy quota is no longer met


#### ClearStage
If the energy exceeds the quota, end stage with ClearAction

#### ClearAction
- Sets play speed to 0
- Ends management
- Calls the emergency controller (OnStageEnd)
- Notifies observers of OnStageEnd
- Displays the [results screen](/api/Global/IANimatorEventCalled/ResultScreen)

#### ExitStage
- Resets time
- Calls next day in [PlayerModel](/api/Global/Model/PlayerModel)
- Releases with Release
- Updates [GlobalEtcDataModel](/api/Global/Model/GlobalEtcDataModel)'s day1clearCount #INC 
- In unlimited mode:
	- Sets loading screen to DayEndScene
	- if past day 99 exits to intro
	- otherwise loads into the next day
- In story mode:
	- Sets loading screen to DayEndScreen
	- Loads the story
- Sets saveState to "story" #INC 


#### GameOverEnding
Game over for losing on days 47-49 (see )


#### Quit
Quits application

#### PAUSECALL GetCurrentPauseCaller
Gets whatever paused the game

#### int GetMoneyReward
Gets the LOB amount for the day, accounting for penalties and Malkuth's bonus

#### int GetPenaltyValueByCreature
Penalty for breaching abnormalities; equal to the sum of risk levels, except breaching Alephs, who add 1000. [Army in Black](/api/Global/Misc/BlackCorps) is an Aleph when breaching.

#### float GetPenaltyValueByDead
LOB multiplier for survival rate.
Survival rate : multiplier
=    1 : 2.0
$\geq$ 0.9 : 1.5
$\geq$ 0.7 : 1.25
$\geq$ 0.5 : 1.0
$\geq$ 0.3 : 0.5
$<$ 0.3 : 0.0

#### GetStageRank
Gets the stage rank.
$\geq$    1 : S
$\geq$ 0.9 : A
$\geq$ 0.7 : B
$\geq$ 0.5 : C
$\geq$ 0.3 : D
$<$ 0.3 : F
##### Special Ending (unused)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → GameManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GameManager()

```csharp
public GameManager()
```

## Fields

### _currentGameManager

```csharp
private static GameManager _currentGameManager
```
#INC


#### Field Value

**Type:** Global.GameManager

### _finalRewardAdditionalLob

```csharp
private const int _finalRewardAdditionalLob = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _finalStageRewardDay

```csharp
private const int _finalStageRewardDay = 48
```
#INC


#### Field Value

**Type:** System.Int32

### currentPauseCaller

```csharp
private PAUSECALL currentPauseCaller
```
#INC


#### Field Value

**Type:** Global.PAUSECALL

### currentSpeedValue

```csharp
private float currentSpeedValue
```
#INC


#### Field Value

**Type:** System.Single

### currentUIState

```csharp
private CurrentUIState currentUIState
```
#INC


#### Field Value

**Type:** Global.CurrentUIState

### elapsed

```csharp
private float elapsed
```
#INC


#### Field Value

**Type:** System.Single

### emergency

```csharp
public bool emergency
```
#INC


#### Field Value

**Type:** System.Boolean

### emergencyReturn

```csharp
public float emergencyReturn
```
#INC


#### Field Value

**Type:** System.Single

### gameSpeedLevel

```csharp
public int gameSpeedLevel
```
#INC


#### Field Value

**Type:** System.Int32

### ManageStarted

```csharp
public bool ManageStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### Penalty

```csharp
public static readonly int[] Penalty
```
#INC


#### Field Value

**Type:** System.Int32[]

### playerModel

```csharp
private PlayerModel playerModel
```
#INC


#### Field Value

**Type:** Global.PlayerModel

### playTime

```csharp
private float playTime
```
#INC


#### Field Value

**Type:** System.Single

### saveFileName

```csharp
private string saveFileName
```
#INC


#### Field Value

**Type:** System.String

### stageEnded

```csharp
private bool stageEnded
```
#INC


#### Field Value

**Type:** System.Boolean

### state

```csharp
public GameState state
```
#INC


#### Field Value

**Type:** Global.GameState

## Properties

### BossEvent

```csharp
private bool BossEvent { get; }
```

#### Property Value

**Type:** System.Boolean

### currentGameManager

```csharp
public static GameManager currentGameManager { get; }
```

#### Property Value

**Type:** Global.GameManager

### PlayTime

```csharp
public float PlayTime { get; }
```

#### Property Value

**Type:** System.Single

### StageEnded

```csharp
public bool StageEnded { get; }
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


### ClearAction()

```csharp
public void ClearAction()
```
#INC


### ClearStage()

```csharp
public void ClearStage()
```
#INC


### EndGame()

```csharp
public void EndGame()
```
#INC


### ExitGame()

```csharp
public void ExitGame()
```
#INC


### ExitStage()

```csharp
public void ExitStage()
```
#INC


### FixedUpdate()

```csharp
private void FixedUpdate()
```
#INC


### FixedUpdateProccess()

```csharp
public void FixedUpdateProccess()
```
#INC


### GameOverEnding()

```csharp
public void GameOverEnding()
```
#INC


### GetCurrentPauseCaller()

```csharp
public PAUSECALL GetCurrentPauseCaller()
```
#INC


#### Returns

**Type:** Global.PAUSECALL

### GetMoneyReward()

```csharp
public int GetMoneyReward()
```
#INC


#### Returns

**Type:** System.Int32

### GetPenaltyValueByCreature()

```csharp
public int GetPenaltyValueByCreature()
```
#INC


#### Returns

**Type:** System.Int32

### GetPenaltyValueByDead()

```csharp
public float GetPenaltyValueByDead()
```
#INC


#### Returns

**Type:** System.Single

### GetStageRank(float)

```csharp
public StageRank GetStageRank(float rate)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

#### Returns

**Type:** Global.StageRank

### InitGame()

```csharp
public void InitGame()
```
#INC


### LoadScene()

```csharp
private IEnumerator LoadScene()
```
#INC


#### Returns

**Type:** System.Collections.IEnumerator

### MoveToCredit()

```csharp
public void MoveToCredit()
```
#INC


### Pause()

```csharp
public void Pause()
```
#INC


### Pause(PAUSECALL)

```csharp
public void Pause(PAUSECALL caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### Quit()

```csharp
public void Quit()
```
#INC


### Release()

```csharp
private void Release()
```
#INC


### Reload()

```csharp
private IEnumerator Reload()
```
#INC


#### Returns

**Type:** System.Collections.IEnumerator

### RestartGame()

```csharp
public void RestartGame()
```
#INC


### Resume()

```csharp
public void Resume()
```
#INC


### Resume(PAUSECALL)

```csharp
public void Resume(PAUSECALL caller)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### ReturnToCheckPoint()

```csharp
public void ReturnToCheckPoint()
```
#INC


### ReturnToIntro()

```csharp
public void ReturnToIntro()
```
#INC


### ReturnToTitle()

```csharp
public void ReturnToTitle()
```
#INC


### RevertSuccess()

```csharp
public void RevertSuccess()
```
#INC


### SetPlaySpeed(int)

```csharp
public void SetPlaySpeed(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetPlaySpeedForcely(float)

```csharp
public void SetPlaySpeedForcely(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SpecialEnding()

```csharp
public void SpecialEnding()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### StartGame()

```csharp
public void StartGame()
```
#INC


### StartStage()

```csharp
public void StartStage()
```
#INC


### SuccessStage()

```csharp
public void SuccessStage()
```
#INC


### TutorialPause()

```csharp
public void TutorialPause()
```
#INC


### TutorialResume()

```csharp
public void TutorialResume()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateGameSpeed()

```csharp
private void UpdateGameSpeed()
```
#INC

