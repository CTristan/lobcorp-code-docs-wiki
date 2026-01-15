---
uid: Global.BgmManager
canonical_path: /api/Global/IOBserver/BgmManager
---

# Class BgmManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BgmManager : MonoBehaviour, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → BgmManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BgmManager()

```csharp
public BgmManager()
```

## Fields

### _bossClip

```csharp
private AudioClip _bossClip
```

#### Field Value

**Type:** UnityEngine.AudioClip

### _currentDangerScore

```csharp
private float _currentDangerScore
```

#### Field Value

**Type:** System.Single

### _instance

```csharp
private static BgmManager _instance
```

#### Field Value

**Type:** Global.BgmManager

### _isUnique

```csharp
private bool _isUnique
```

#### Field Value

**Type:** System.Boolean

### _src

```csharp
private AudioSource _src
```

#### Field Value

**Type:** UnityEngine.AudioSource

### alarmBeep

```csharp
private const string alarmBeep = "alertBeep"
```

#### Field Value

**Type:** System.String

### canRecover

```csharp
public bool canRecover
```

#### Field Value

**Type:** System.Boolean

### currentAgent

```csharp
private int currentAgent
```

#### Field Value

**Type:** System.Int32

### currentBgmVolume

```csharp
public float currentBgmVolume
```

#### Field Value

**Type:** System.Single

### currentLevel

```csharp
private EmergencyLevel currentLevel
```

#### Field Value

**Type:** Global.EmergencyLevel

### currentLevelDisplay

```csharp
public Text currentLevelDisplay
```

#### Field Value

**Type:** UnityEngine.UI.Text

### currentMasterVolume

```csharp
public float currentMasterVolume
```

#### Field Value

**Type:** System.Single

### delayMin

```csharp
public float delayMin
```

#### Field Value

**Type:** System.Single

### delayTime

```csharp
[Range(10, 30)]
public float delayTime
```

#### Field Value

**Type:** System.Single

### elapsed

```csharp
private float elapsed
```

#### Field Value

**Type:** System.Single

### emergencyLevel_1

```csharp
public BgmManager.AudioClipList emergencyLevel_1
```

#### Field Value

**Type:** Global.BgmManager.AudioClipList

### emergencyLevel_2

```csharp
public BgmManager.AudioClipList emergencyLevel_2
```

#### Field Value

**Type:** Global.BgmManager.AudioClipList

### emergencyLevel_3

```csharp
public BgmManager.AudioClipList emergencyLevel_3
```

#### Field Value

**Type:** Global.BgmManager.AudioClipList

### fadeElap

```csharp
private float fadeElap
```

#### Field Value

**Type:** System.Single

### fadeEnabled

```csharp
private bool fadeEnabled
```

#### Field Value

**Type:** System.Boolean

### fadeInEvent

```csharp
public BgmManager.FadeEffectEvent fadeInEvent
```

#### Field Value

**Type:** Global.BgmManager.FadeEffectEvent

### fadeOutEvent

```csharp
public BgmManager.FadeEffectEvent fadeOutEvent
```

#### Field Value

**Type:** Global.BgmManager.FadeEffectEvent

### fadeTime

```csharp
public float fadeTime
```

#### Field Value

**Type:** System.Single

### isFadeIn

```csharp
private bool isFadeIn
```

#### Field Value

**Type:** System.Boolean

### isTimerRunning

```csharp
private bool isTimerRunning
```

#### Field Value

**Type:** System.Boolean

### normal

```csharp
public BgmManager.AudioClipList normal
```

#### Field Value

**Type:** Global.BgmManager.AudioClipList

### PlayingState

```csharp
public bool PlayingState
```

#### Field Value

**Type:** System.Boolean

### randTimer

```csharp
private Timer randTimer
```

#### Field Value

**Type:** Global.Timer

### recoverBlockTime

```csharp
private const float recoverBlockTime = 30
```

#### Field Value

**Type:** System.Single

### recoverBlockTimer

```csharp
private Timer recoverBlockTimer
```

#### Field Value

**Type:** Global.Timer

### recoveryTime

```csharp
private float recoveryTime
```

#### Field Value

**Type:** System.Single

### ScoreDisplay

```csharp
public Text ScoreDisplay
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SoundPlayTime

```csharp
public Text SoundPlayTime
```

#### Field Value

**Type:** UnityEngine.UI.Text

### stageAgentMax

```csharp
private int stageAgentMax
```

#### Field Value

**Type:** System.Int32

## Properties

### audioSource

```csharp
public AudioSource audioSource { get; }
```

#### Property Value

**Type:** UnityEngine.AudioSource

### controller

```csharp
private PlayerModel.EmergencyController controller { get; }
```

#### Property Value

**Type:** Global.PlayerModel.EmergencyController

### currentDangerScore

```csharp
private float currentDangerScore { get; set; }
```

#### Property Value

**Type:** System.Single

### instance

```csharp
public static BgmManager instance { get; }
```

#### Property Value

**Type:** Global.BgmManager

### IsBossActivated

```csharp
public bool IsBossActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### isPlaying

```csharp
public bool isPlaying { get; }
```

#### Property Value

**Type:** System.Boolean

### recoverMult

```csharp
private float recoverMult { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### Awake()

```csharp
private void Awake()
```

### BGMForcelyStop()

```csharp
public void BGMForcelyStop()
```

### BlockRecover()

```csharp
public void BlockRecover()
```

### BlockRecoverInf()

```csharp
public void BlockRecoverInf()
```

### ClearUniqueBgm()

```csharp
public void ClearUniqueBgm()
```

### FadeIn()

```csharp
public bool FadeIn()
```

#### Returns

**Type:** System.Boolean

### FadeOut()

```csharp
public bool FadeOut()
```

#### Returns

**Type:** System.Boolean

### FixedUpdate()

```csharp
private void FixedUpdate()
```

### GetBossClip()

```csharp
public AudioClip GetBossClip()
```

#### Returns

**Type:** UnityEngine.AudioClip

### GetClip(EmergencyLevel)

```csharp
private AudioClip GetClip(EmergencyLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.EmergencyLevel` |  |

#### Returns

**Type:** UnityEngine.AudioClip

### GetClipList(EmergencyLevel)

```csharp
public BgmManager.AudioClipList GetClipList(EmergencyLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.EmergencyLevel` |  |

#### Returns

**Type:** Global.BgmManager.AudioClipList

### GetCurrentClip(EmergencyLevel)

```csharp
private AudioClip GetCurrentClip(EmergencyLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.EmergencyLevel` |  |

#### Returns

**Type:** UnityEngine.AudioClip

### Halt()

```csharp
public void Halt()
```

### InitVolume(float, float)

```csharp
public void InitVolume(float master, float bgm)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `master` | `System.Single` |  |
| `bgm` | `System.Single` |  |

### LoadUniqueBgm(string)

```csharp
public void LoadUniqueBgm(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### OnClick(string)

```csharp
public void OnClick(string level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.String` |  |

### OnManagementStart()

```csharp
public void OnManagementStart()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### PlayBgm(AudioClip)

```csharp
private void PlayBgm(AudioClip clip)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clip` | `UnityEngine.AudioClip` |  |

### ReleaseRecoverBlock()

```csharp
public void ReleaseRecoverBlock()
```

### ResetBgm()

```csharp
public void ResetBgm()
```

### Resume()

```csharp
public void Resume()
```

### SetBgm(EmergencyLevel)

```csharp
public void SetBgm(EmergencyLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.EmergencyLevel` |  |

### SetBgmSoundVolume(float)

```csharp
public void SetBgmSoundVolume(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetBossClip()

```csharp
public void SetBossClip()
```

### SetBossClip(string)

```csharp
public void SetBossClip(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### SetMasterSoundVolume(float)

```csharp
public void SetMasterSoundVolume(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### Start()

```csharp
private void Start()
```

### SubAgent()

```csharp
public void SubAgent()
```

### Update()

```csharp
public void Update()
```
