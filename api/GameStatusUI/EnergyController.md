---
uid: GameStatusUI.EnergyController
canonical_path: /api/GameStatusUI/EnergyController
---

# Class EnergyController

**Namespace:** [GameStatusUI](/api/GameStatusUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EnergyController : MonoBehaviour
```

extends 
UI for displaying the current energy, as well as potential ordeals (or otherwise the number of upcoming meltdowns).

See [GameStatusUI](/api/GameStatusUI)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → EnergyController

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EnergyController()

```csharp
public EnergyController()
```

## Fields

### _currentEntered

```csharp
private int _currentEntered
```
#INC


#### Field Value

**Type:** System.Int32

### _overloadUITime

```csharp
private const float _overloadUITime = 5
```
#INC


#### Field Value

**Type:** System.Single

### _overloadUITimer

```csharp
private UnscaledTimer _overloadUITimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### current

```csharp
private float current
```
#INC


#### Field Value

**Type:** System.Single

### EnergyFill

```csharp
public Image EnergyFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### InnerText

```csharp
public Text InnerText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### LobPoint

```csharp
public Text LobPoint
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### LobPointTexture

```csharp
public Image LobPointTexture
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### max

```csharp
private float max
```
#INC


#### Field Value

**Type:** System.Single

### Orange

```csharp
public Color Orange
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### OrdealSlots

```csharp
[Header("Ordeal")]
public EnergyController.OrdealSlot[] OrdealSlots
```

#### Field Value

**Type:** GameStatusUI.EnergyController.OrdealSlot[]

### OverloadClip

```csharp
public AudioClip OverloadClip
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### OverloadColored

```csharp
public List<MaskableGraphic> OverloadColored
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### OverLoadGaugeLayout

```csharp
public GameObject OverLoadGaugeLayout
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### OverloadGaugeUnitPrefab

```csharp
public GameObject OverloadGaugeUnitPrefab
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### OverloadImage

```csharp
public Image OverloadImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### OverLoadIsolateNumText

```csharp
[Header("Overload")]
public Text OverLoadIsolateNumText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### OverloadLevelText

```csharp
public Text OverloadLevelText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### OverLoadOrdealImage

```csharp
public Image OverLoadOrdealImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### OverLoadOrdealName

```csharp
public Text OverLoadOrdealName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### OverLoadOrdealRoot

```csharp
public GameObject OverLoadOrdealRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### OverloadUIController

```csharp
public UIController OverloadUIController
```
#INC


#### Field Value

**Type:** Global.UIController

### OverloadUIText

```csharp
public Text OverloadUIText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### PlayTime

```csharp
[Header("StageInfo")]
public Text PlayTime
```

#### Field Value

**Type:** UnityEngine.UI.Text

### RankSlots

```csharp
public EnergyController.RankSlot[] RankSlots
```

#### Field Value

**Type:** GameStatusUI.EnergyController.RankSlot[]

### Red

```csharp
public Color Red
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### stageRewardInfo

```csharp
private StageRewardTypeInfo stageRewardInfo
```
#INC


#### Field Value

**Type:** Global.StageRewardTypeInfo

## Methods

### CheckGameStatus()

```csharp
public void CheckGameStatus()
```
#INC


### GetOrdealName(OrdealLevel)

```csharp
private string GetOrdealName(OrdealLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

#### Returns

**Type:** System.String

### GetRankTime(StageRank)

```csharp
public float GetRankTime(StageRank rank)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `Global.StageRank` |  |

#### Returns

**Type:** System.Single

### OnRankSlotEnter(int)

```csharp
public void OnRankSlotEnter(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnRankSlotExit(int)

```csharp
public void OnRankSlotExit(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### OrdealSlotInit()

```csharp
private void OrdealSlotInit()
```
#INC


### OrdealUpdate()

```csharp
private void OrdealUpdate()
```
#INC


### SetDawnOrdeal(bool, int)

```csharp
public void SetDawnOrdeal(bool activated, int timeSec)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `timeSec` | `System.Int32` |  |

### SetDawnOrdeal(bool, int, int)

```csharp
public void SetDawnOrdeal(bool activated, int current, int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `current` | `System.Int32` |  |
| `max` | `System.Int32` |  |

### SetDawnOrdealVisible(bool)

```csharp
public void SetDawnOrdealVisible(bool visible)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `visible` | `System.Boolean` |  |

### SetDuskOrdeal(bool, int)

```csharp
public void SetDuskOrdeal(bool activated, int timeSec)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `timeSec` | `System.Int32` |  |

### SetDuskOrdeal(bool, int, int)

```csharp
public void SetDuskOrdeal(bool activated, int current, int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `current` | `System.Int32` |  |
| `max` | `System.Int32` |  |

### SetDuskOrdealVisible(bool)

```csharp
public void SetDuskOrdealVisible(bool visible)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `visible` | `System.Boolean` |  |

### SetNoonOrdeal(bool, int)

```csharp
public void SetNoonOrdeal(bool activated, int timeSec)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `timeSec` | `System.Int32` |  |

### SetNoonOrdeal(bool, int, int)

```csharp
public void SetNoonOrdeal(bool activated, int current, int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `current` | `System.Int32` |  |
| `max` | `System.Int32` |  |

### SetNoonOrdealVisible(bool)

```csharp
public void SetNoonOrdealVisible(bool visible)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `visible` | `System.Boolean` |  |

### SetOverloadGauge(int, int)

```csharp
public void SetOverloadGauge(int num, int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `num` | `System.Int32` |  |
| `max` | `System.Int32` |  |

### SetOverloadIsolateNum(int)

```csharp
public void SetOverloadIsolateNum(int num)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `num` | `System.Int32` |  |

### SetOverloadLevel(int)

```csharp
public void SetOverloadLevel(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetOverLoadOrdeal(OrdealBase)

```csharp
public void SetOverLoadOrdeal(OrdealBase ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |

### SetOverLoadUI(string)

```csharp
public void SetOverLoadUI(string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### SetStageRank(StageRank)

```csharp
public void SetStageRank(StageRank rank)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `Global.StageRank` |  |

### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
public void Update()
```
#INC
#code-generated

