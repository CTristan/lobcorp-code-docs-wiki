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

#### Field Value

**Type:** Global.Sefira

### ActiveControl

```csharp
public GameObject ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### AreaNameText

```csharp
public Text AreaNameText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraAreaFill

```csharp
public Image SefiraAreaFill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### slots

```csharp
public List<InventoryAgentSlot> slots
```

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

### Init()

```csharp
public void Init()
```

### SetAgentList(SefiraUIColor)

```csharp
public void SetAgentList(SefiraUIColor color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `color` | `Global.SefiraUIColor` |  |

### SetSefira(Sefira)

```csharp
public void SetSefira(Sefira current)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.Sefira` |  |
