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

#### Field Value

**Type:** Global.CreatureModel

### CodeNo

```csharp
public Text CodeNo
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DefenseFactor

```csharp
public Text[] DefenseFactor
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### DefenseType

```csharp
public Text[] DefenseType
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### Name

```csharp
public Text Name
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Portrait

```csharp
public Image Portrait
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RiskLevel

```csharp
public Text RiskLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text

### RWBPAttackType

```csharp
public GameObject[] RWBPAttackType
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### unk

```csharp
private const string unk = "?"
```

#### Field Value

**Type:** System.String

### Unknown

```csharp
private const string Unknown = "Unknown"
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{DefenseInfo}` |  |

### SetData(UnitModel)

```csharp
public override void SetData(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SetOrdealData(OrdealCreatureModel)

```csharp
private void SetOrdealData(OrdealCreatureModel ordeal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |
