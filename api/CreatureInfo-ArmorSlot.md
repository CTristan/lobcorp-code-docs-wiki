# Class ArmorSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ArmorSlot : EquipSlot
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo-EquipSlot) → ArmorSlot

## Inherited Members
[ActiveControl](/api/CreatureInfo-EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo-EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo-EquipSlot#blocktext), [Title](/api/CreatureInfo-EquipSlot#title), [Outlook](/api/CreatureInfo-EquipSlot#outlook), [ItemName](/api/CreatureInfo-EquipSlot#itemname), [CheckBlocked(bool, int)](/api/CreatureInfo-EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo-EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo-EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo-EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo-EquipSlot#info), [Model](/api/CreatureInfo-EquipSlot#model), [MakeInfo](/api/CreatureInfo-EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** UnityEngine.UI.Button

### Cost

```csharp
public int Cost
```

#### Field Value

**Type:** System.Int32

### currentCreature

```csharp
public CreatureModel currentCreature
```

#### Field Value

**Type:** Global.CreatureModel

### GradeText

```csharp
public Text GradeText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### MakeArmorTooltip

```csharp
public TooltipMouseOver MakeArmorTooltip
```

#### Field Value

**Type:** Global.TooltipMouseOver

### MakeCount

```csharp
public Text MakeCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### portrait

```csharp
public WorkerPortraitSetter portrait
```

#### Field Value

**Type:** Global.WorkerPortraitSetter

### RWBP_Defense

```csharp
public Text[] RWBP_Defense
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### TypeText

```csharp
public Text[] TypeText
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

## Methods

### CheckMakeCount()

```csharp
public void CheckMakeCount()
```

### OnEnter()

```csharp
public void OnEnter()
```

### OnExit()

```csharp
public void OnExit()
```

### SetModel(EquipmentModel)

```csharp
public override void SetModel(EquipmentModel Model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Model` | `Global.EquipmentModel` |  |

### SetModel(EquipmentTypeInfo)

```csharp
public override void SetModel(EquipmentTypeInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
