---
uid: Global.DayUnitButton.GraphicData
canonical_path: /api/Global/Misc/DayUnitButtonGraphicData
---

# Class DayUnitButton.GraphicData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DayUnitButton.GraphicData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DayUnitButton.GraphicData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GraphicData()

```csharp
public GraphicData()
```

## Fields

### disableColor

```csharp
public Color disableColor
```

#### Field Value

**Type:** UnityEngine.Color

### initialColor

```csharp
public Color initialColor
```

#### Field Value

**Type:** UnityEngine.Color

### targetGraphic

```csharp
public MaskableGraphic targetGraphic
```

#### Field Value

**Type:** UnityEngine.UI.MaskableGraphic

### transitionSave

```csharp
public Color transitionSave
```

#### Field Value

**Type:** UnityEngine.Color

## Methods

### LerpColor(Color, float)

```csharp
public void LerpColor(Color targetColor, float rate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetColor` | `UnityEngine.Color` |  |
| `rate` | `System.Single` |  |

### SetColor(Color)

```csharp
public void SetColor(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |
