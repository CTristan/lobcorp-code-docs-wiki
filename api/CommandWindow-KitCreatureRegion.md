# Class KitCreatureRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KitCreatureRegion : CommandWindowRegion
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow-CommandWindowRegion) → KitCreatureRegion

## Inherited Members
[ActiveControl](/api/CommandWindow-CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow-CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow-CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KitCreatureRegion()

```csharp
public KitCreatureRegion()
```

## Fields

### CodeNo

```csharp
public Text CodeNo
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ObserveLevelText

```csharp
public Text ObserveLevelText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ObserveLevelZeroImage

```csharp
public Image ObserveLevelZeroImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RiskLevel

```csharp
public Text RiskLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text

### UseCountText

```csharp
public Text UseCountText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### UseCountTitleText

```csharp
public Text UseCountTitleText
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### CurrentModel

```csharp
public CreatureModel CurrentModel { get; }
```

#### Property Value

**Type:** Global.CreatureModel

## Methods

### SetData(UnitModel)

```csharp
public override void SetData(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
