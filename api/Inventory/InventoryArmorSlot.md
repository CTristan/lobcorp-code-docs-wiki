---
uid: Inventory.InventoryArmorSlot
canonical_path: /api/Inventory/InventoryArmorSlot
---

# Class InventoryArmorSlot

**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public class InventoryArmorSlot : InventorySlot
```

EGO Suit entry.

See [InventoryItemController](/api/Inventory/InventoryItemController)

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [InventorySlot](/api/Inventory/InventorySlot) → InventoryArmorSlot

## Inherited Members
[_info](/api/Inventory/InventorySlot#info), [Grade](/api/Inventory/InventorySlot#grade), [Icon](/api/Inventory/InventorySlot#icon), [Name](/api/Inventory/InventorySlot#name), [TooltipButton](/api/Inventory/InventorySlot#tooltipbutton), [ownerSlot](/api/Inventory/InventorySlot#ownerslot), [requireLayout](/api/Inventory/InventorySlot#requirelayout), [equipments](/api/Inventory/InventorySlot#equipments), [owners](/api/Inventory/InventorySlot#owners), [Awake()](/api/Inventory/InventorySlot#awake), [SetModel(EquipmentTypeInfo, List<EquipmentModel>)](/api/Inventory/InventorySlot#setmodel-equipmenttypeinfo-list-equipmentmodel), [UpdateList(List<EquipmentModel>)](/api/Inventory/InventorySlot#updatelist-list-equipmentmodel), [RequireInit(EquipmentTypeInfo)](/api/Inventory/InventorySlot#requireinit-equipmenttypeinfo), [GetEquipmentModel(InventoryAgentSlot)](/api/Inventory/InventorySlot#getequipmentmodel-inventoryagentslot), [GetDummyEquipmentModel()](/api/Inventory/InventorySlot#getdummyequipmentmodel), [CheckOwner()](/api/Inventory/InventorySlot#checkowner), [OnClickAgentSlot(InventoryAgentSlot)](/api/Inventory/InventorySlot#onclickagentslot-inventoryagentslot), [GetAgentSlotIndex(AgentModel)](/api/Inventory/InventorySlot#getagentslotindex-agentmodel), [CheckRequire(EquipmentModel, AgentModel)](/api/Inventory/InventorySlot#checkrequire-equipmentmodel-agentmodel), [CheckOwner(AgentModel)](/api/Inventory/InventorySlot#checkowner-agentmodel), [CheckOwner(AgentModel, out EquipmentModel)](/api/Inventory/InventorySlot#checkowner-agentmodel-out-equipmentmodel), [GetOwnedEquipment(AgentModel)](/api/Inventory/InventorySlot#getownedequipment-agentmodel), [GetUnownedEquipment(out EquipmentModel)](/api/Inventory/InventorySlot#getunownedequipment-out-equipmentmodel), [SortCompare(InventorySlot, InventorySlot)](/api/Inventory/InventorySlot#sortcompare-inventoryslot-inventoryslot), [LateUpdate()](/api/Inventory/InventorySlot#lateupdate), [Info](/api/Inventory/InventorySlot#info), [RectTransform](/api/Inventory/InventorySlot#recttransform), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InventoryArmorSlot()

```csharp
public InventoryArmorSlot()
```

## Fields

### _armor

```csharp
private ArmorModel _armor
```
#INC


#### Field Value

**Type:** Global.ArmorModel

### DefenseFactor

```csharp
public Text[] DefenseFactor
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseInfo

```csharp
public Text[] DefenseInfo
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### oldText

```csharp
private string oldText
```
#INC


#### Field Value

**Type:** System.String

### portrait

```csharp
public WorkerPortraitSetter portrait
```
#INC


#### Field Value

**Type:** Global.WorkerPortraitSetter

## Properties

### Armor

```csharp
public ArmorModel Armor { get; }
```

#### Property Value

**Type:** Global.ArmorModel

## Methods

### ApplyPortrait()

```csharp
public override void ApplyPortrait()
```
#INC


### CheckTransformRaycast(Transform)

```csharp
private void CheckTransformRaycast(Transform t)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Transform` |  |

### InitScroll()

```csharp
public void InitScroll()
```
#INC


### OnCheckOwner()

```csharp
public void OnCheckOwner()
```
#INC


### OnClickEquipment()

```csharp
public void OnClickEquipment()
```
#INC


### OnClickToolTip()

```csharp
public void OnClickToolTip()
```
#INC


### OnDisabledClick()

```csharp
public void OnDisabledClick()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### OnEnterEquip()

```csharp
public void OnEnterEquip()
```
#INC


### OnExitEquip()

```csharp
public void OnExitEquip()
```
#INC


### SetArmor(ArmorModel)

```csharp
public void SetArmor(ArmorModel armor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armor` | `Global.ArmorModel` |  |

### SetEquipmentText()

```csharp
public void SetEquipmentText()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### UpdateUI()

```csharp
public override void UpdateUI()
```
#INC
#code-generated

