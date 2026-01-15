---
uid: GameStatusUI.EnergyController.OrdealSlot
canonical_path: /api/GameStatusUI/EnergyController/OrdealSlot
---

# Class EnergyController.OrdealSlot

**Namespace:** [GameStatusUI](/api/GameStatusUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EnergyController.OrdealSlot
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EnergyController.OrdealSlot

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OrdealSlot()

```csharp
public OrdealSlot()
```

## Fields

### ColoredGraphic

```csharp
public List<MaskableGraphic> ColoredGraphic
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### OrdealNameText

```csharp
public Text OrdealNameText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### rootObject

```csharp
public GameObject rootObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### StatusText

```csharp
public Text StatusText
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetColorBlue()

```csharp
public void SetColorBlue()
```

### SetColorNormal()

```csharp
public void SetColorNormal()
```

### SetOrdealName(string)

```csharp
public void SetOrdealName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### SetStatusText(bool, int, int)

```csharp
public void SetStatusText(bool activated, int current, int max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `current` | `System.Int32` |  |
| `max` | `System.Int32` |  |

### SetStatusTimeText(bool, int)

```csharp
public void SetStatusTimeText(bool activated, int timeSec)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activated` | `System.Boolean` |  |
| `timeSec` | `System.Int32` |  |
