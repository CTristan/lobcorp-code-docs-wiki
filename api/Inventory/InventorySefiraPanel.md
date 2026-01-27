---
uid: Inventory.InventorySefiraPanel
canonical_path: /api/Inventory/InventorySefiraPanel
---

# Class InventorySefiraPanel

**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public class InventorySefiraPanel
```
UI element for displaying the agents in a department on the [E.G.O List screen](/api/Inventory/InventoryUI).

See [InventorySefiraController](/api/Inventory/InventorySefiraController)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → InventorySefiraPanel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InventorySefiraPanel()

```csharp
public InventorySefiraPanel()
```

## Fields

### _currentSefira

```csharp
private Sefira _currentSefira
```
#INC


#### Field Value

**Type:** Global.Sefira

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### AreaNameText

```csharp
public Text AreaNameText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraAreaFill

```csharp
public Image SefiraAreaFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### slots

```csharp
public List<InventoryAgentSlot> slots
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Inventory.InventoryAgentSlot}

## Properties

### CurrentSefira

```csharp
public Sefira CurrentSefira { get; }
```

#### Property Value

**Type:** Global.Sefira

## Methods

### AwakeAction()

```csharp
public void AwakeAction()
```
#INC


### Init()

```csharp
public void Init()
```
#INC
#code-generated


### SetAgentList(SefiraUIColor)

```csharp
public void SetAgentList(SefiraUIColor color)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `color` | `Global.SefiraUIColor` |  |

### SetSefira(Sefira)

```csharp
public void SetSefira(Sefira current)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.Sefira` |  |
