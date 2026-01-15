---
uid: Global.AgentInfoWindow.UIComponent
canonical_path: /api/Global/Misc/AgentInfoWindowUIComponent
---

# Class AgentInfoWindow.UIComponent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentInfoWindow.UIComponent
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentInfoWindow.UIComponent

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UIComponent()

```csharp
public UIComponent()
```

## Fields

### AgentName

```csharp
public Text AgentName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### AgentTitle

```csharp
public Text AgentTitle
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ArmorGrade

```csharp
public Text ArmorGrade
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ArmorName

```csharp
public Text ArmorName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Colored_B

```csharp
public List<MaskableGraphic> Colored_B
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### Colored_P

```csharp
public List<MaskableGraphic> Colored_P
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### Colored_R

```csharp
public List<MaskableGraphic> Colored_R
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### Colored_W

```csharp
public List<MaskableGraphic> Colored_W
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### DefenseFill

```csharp
public Image[] DefenseFill
```

#### Field Value

**Type:** UnityEngine.UI.Image[]

### DefenseInner

```csharp
public Text[] DefenseInner
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseTooltips

```csharp
public TooltipMouseOver[] DefenseTooltips
```

#### Field Value

**Type:** Global.TooltipMouseOver[]

### DefenseType

```csharp
public Text[] DefenseType
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseTypeRenderer

```csharp
public Image[] DefenseTypeRenderer
```

#### Field Value

**Type:** UnityEngine.UI.Image[]

### GradeImage

```csharp
public Image GradeImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### portrait

```csharp
public WorkerPortraitSetter portrait
```

#### Field Value

**Type:** Global.WorkerPortraitSetter

### Stat_B

```csharp
public AgentInfoWindow.StatObject Stat_B
```

#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_P

```csharp
public AgentInfoWindow.StatObject Stat_P
```

#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_R

```csharp
public AgentInfoWindow.StatObject Stat_R
```

#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_W

```csharp
public AgentInfoWindow.StatObject Stat_W
```

#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### StatTooltips

```csharp
public TooltipMouseOver[] StatTooltips
```

#### Field Value

**Type:** Global.TooltipMouseOver[]

### Weapon

```csharp
public AgentInfoWindow.StatObject Weapon
```

#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### WeaponGrade

```csharp
public Text WeaponGrade
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### GetDefenseTypeText(DefenseInfo, RwbpType)

```csharp
private string GetDefenseTypeText(DefenseInfo def, RwbpType t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `def` | `Global.DefenseInfo` |  |
| `t` | `Global.RwbpType` |  |

#### Returns

**Type:** System.String

### SetColorData()

```csharp
public void SetColorData()
```

### SetData(AgentData)

```csharp
public void SetData(AgentData agentData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agentData` | `Customizing.AgentData` |  |

### SetData(AgentModel)

```csharp
public void SetData(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Start()

```csharp
public void Start()
```
