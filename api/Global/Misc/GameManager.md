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

#### Field Value

**Type:** Global.GameManager

### _finalRewardAdditionalLob

```csharp
private const int _finalRewardAdditionalLob = 20
```

#### Field Value

**Type:** System.Int32

### _finalStageRewardDay

```csharp
private const int _finalStageRewardDay = 48
```

#### Field Value

**Type:** System.Int32

### currentPauseCaller

```csharp
private PAUSECALL currentPauseCaller
```

#### Field Value

**Type:** Global.PAUSECALL

### currentSpeedValue

```csharp
private float currentSpeedValue
```

#### Field Value

**Type:** System.Single

### currentUIState

```csharp
private CurrentUIState currentUIState
```

#### Field Value

**Type:** Global.CurrentUIState

### elapsed

```csharp
private float elapsed
```

#### Field Value

**Type:** System.Single

### emergency

```csharp
public bool emergency
```

#### Field Value

**Type:** System.Boolean

### emergencyReturn

```csharp
public float emergencyReturn
```

#### Field Value

**Type:** System.Single

### gameSpeedLevel

```csharp
public int gameSpeedLevel
```

#### Field Value

**Type:** System.Int32

### ManageStarted

```csharp
public bool ManageStarted
```

#### Field Value

**Type:** System.Boolean

### Penalty

```csharp
public static readonly int[] Penalty
```

#### Field Value

**Type:** System.Int32[]

### playerModel

```csharp
private PlayerModel playerModel
```

#### Field Value

**Type:** Global.PlayerModel

### playTime

```csharp
private float playTime
```

#### Field Value

**Type:** System.Single

### saveFileName

```csharp
private string saveFileName
```

#### Field Value

**Type:** System.String

### stageEnded

```csharp
private bool stageEnded
```

#### Field Value

**Type:** System.Boolean

### state

```csharp
public GameState state
```

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

### ClearAction()

```csharp
public void ClearAction()
```

### ClearStage()

```csharp
public void ClearStage()
```

### EndGame()

```csharp
public void EndGame()
```

### ExitGame()

```csharp
public void ExitGame()
```

### ExitStage()

```csharp
public void ExitStage()
```

### FixedUpdate()

```csharp
private void FixedUpdate()
```

### FixedUpdateProccess()

```csharp
public void FixedUpdateProccess()
```

### GameOverEnding()

```csharp
public void GameOverEnding()
```

### GetCurrentPauseCaller()

```csharp
public PAUSECALL GetCurrentPauseCaller()
```

#### Returns

**Type:** Global.PAUSECALL

### GetMoneyReward()

```csharp
public int GetMoneyReward()
```

#### Returns

**Type:** System.Int32

### GetPenaltyValueByCreature()

```csharp
public int GetPenaltyValueByCreature()
```

#### Returns

**Type:** System.Int32

### GetPenaltyValueByDead()

```csharp
public float GetPenaltyValueByDead()
```

#### Returns

**Type:** System.Single

### GetStageRank(float)

```csharp
public StageRank GetStageRank(float rate)
```

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

### LoadScene()

```csharp
private IEnumerator LoadScene()
```

#### Returns

**Type:** System.Collections.IEnumerator

### MoveToCredit()

```csharp
public void MoveToCredit()
```

### Pause()

```csharp
public void Pause()
```

### Pause(PAUSECALL)

```csharp
public void Pause(PAUSECALL caller)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### Quit()

```csharp
public void Quit()
```

### Release()

```csharp
private void Release()
```

### Reload()

```csharp
private IEnumerator Reload()
```

#### Returns

**Type:** System.Collections.IEnumerator

### RestartGame()

```csharp
public void RestartGame()
```

### Resume()

```csharp
public void Resume()
```

### Resume(PAUSECALL)

```csharp
public void Resume(PAUSECALL caller)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |

### ReturnToCheckPoint()

```csharp
public void ReturnToCheckPoint()
```

### ReturnToIntro()

```csharp
public void ReturnToIntro()
```

### ReturnToTitle()

```csharp
public void ReturnToTitle()
```

### RevertSuccess()

```csharp
public void RevertSuccess()
```

### SetPlaySpeed(int)

```csharp
public void SetPlaySpeed(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetPlaySpeedForcely(float)

```csharp
public void SetPlaySpeedForcely(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SpecialEnding()

```csharp
public void SpecialEnding()
```

### Start()

```csharp
private void Start()
```

### StartGame()

```csharp
public void StartGame()
```

### StartStage()

```csharp
public void StartStage()
```

### SuccessStage()

```csharp
public void SuccessStage()
```

### TutorialPause()

```csharp
public void TutorialPause()
```

### TutorialResume()

```csharp
public void TutorialResume()
```

### Update()

```csharp
private void Update()
```

### UpdateGameSpeed()

```csharp
private void UpdateGameSpeed()
```
