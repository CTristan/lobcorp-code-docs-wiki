---
uid: Customizing.StatUI.StatController
canonical_path: /api/Customizing/StatUI/StatController
---

# Class StatUI.StatController

**Namespace:** [Customizing](/api/Customizing)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StatUI.StatController
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StatUI.StatController

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StatController()

```csharp
public StatController()
```

## Fields

### _currentCost

```csharp
private int _currentCost
```

#### Field Value

**Type:** System.Int32

### costAry

```csharp
private int[] costAry
```

#### Field Value

**Type:** System.Int32[]

### CostText

```csharp
public Text CostText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentBonus

```csharp
public int CurrentBonus
```

#### Field Value

**Type:** System.Int32

### Generate

```csharp
public bool Generate
```

#### Field Value

**Type:** System.Boolean

### GradeText

```csharp
public Text GradeText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Minus

```csharp
public Button Minus
```

#### Field Value

**Type:** UnityEngine.UI.Button

### OriginalLevel

```csharp
public int OriginalLevel
```

#### Field Value

**Type:** System.Int32

### Plus

```csharp
public Button Plus
```

#### Field Value

**Type:** UnityEngine.UI.Button

### PointText

```csharp
public Text PointText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### statUI

```csharp
private StatUI statUI
```

#### Field Value

**Type:** Customizing.StatUI

## Properties

### CurrentCost

```csharp
public int CurrentCost { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ButtonSetting()

```csharp
public void ButtonSetting()
```

### Init(int, int, bool)

```csharp
public void Init(int original, int bonus, bool generate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `original` | `System.Int32` |  |
| `bonus` | `System.Int32` |  |
| `generate` | `System.Boolean` |  |

### InitButtonAction()

```csharp
public void InitButtonAction()
```

### OnClickAfter()

```csharp
private void OnClickAfter()
```

### OnClickMinus()

```csharp
public void OnClickMinus()
```

### OnClickPlus()

```csharp
public void OnClickPlus()
```

### SetCost()

```csharp
public void SetCost()
```

### SetCostAry(int[])

```csharp
public void SetCostAry(int[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `System.Int32[]` |  |

### SetGradeText(int)

```csharp
public void SetGradeText(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetStatUI(StatUI)

```csharp
public void SetStatUI(StatUI ui)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ui` | `Customizing.StatUI` |  |
