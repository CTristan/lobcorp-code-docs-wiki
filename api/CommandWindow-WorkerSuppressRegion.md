# Class WorkerSuppressRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSuppressRegion : CommandWindowRegion
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow-CommandWindowRegion) → WorkerSuppressRegion

## Inherited Members
[ActiveControl](/api/CommandWindow-CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow-CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow-CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerSuppressRegion()

```csharp
public WorkerSuppressRegion()
```

## Fields

### AgentName

```csharp
public Text AgentName
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

### DefenseFactor

```csharp
public Text[] DefenseFactor
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

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

### Title

```csharp
public Text Title
```

#### Field Value

**Type:** UnityEngine.UI.Text

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

### SetData(UnitModel)

```csharp
public override void SetData(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SetData(WorkerModel)

```csharp
public void SetData(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
