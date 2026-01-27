---
uid: CommandWindow.AgentEquipmentSlot
canonical_path: /api/CommandWindow/AgentEquipmentSlot
---

# Class AgentEquipmentSlot

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentEquipmentSlot
```
UI element for displaying an [agent](/api/Global/Worker/AgentUnit)'s gear section and resistances in the suppression UI. #INC 

See [SuppressSlot](/api/CommandWindow/SuppressSlot)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentEquipmentSlot

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentEquipmentSlot()

```csharp
public AgentEquipmentSlot()
```

## Fields

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Additional

```csharp
public Text Additional
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ArmorGrade

```csharp
public Text ArmorGrade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ArmorName

```csharp
[Header("Armor")]
public Text ArmorName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DefenseFactorRenderer

```csharp
public Image[] DefenseFactorRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image[]

### DefenseType

```csharp
public Text[] DefenseType
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### DualValue

```csharp
public GameObject DualValue
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### SingleValue

```csharp
[Space(5)]
public GameObject SingleValue
```

#### Field Value

**Type:** UnityEngine.GameObject

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

### Vanlia

```csharp
public List<Text> Vanlia
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Text}

### WeaponGrade

```csharp
public Text WeaponGrade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WeaponName

```csharp
[Header("Weapon")]
public Text WeaponName
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetData(AgentModel)

```csharp
public void SetData(AgentModel agent)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
