# Class GiftSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GiftSlot : EquipSlot
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo-EquipSlot) → GiftSlot

## Inherited Members
[ActiveControl](/api/CreatureInfo-EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo-EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo-EquipSlot#blocktext), [Title](/api/CreatureInfo-EquipSlot#title), [Outlook](/api/CreatureInfo-EquipSlot#outlook), [ItemName](/api/CreatureInfo-EquipSlot#itemname), [CheckBlocked(bool, int)](/api/CreatureInfo-EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo-EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo-EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo-EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo-EquipSlot#info), [Model](/api/CreatureInfo-EquipSlot#model), [MakeInfo](/api/CreatureInfo-EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GiftSlot()

```csharp
public GiftSlot()
```

## Fields

### ItemImage

```csharp
public Image ItemImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### ItemTrait

```csharp
public Text ItemTrait
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetEmpty()

```csharp
public void SetEmpty()
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

### SetProb(float)

```csharp
public void SetProb(float prob)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `prob` | `System.Single` |  |
