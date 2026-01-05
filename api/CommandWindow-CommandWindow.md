# Class CommandWindow

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CommandWindow : MonoBehaviour, IObserver, IScrollMessageReciever, IScrollTarget
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CommandWindow

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CommandWindow()

```csharp
public CommandWindow()
```

## Fields

### audioClipPlayer

```csharp
public AudioClipPlayer audioClipPlayer
```

#### Field Value

**Type:** Global.AudioClipPlayer

### BWork

```csharp
public const int BWork = 3
```

#### Field Value

**Type:** System.Int32

### CancelOrcerColor

```csharp
public Color CancelOrcerColor
```

#### Field Value

**Type:** UnityEngine.Color

### CretureSuppress

```csharp
public CreatureSuppressRegion CretureSuppress
```

#### Field Value

**Type:** CommandWindow.CreatureSuppressRegion

### DeadColor

```csharp
[Header("Color")]
public Color DeadColor
```

#### Field Value

**Type:** UnityEngine.Color

### imageColor

```csharp
[Header("ColorSet")]
public Color imageColor
```

#### Field Value

**Type:** UnityEngine.Color

### KitCreature_ActiveControl

```csharp
[Header("KitCreature")]
public GameObject KitCreature_ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### kitCreatureRegion

```csharp
public KitCreatureRegion kitCreatureRegion
```

#### Field Value

**Type:** CommandWindow.KitCreatureRegion

### LeftPos

```csharp
public float LeftPos
```

#### Field Value

**Type:** System.Single

### Management_ActiveControl

```csharp
[Header("Management")]
public GameObject Management_ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### ManagementAgentSlotParent

```csharp
[Header("Agent Slots")]
public GameObject ManagementAgentSlotParent
```

#### Field Value

**Type:** UnityEngine.GameObject

### ManagementSlots

```csharp
public List<ManagementSlot> ManagementSlots
```

#### Field Value

**Type:** System.Collections.Generic.List{CommandWindow.ManagementSlot}

### OrderColor

```csharp
public Color OrderColor
```

#### Field Value

**Type:** UnityEngine.Color

### page

```csharp
public int page
```

#### Field Value

**Type:** System.Int32

### PanicColor

```csharp
public Color PanicColor
```

#### Field Value

**Type:** UnityEngine.Color

### Position_Suppress

```csharp
public Vector2 Position_Suppress
```

#### Field Value

**Type:** UnityEngine.Vector2

### Position_Work

```csharp
public Vector2 Position_Work
```

#### Field Value

**Type:** UnityEngine.Vector2

### PositionPivot

```csharp
public RectTransform PositionPivot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### PWork

```csharp
public const int PWork = 4
```

#### Field Value

**Type:** System.Int32

### RightPos

```csharp
public float RightPos
```

#### Field Value

**Type:** System.Single

### RootControl

```csharp
public GameObject RootControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### RWork

```csharp
public const int RWork = 1
```

#### Field Value

**Type:** System.Int32

### SefiraDisabledColor

```csharp
public Color SefiraDisabledColor
```

#### Field Value

**Type:** UnityEngine.Color

### SefiraMovementPivot

```csharp
public RectTransform SefiraMovementPivot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### SefiraMovementUI

```csharp
[Header("SefiraMovement")]
public SefiraMovement SefiraMovementUI
```

#### Field Value

**Type:** CommandWindow.SefiraMovement

### Suppress_ActiveControl

```csharp
[Header("Suppress")]
public GameObject Suppress_ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### SuppressingColor

```csharp
public Color SuppressingColor
```

#### Field Value

**Type:** UnityEngine.Color

### SuppressPosition

```csharp
public Vector2 SuppressPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### SuppressSlots

```csharp
public List<SuppressSlot> SuppressSlots
```

#### Field Value

**Type:** System.Collections.Generic.List{CommandWindow.SuppressSlot}

### textColor

```csharp
public Color textColor
```

#### Field Value

**Type:** UnityEngine.Color

### UnconColor

```csharp
public Color UnconColor
```

#### Field Value

**Type:** UnityEngine.Color

### Work_B

```csharp
public Sprite Work_B
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_C

```csharp
public Sprite Work_C
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_I

```csharp
public Sprite Work_I
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_P

```csharp
public Sprite Work_P
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_Protection

```csharp
public Sprite Work_Protection
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_R

```csharp
[Header("WorkIcon")]
public Sprite Work_R
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_S

```csharp
public Sprite Work_S
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_V

```csharp
public Sprite Work_V
```

#### Field Value

**Type:** UnityEngine.Sprite

### Work_W

```csharp
public Sprite Work_W
```

#### Field Value

**Type:** UnityEngine.Sprite

### WorkAllocate

```csharp
public WorkAllocateRegion WorkAllocate
```

#### Field Value

**Type:** CommandWindow.WorkAllocateRegion

### WorkAllocate_ActiveControl

```csharp
public GameObject WorkAllocate_ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### WorkButton

```csharp
public Button[] WorkButton
```

#### Field Value

**Type:** UnityEngine.UI.Button[]

### WorkCommmandPosition

```csharp
[Header("Position")]
public Vector2 WorkCommmandPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### WorkerSuppress

```csharp
public WorkerSuppressRegion WorkerSuppress
```

#### Field Value

**Type:** CommandWindow.WorkerSuppressRegion

### WorkingColor

```csharp
public Color WorkingColor
```

#### Field Value

**Type:** UnityEngine.Color

### workNames

```csharp
public LocalizeTextLoadScript[] workNames
```

#### Field Value

**Type:** Assets.Scripts.UI.Utils.LocalizeTextLoadScript[]

### WorkScrollDown

```csharp
public GameObject WorkScrollDown
```

#### Field Value

**Type:** UnityEngine.GameObject

### WorkScrollUp

```csharp
public GameObject WorkScrollUp
```

#### Field Value

**Type:** UnityEngine.GameObject

### WWork

```csharp
public const int WWork = 2
```

#### Field Value

**Type:** System.Int32

## Properties

### CurrentSefira

```csharp
public Sefira CurrentSefira { get; }
```

#### Property Value

**Type:** Global.Sefira

### CurrentSkill

```csharp
public SkillTypeInfo CurrentSkill { get; }
```

#### Property Value

**Type:** Global.SkillTypeInfo

### CurrentTarget

```csharp
public UnitModel CurrentTarget { get; }
```

#### Property Value

**Type:** Global.UnitModel

### CurrentWindow

```csharp
public static CommandWindow CurrentWindow { get; }
```

#### Property Value

**Type:** CommandWindow.CommandWindow

### CurrentWindowType

```csharp
public CommandType CurrentWindowType { get; }
```

#### Property Value

**Type:** Global.CommandType

### IsEnabled

```csharp
public bool IsEnabled { get; set; }
```

#### Property Value

**Type:** System.Boolean

### SelectedWork

```csharp
public long SelectedWork { get; set; }
```

#### Property Value

**Type:** System.Int64

## Methods

### AddTrigger()

```csharp
public void AddTrigger()
```

### CheckSefiraMovementEnable()

```csharp
public bool CheckSefiraMovementEnable()
```

#### Returns

**Type:** System.Boolean

### CloseWindow()

```csharp
public void CloseWindow()
```

### CreateWindow(CommandType, UnitModel)

```csharp
public static CommandWindow CreateWindow(CommandType type, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.CommandType` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** CommandWindow.CommandWindow

### DeRegist()

```csharp
public void DeRegist()
```

### GetWorkSprite(RwbpType)

```csharp
public Sprite GetWorkSprite(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** UnityEngine.Sprite

### OnClick(AgentModel)

```csharp
public void OnClick(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnClickNextSefira()

```csharp
public void OnClickNextSefira()
```

### OnClickPrevSefira()

```csharp
public void OnClickPrevSefira()
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

### OnScroll(BaseEventData)

```csharp
public void OnScroll(BaseEventData bData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnSefiraMove(SefiraEnum)

```csharp
public void OnSefiraMove(SefiraEnum target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.SefiraEnum` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnWorkSelect(int)

```csharp
public void OnWorkSelect(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### Regist()

```csharp
public void Regist()
```

### SetAgentList(CommandType, List<AgentModel>)

```csharp
public void SetAgentList(CommandType type, List<AgentModel> agents)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.CommandType` |  |
| `agents` | `System.Collections.Generic.List{AgentModel}` |  |

### SetAgentList(CommandType, Sefira)

```csharp
public void SetAgentList(CommandType type, Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.CommandType` |  |
| `sefira` | `Global.Sefira` |  |
