---
uid: CommandWindow.SuppressSlot
canonical_path: /api/CommandWindow/SuppressSlot
---

# Class SuppressSlot

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SuppressSlot : AgentSlot
```

UI for displaying the agents along with their [defense info](/api/Global/Info/DefenseInfo) and equipment in the suppression window.

See [CommandWindow](/api/CommandWindow)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AgentSlot](/api/CommandWindow/AgentSlot) → SuppressSlot

## Inherited Members
[ActiveControl](/api/CommandWindow/AgentSlot#activecontrol), [Portrait](/api/CommandWindow/AgentSlot#portrait), [portrait](/api/CommandWindow/AgentSlot#portrait), [Grade](/api/CommandWindow/AgentSlot#grade), [AgentName](/api/CommandWindow/AgentSlot#agentname), [HealthFill](/api/CommandWindow/AgentSlot#healthfill), [HealthText](/api/CommandWindow/AgentSlot#healthtext), [MentalFill](/api/CommandWindow/AgentSlot#mentalfill), [MentalText](/api/CommandWindow/AgentSlot#mentaltext), [FilterControl](/api/CommandWindow/AgentSlot#filtercontrol), [FilterFill](/api/CommandWindow/AgentSlot#filterfill), [FilterText](/api/CommandWindow/AgentSlot#filtertext), [WorkFilterControl](/api/CommandWindow/AgentSlot#workfiltercontrol), [WorkFilterFill](/api/CommandWindow/AgentSlot#workfilterfill), [WorkFilterText](/api/CommandWindow/AgentSlot#workfiltertext), [WorkFilterSubText](/api/CommandWindow/AgentSlot#workfiltersubtext), [coloredTargets](/api/CommandWindow/AgentSlot#coloredtargets), [_overlayEntered](/api/CommandWindow/AgentSlot#overlayentered), [_state](/api/CommandWindow/AgentSlot#state), [_currentAgent](/api/CommandWindow/AgentSlot#currentagent), [GetRate(float, float)](/api/CommandWindow/AgentSlot#getrate-float-float), [SetModel(AgentModel)](/api/CommandWindow/AgentSlot#setmodel-agentmodel), [OnEnable()](/api/CommandWindow/AgentSlot#onenable), [OnClickInfo()](/api/CommandWindow/AgentSlot#onclickinfo), [SetUIColor()](/api/CommandWindow/AgentSlot#setuicolor), [SetColor(Color)](/api/CommandWindow/AgentSlot#setcolor-color), [CheckAgentState()](/api/CommandWindow/AgentSlot#checkagentstate), [SetFilter(AgentState)](/api/CommandWindow/AgentSlot#setfilter-agentstate), [OnOverlayEnter(int)](/api/CommandWindow/AgentSlot#onoverlayenter-int), [OnOvelrayExit(int)](/api/CommandWindow/AgentSlot#onovelrayexit-int), [OnOverlayEnter()](/api/CommandWindow/AgentSlot#onoverlayenter), [OnOvelrayExit()](/api/CommandWindow/AgentSlot#onovelrayexit), [OnClick()](/api/CommandWindow/AgentSlot#onclick), [Start()](/api/CommandWindow/AgentSlot#start), [OverlayEntered](/api/CommandWindow/AgentSlot#overlayentered), [State](/api/CommandWindow/AgentSlot#state), [IsOrderable](/api/CommandWindow/AgentSlot#isorderable), [CurrentAgent](/api/CommandWindow/AgentSlot#currentagent), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SuppressSlot()

```csharp
public SuppressSlot()
```

## Fields

### equipment

```csharp
public AgentEquipmentSlot equipment
```
#INC


#### Field Value

**Type:** CommandWindow.AgentEquipmentSlot

### tooltips

```csharp
[Header("Defense Tooltip")]
public TooltipMouseOver[] tooltips
```

#### Field Value

**Type:** Global.TooltipMouseOver[]

## Methods

### GetDefenseTypeText(DefenseInfo, RwbpType)

```csharp
private string GetDefenseTypeText(DefenseInfo def, RwbpType t)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `def` | `Global.DefenseInfo` |  |
| `t` | `Global.RwbpType` |  |

#### Returns

**Type:** System.String

### SetUI(AgentModel)

```csharp
public override void SetUI(AgentModel agent)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Update()

```csharp
private void Update()
```
#INC


### UpdateUI()

```csharp
public override void UpdateUI()
```
#INC

