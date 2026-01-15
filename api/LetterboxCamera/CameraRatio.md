---
uid: LetterboxCamera.CameraRatio
canonical_path: /api/LetterboxCamera/CameraRatio
---

# Class CameraRatio

**Namespace:** [LetterboxCamera](/api/LetterboxCamera)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CameraRatio
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CameraRatio

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CameraRatio(Camera, Vector2)

```csharp
public CameraRatio(Camera _camera, Vector2 _anchor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_camera` | `UnityEngine.Camera` |  |
| `_anchor` | `UnityEngine.Vector2` |  |

## Fields

### anchor

```csharp
[Tooltip("When a Camera Viewport is shrunk to fit a ratio, it will anchor the new Viewport Rectangle at the given point (relative to the original, unshrunk Viewport)")]
public CameraRatio.CameraAnchor anchor
```

#### Field Value

**Type:** LetterboxCamera.CameraRatio.CameraAnchor

### camera

```csharp
[Tooltip("The Camera assigned to have an automatically calculated Viewport Ratio")]
public Camera camera
```

#### Field Value

**Type:** UnityEngine.Camera

### originViewPort

```csharp
private Rect originViewPort
```

#### Field Value

**Type:** UnityEngine.Rect

### vectorAnchor

```csharp
[HideInInspector]
public Vector2 vectorAnchor
```

#### Field Value

**Type:** UnityEngine.Vector2

## Methods

### CalculateAndSetCameraRatio(float, float, bool)

```csharp
public void CalculateAndSetCameraRatio(float _width, float _height, bool _horizontalLetterbox)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_width` | `System.Single` |  |
| `_height` | `System.Single` |  |
| `_horizontalLetterbox` | `System.Boolean` |  |

### ResetOriginViewport()

```csharp
public void ResetOriginViewport()
```

### SetAnchorBasedOnEnum(CameraAnchor)

```csharp
public void SetAnchorBasedOnEnum(CameraRatio.CameraAnchor _anchor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_anchor` | `LetterboxCamera.CameraRatio.CameraAnchor` |  |
