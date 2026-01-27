---
uid: CreatureInfo.EquipSlot
canonical_path: /api/CreatureInfo/EquipSlot
---

# Class EquipSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipSlot
```

Parent class for displaying EGO in the abnormality information screen.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipSlot

## Derived
[ArmorSlot](/api/CreatureInfo/ArmorSlot), [GiftSlot](/api/CreatureInfo/GiftSlot), [WeaponSlot](/api/CreatureInfo/WeaponSlot)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EquipSlot()

```csharp
public EquipSlot()
```

## Fields

### _info

```csharp
private EquipmentTypeInfo _info
```
#INC


#### Field Value

**Type:** Global.EquipmentTypeInfo

### _model

```csharp
private EquipmentModel _model
```
#INC


#### Field Value

**Type:** Global.EquipmentModel

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### BlockControl

```csharp
public GameObject BlockControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### BlockText

```csharp
public Text BlockText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ItemName

```csharp
public Text ItemName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### makeInfo

```csharp
private CreatureEquipmentMakeInfo makeInfo
```
#INC


#### Field Value

**Type:** Global.CreatureEquipmentMakeInfo

### Outlook

```csharp
public Image Outlook
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Title

```csharp
[Header("UI Common")]
public Text Title
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### Info

```csharp
public EquipmentTypeInfo Info { get; }
```

#### Property Value

**Type:** Global.EquipmentTypeInfo

### MakeInfo

```csharp
public CreatureEquipmentMakeInfo MakeInfo { get; }
```

#### Property Value

**Type:** Global.CreatureEquipmentMakeInfo

### Model

```csharp
public EquipmentModel Model { get; }
```

#### Property Value

**Type:** Global.EquipmentModel

## Methods

### CheckBlocked(bool, int)

```csharp
public void CheckBlocked(bool state, int level)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
| `level` | `System.Int32` |  |

### CheckOpened(out int)

```csharp
public virtual bool CheckOpened(out int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### NoData(string)

```csharp
public void NoData(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

### SetEquipInfo(CreatureEquipmentMakeInfo)

```csharp
public virtual void SetEquipInfo(CreatureEquipmentMakeInfo i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Global.CreatureEquipmentMakeInfo` |  |

### SetModel(EquipmentModel)

```csharp
public virtual void SetModel(EquipmentModel Model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Model` | `Global.EquipmentModel` |  |

### SetModel(EquipmentTypeInfo)

```csharp
public virtual void SetModel(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
