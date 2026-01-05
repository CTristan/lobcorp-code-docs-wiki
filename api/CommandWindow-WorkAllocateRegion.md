# Class WorkAllocateRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkAllocateRegion : CommandWindowRegion
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow-CommandWindowRegion) → WorkAllocateRegion

## Inherited Members
[ActiveControl](/api/CommandWindow-CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow-CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow-CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkAllocateRegion()

```csharp
public WorkAllocateRegion()
```

## Fields

### CodeNo

```csharp
public Text CodeNo
```

#### Field Value

**Type:** UnityEngine.UI.Text

### listParent

```csharp
public RectTransform listParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### MaximumCubeGenerate

```csharp
public Text MaximumCubeGenerate
```

#### Field Value

**Type:** UnityEngine.UI.Text

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

### slots

```csharp
public List<CreatureInfoStatFeelingStateSlot> slots
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureInfo.CreatureInfoStatFeelingStateSlot}

### WorkDamageFill

```csharp
public Image WorkDamageFill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### WorkDamageRange

```csharp
public Text WorkDamageRange
```

#### Field Value

**Type:** UnityEngine.UI.Text

### WorkDamageType

```csharp
public Text WorkDamageType
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
