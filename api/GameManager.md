# Class GameManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameManager : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → GameManager

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GameManager()

```csharp
public GameManager()
```

## Fields

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

### state

```csharp
public GameState state
```

#### Field Value

**Type:** Global.GameState

## Properties

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
