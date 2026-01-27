---
uid: CreatureInfo.ArmorSlot
canonical_path: /api/CreatureInfo/ArmorSlot
---

# Class ArmorSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ArmorSlot : EquipSlot
```

Class for displaying the EGO Suit slot in the abnormality information screen.


**Fields:**
TooltipMouseOver MakeArmorTooltip: Tooltip for making? #INC
Text GradeText: Class? #INC
Text TypeText: #INC
Text RWBP_Defense: RWBP damage multipliers
Text MakeCount: How many are made out of how many possible? #INC
WorkerPortraitSetter portrait: presumably, the sprite for displaying the armor
Button BuildButton: button that makes the EGO
int Cost: PE box cost for making EGO

CreatureModel currentCreature: presumably, the parent abnormality


**Methods:**
void SetModel([EquipmentModel](/api/Global/Model/EquipmentModel) Model): Pseudo-constructor based on a more generic 'EquipmentModel'? #INC

void SetModel([EquipmentTypeInfo](/api/Global/Info/EquipmentTypeInfo) info): Pseudo-constructor from EquipmentTypeInfo? #INC

void CheckMakeCount(): Grabs and updates current count and max count from [InventoryModel](/api/Global/Model/InventoryModel).

void OnEnter(): Changes the text to display buy message

void OnExit(): Changes the text to display the cost


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo/EquipSlot) → ArmorSlot

## Inherited Members
[ActiveControl](/api/CreatureInfo/EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo/EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo/EquipSlot#blocktext), [Title](/api/CreatureInfo/EquipSlot#title), [Outlook](/api/CreatureInfo/EquipSlot#outlook), [ItemName](/api/CreatureInfo/EquipSlot#itemname), [_info](/api/CreatureInfo/EquipSlot#info), [_model](/api/CreatureInfo/EquipSlot#model), [makeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [CheckBlocked(bool, int)](/api/CreatureInfo/EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo/EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo/EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo/EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo/EquipSlot#info), [Model](/api/CreatureInfo/EquipSlot#model), [MakeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ArmorSlot()

```csharp
public ArmorSlot()
```

## Fields

### BuildButton

```csharp
public Button BuildButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### Cost

```csharp
public int Cost
```
#INC


#### Field Value

**Type:** System.Int32

### cost

```csharp
private string cost
```
#INC


#### Field Value

**Type:** System.String

### currentCreature

```csharp
public CreatureModel currentCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### GradeText

```csharp
public Text GradeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### MakeArmorTooltip

```csharp
public TooltipMouseOver MakeArmorTooltip
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### MakeCount

```csharp
public Text MakeCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### portrait

```csharp
public WorkerPortraitSetter portrait
```
#INC


#### Field Value

**Type:** Global.WorkerPortraitSetter

### RWBP_Defense

```csharp
public Text[] RWBP_Defense
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### TypeText

```csharp
public Text[] TypeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

## Properties

### ArmorModel

```csharp
private ArmorModel ArmorModel { get; }
```

#### Property Value

**Type:** Global.ArmorModel

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
