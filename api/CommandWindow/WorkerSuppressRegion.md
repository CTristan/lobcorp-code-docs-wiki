---
uid: CommandWindow.WorkerSuppressRegion
canonical_path: /api/CommandWindow/WorkerSuppressRegion
---

# Class WorkerSuppressRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSuppressRegion : CommandWindowRegion
```

UI element for displaying the targeted [agent](/api/Global/Worker/AgentUnit) during agent suppression.

See [CommandWindow](/api/CommandWindow)

!


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow/CommandWindowRegion) → WorkerSuppressRegion

## Inherited Members
[ActiveControl](/api/CommandWindow/CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow/CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow/CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
public Text ArmorName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DefenseFactor

```csharp
public Text[] DefenseFactor
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseFill

```csharp
public Image[] DefenseFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image[]

### DefenseInner

```csharp
public Text[] DefenseInner
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseType

```csharp
public Text[] DefenseType
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### GradeImage

```csharp
public Image GradeImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### portrait

```csharp
public WorkerPortraitSetter portrait
```
#INC


#### Field Value

**Type:** Global.WorkerPortraitSetter

### Stat_B

```csharp
public AgentInfoWindow.StatObject Stat_B
```
#INC


#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_P

```csharp
public AgentInfoWindow.StatObject Stat_P
```
#INC


#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_R

```csharp
public AgentInfoWindow.StatObject Stat_R
```
#INC


#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Stat_W

```csharp
public AgentInfoWindow.StatObject Stat_W
```
#INC


#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### Title

```csharp
public Text Title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Weapon

```csharp
public AgentInfoWindow.StatObject Weapon
```
#INC


#### Field Value

**Type:** Global.AgentInfoWindow.StatObject

### WeaponGrade

```csharp
public Text WeaponGrade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetData(UnitModel)

```csharp
public override void SetData(UnitModel target)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SetData(WorkerModel)

```csharp
public void SetData(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
