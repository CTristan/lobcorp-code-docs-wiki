---
uid: CreatureInfo.WeaponSlot
canonical_path: /api/CreatureInfo/WeaponSlot
---

# Class WeaponSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WeaponSlot : EquipSlot
```
Class for displaying the EGO weapon in the abnormality information screen.

**Fields:**
TooltipMouseOver MakeWeaponTooltip: #INC

Image ItemImage: Weapon sprite

Text ItemGrade: Item EGO grade

Text DamageRange: range of damage (e.g., 4-6 red?)

Text AttackSpeed: estimate of attack speed (e.g., very slow)

Text MakeCount: displays how many are made of what max? #INC

Image TypeFill: ? #INC

Text TypeText: Type of weapon (e.g., spear?)

Button BuildButton: Buys and constructs a weapon

int Cost: cost in PE boxes of this weapon

CreatureModel currentCreature: presumably, a pointer to the parent? #INC



**Methods:**
void SetModel([EquipmentModel](/api/Global/Model/EquipmentModel) Model): Pseudo-constructor based on a more generic 'EquipmentModel'? #INC

void SetModel([EquipmentTypeInfo](/api/Global/Info/EquipmentTypeInfo) info): Pseudo-constructor from EquipmentTypeInfo? #INC

void CheckMakeCount(): Grabs and updates current count and max count from [InventoryModel](/api/Global/Model/InventoryModel).

void OnEnter(): Changes the text to display buy message

void OnExit(): Changes the text to display the cost

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo/EquipSlot) → WeaponSlot

## Inherited Members
[ActiveControl](/api/CreatureInfo/EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo/EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo/EquipSlot#blocktext), [Title](/api/CreatureInfo/EquipSlot#title), [Outlook](/api/CreatureInfo/EquipSlot#outlook), [ItemName](/api/CreatureInfo/EquipSlot#itemname), [_info](/api/CreatureInfo/EquipSlot#info), [_model](/api/CreatureInfo/EquipSlot#model), [makeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [CheckBlocked(bool, int)](/api/CreatureInfo/EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo/EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo/EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo/EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo/EquipSlot#info), [Model](/api/CreatureInfo/EquipSlot#model), [MakeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WeaponSlot()

```csharp
public WeaponSlot()
```

## Fields

### AttackRange

```csharp
public Text AttackRange
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### AttackSpeed

```csharp
public Text AttackSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### BuildButton

```csharp
public Button BuildButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### cost

```csharp
private string cost
```
#INC


#### Field Value

**Type:** System.String

### Cost

```csharp
public int Cost
```
#INC


#### Field Value

**Type:** System.Int32

### currentCreature

```csharp
public CreatureModel currentCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### DamageRange

```csharp
public Text DamageRange
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ItemGrade

```csharp
public Text ItemGrade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ItemImage

```csharp
public Image ItemImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### MakeCount

```csharp
public Text MakeCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### MakeWeaponTooltip

```csharp
public TooltipMouseOver MakeWeaponTooltip
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TypeFill

```csharp
public Image TypeFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### TypeText

```csharp
public Text TypeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### WeaponModel

```csharp
private WeaponModel WeaponModel { get; }
```

#### Property Value

**Type:** Global.WeaponModel

## Methods

### CheckMakeCount()

```csharp
public void CheckMakeCount()
```
#INC


### OnEnter()

```csharp
public void OnEnter()
```
#INC


### OnExit()

```csharp
public void OnExit()
```
#INC


### SetModel(EquipmentModel)

```csharp
public override void SetModel(EquipmentModel Model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Model` | `Global.EquipmentModel` |  |

### SetModel(EquipmentTypeInfo)

```csharp
public override void SetModel(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
