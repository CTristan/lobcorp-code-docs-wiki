---
uid: Global.AgentInfoWindow.InGameModeComponent
canonical_path: /api/Global/Misc/AgentInfoWindowInGameModeComponent
---

# Class AgentInfoWindow.InGameModeComponent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentInfoWindow.InGameModeComponent
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentInfoWindow.InGameModeComponent

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InGameModeComponent()

```csharp
public InGameModeComponent()
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
[Header("Armor")]
public Text ArmorName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DefenseIcon

```csharp
public Image[] DefenseIcon
```

#### Field Value

**Type:** UnityEngine.UI.Image[]

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

### StatTooltips

```csharp
public TooltipMouseOver[] StatTooltips
```

#### Field Value

**Type:** Global.TooltipMouseOver[]

### statUI

```csharp
[Header("Stat")]
public AgentInfoWindow.WorkerPrimaryStatUI[] statUI
```

#### Field Value

**Type:** Global.AgentInfoWindow.WorkerPrimaryStatUI[]

### Weapon

```csharp
[Header("Weapon")]
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
public string GetDefenseTypeText(DefenseInfo def, RwbpType t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `def` | `Global.DefenseInfo` |  |
| `t` | `Global.RwbpType` |  |

#### Returns

**Type:** System.String

### SetUI(AgentModel)

```csharp
public void SetUI(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
