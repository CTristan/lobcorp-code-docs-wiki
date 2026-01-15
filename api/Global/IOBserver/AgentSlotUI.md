---
uid: Global.AgentSlotUI
canonical_path: /api/Global/IOBserver/AgentSlotUI
---

# Class AgentSlotUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentSlotUI : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentSlotUI

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentSlotUI()

```csharp
public AgentSlotUI()
```

## Fields

### _currentAgent

```csharp
private AgentModel _currentAgent
```

#### Field Value

**Type:** Global.AgentModel

### _normalColor

```csharp
private Color _normalColor
```

#### Field Value

**Type:** UnityEngine.Color

### AgentName

```csharp
public Text AgentName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Grade

```csharp
public Image Grade
```

#### Field Value

**Type:** UnityEngine.UI.Image

### GradeText

```csharp
public Text GradeText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### graphics

```csharp
public List<MaskableGraphic> graphics
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### inverse

```csharp
public List<MaskableGraphic> inverse
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### normal

```csharp
public List<MaskableGraphic> normal
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### observeNotice

```csharp
private bool observeNotice
```

#### Field Value

**Type:** System.Boolean

### outline

```csharp
public Outline outline
```

#### Field Value

**Type:** UnityEngine.UI.Outline

### setter

```csharp
public WorkerPortraitSetter setter
```

#### Field Value

**Type:** Global.WorkerPortraitSetter

### standalone

```csharp
public List<MaskableGraphic> standalone
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

## Properties

### _inverseColor

```csharp
private Color _inverseColor { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### OutLineImage

```csharp
public MaskableGraphic OutLineImage { get; }
```

#### Property Value

**Type:** UnityEngine.UI.MaskableGraphic

## Methods

### DestroyNotice()

```csharp
public void DestroyNotice()
```

### EquipmentData(AgentModel)

```csharp
public void EquipmentData(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### InitNotice()

```csharp
public void InitNotice()
```

### InverseColor()

```csharp
public void InverseColor()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### SetColor()

```csharp
public void SetColor()
```

### SetColor(Color)

```csharp
public void SetColor(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### SetNormalColor(Color)

```csharp
public void SetNormalColor(Color normal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normal` | `UnityEngine.Color` |  |

### SetOutline(bool)

```csharp
public void SetOutline(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetPortrait(bool)

```csharp
public void SetPortrait(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SettingColor(Color, Color)

```csharp
public void SettingColor(Color normal, Color inverse)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normal` | `UnityEngine.Color` |  |
| `inverse` | `UnityEngine.Color` |  |

### SetUI(AgentModel)

```csharp
public void SetUI(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### UpdateData(AgentModel)

```csharp
public void UpdateData(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
