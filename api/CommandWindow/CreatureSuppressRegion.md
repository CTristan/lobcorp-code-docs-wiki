---
uid: CommandWindow.CreatureSuppressRegion
canonical_path: /api/CommandWindow/CreatureSuppressRegion
---

# Class CreatureSuppressRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSuppressRegion : CommandWindowRegion
```

Displays an [abnormality](/api/Global/Model/CreatureModel), its attack information, and its [defenses](/api/Global/Info/DefenseInfo) in the suppression UI.

See [CommandWindow](/api/CommandWindow)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow/CommandWindowRegion) → CreatureSuppressRegion

## Inherited Members
[ActiveControl](/api/CommandWindow/CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow/CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow/CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSuppressRegion()

```csharp
public CreatureSuppressRegion()
```

## Fields

### _currentModel

```csharp
private CreatureModel _currentModel
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### CodeNo

```csharp
public Text CodeNo
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

### DefenseType

```csharp
public Text[] DefenseType
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### Name

```csharp
public Text Name
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Portrait

```csharp
public Image Portrait
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### RiskLevel

```csharp
public Text RiskLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### RWBPAttackType

```csharp
public GameObject[] RWBPAttackType
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### unk

```csharp
private const string unk = "?"
```
#INC


#### Field Value

**Type:** System.String

### Unknown

```csharp
private const string Unknown = "Unknown"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### CurrentModel

```csharp
public CreatureModel CurrentModel { get; }
```

#### Property Value

**Type:** Global.CreatureModel

## Methods

### CalculateMultipleType(List<DefenseInfo>)

```csharp
private void CalculateMultipleType(List<DefenseInfo> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{DefenseInfo}` |  |

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

### SetOrdealData(OrdealCreatureModel)

```csharp
private void SetOrdealData(OrdealCreatureModel ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |
