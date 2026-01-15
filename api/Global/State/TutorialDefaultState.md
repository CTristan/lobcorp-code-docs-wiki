---
uid: Global.Tutorial.DefaultState
canonical_path: /api/Global/State/TutorialDefaultState
---

# Class Tutorial.DefaultState

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class Tutorial.DefaultState
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Tutorial.DefaultState

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DefaultState(Canvas, bool, bool)

```csharp
public DefaultState(Canvas canvas, bool isHighLight, bool isParent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `canvas` | `UnityEngine.Canvas` |  |
| `isHighLight` | `System.Boolean` |  |
| `isParent` | `System.Boolean` |  |

## Fields

### canvas

```csharp
private Canvas canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### defaultLayer

```csharp
private string defaultLayer
```

#### Field Value

**Type:** System.String

### defaultOrder

```csharp
private int defaultOrder
```

#### Field Value

**Type:** System.Int32

## Properties

### Canvas

```csharp
public Canvas Canvas { get; }
```

#### Property Value

**Type:** UnityEngine.Canvas

## Methods

### BackToDefault()

```csharp
public void BackToDefault()
```

### SaveDefaultState(bool, bool)

```csharp
private void SaveDefaultState(bool isHighLight, bool isParent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isHighLight` | `System.Boolean` |  |
| `isParent` | `System.Boolean` |  |
