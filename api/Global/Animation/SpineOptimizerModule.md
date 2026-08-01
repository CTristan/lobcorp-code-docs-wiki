---
title: SpineOptimizerModule
description: 
published: true
date: 2026-08-01T00:05:45.404Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:02:14.049Z
---

# Class SpineOptimizerModule
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpineOptimizerModule
```
> This section may have incomplete or incorrect information.
{.is-warning}

Keeps track of whether this animated thing is in the camera, and sets the optimization level of the renderer depending on how big it is in the screen.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpineOptimizerModule

## Constructors
### SpineOptimizerModule(SkeletonRenderer, UnitModel, float)
```csharp
public SpineOptimizerModule(SkeletonRenderer spineRenderer, UnitModel target, float loosenessLevel = 1)
```
Initializes with the given `spineRenderer`, `target`, and `loosenessLevel`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` | The Spine SkeletonRenderer to optimize. |
| `target` | `Global.UnitModel` | The `UnitModel` target that the SkeletonRenderer belongs to. |
| `loosenessLevel` | `System.Single` | Higher values mean only optimized at higher zoom levels; only used by [Violet Noon](/api/Global/Abnormalities/Ordeals/Violet-Ordeals/Violet-Noon/OutterGodNoon) (`1.2f`) and [Today's Shy Look](/api/Global/Abnormalities/Today's-Shy-Look/ShyThing) (`2f`). Default `1f`. |

## Fields
### \_inCamera
```csharp
private bool _inCamera
```
Flag indicating if the unit is in the camera.

Due to the implementation, it actually calculates an area roughly twice the size of the camera's actual view.

#### Field Value
**Type:** System.Boolean

### \_loosenessLevel
```csharp
private float _loosenessLevel
```
Value which affects the zoom level at which this unit is optimized. Higher values mean a greater zoom level is required.

Only changed by [Violet Noon](/api/Global/Abnormalities/Ordeals/Violet-Ordeals/Violet-Noon/OutterGodNoon) (`1.2f`) and [Today's Shy Look](/api/Global/Abnormalities/Today's-Shy-Look/ShyThing) (`2f`).

#### Field Value
**Type:** System.Single

### \_spineRenderer
```csharp
private SkeletonRenderer _spineRenderer
```
The Spine SkeletonRenderer to optimize.

#### Field Value
**Type:** Spine.Unity.SkeletonRenderer

### \_targetModel
```csharp
private UnitModel _targetModel
```
The unit that the SkeletonRenderer belongs to.

#### Field Value
**Type:** Global.UnitModel

## Methods
### Init(SkeletonRenderer, UnitModel, float)
```csharp
public void Init(SkeletonRenderer spineRenderer, UnitModel target, float scale = 1)
```
Initializes this `SpineOptimizerModule` with the given SkeletonRenderer, unit, and looseness level. Only used by the constructor.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` | The Spine SkeletonRenderer to optimize. |
| `target` | `Global.UnitModel` | The `UnitModel` target that the SkeletonRenderer belongs to. |
| `scale` | `System.Single` | Higher values mean only optimized at higher zoom levels; only used by [Violet Noon](/api/Global/Abnormalities/Ordeals/Violet-Ordeals/Violet-Noon/OutterGodNoon) (`1.2f`) and [Today's Shy Look](/api/Global/Abnormalities/Today's-Shy-Look/ShyThing) (`2f`). Default `1f`. |

### Update()
```csharp
public void Update()
```
Updates whether the unit is in the camera and should be optimized each frame.

### UpdateAnimationQuality()
```csharp
public void UpdateAnimationQuality()
```
If the SpineRenderer and unit both exist, changes the optimization level of the renderer.

If the day has ended or the unit is not in the camera, sets the optimization level to the highest value (`5`).

Otherwise, calculates the effective size of the unit $\frac{(cameraOrthoSize)}{ (unit CurrentScale)\cdot loosenessLevel)}$, where:
- $cameraOrthoSize$ is the `orthographicSize` of the main camera;
- $unitCurrentScale$ is the scale factor of the room `target` is in;
- $loosenessLevel$ is `_loosenessLevel`.

Then sets the `optimizeLevel` of the renderer as follows:

| Effective Size | optimizeLevel |
| --- | --- |
| $>80$ | 4 |
| $>50$ | 3 |
| $>30$ | 2 |
| $>25$ | 1 |
| $\leq 25$ | 0 |


### UpdateCheckInCamera()
```csharp
public void UpdateCheckInCamera()
```
Updates whether the SkeletonRenderer is in the camera.

Calculates the difference of the current position of the unit and the camera.

If the difference both:
- has an `x` value with absolute value less than $orthographicSize + 1.5$, where $orthographicSize$ is the main camera's `orthographicSize`;
- has a `y` value with absolute value less than $orthographicSize\cdot aspect + 1.5$, where $orthographicSize$ is the main camera's `orthographicSize` and `aspect` is its aspect ratio (width divided by height);

sets the flag to true.

Effectively, this calculates if the unit is in a rectangular box :question: twice the size of the camera (both values above should be halved!).

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









