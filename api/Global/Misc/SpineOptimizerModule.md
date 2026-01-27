---
uid: Global.SpineOptimizerModule
canonical_path: /api/Global/Misc/SpineOptimizerModule
---

# Class SpineOptimizerModule

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpineOptimizerModule
```
Keeps track of whether this animated thing is in the camera, and sets the optimization level of the renderer depending on how big this is in the screen.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpineOptimizerModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpineOptimizerModule(SkeletonRenderer, UnitModel, float)

```csharp
public SpineOptimizerModule(SkeletonRenderer spineRenderer, UnitModel target, float loosenessLevel = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` |  |
| `target` | `Global.UnitModel` |  |
| `loosenessLevel` | `System.Single` |  |

## Fields

### _inCamera

```csharp
private bool _inCamera
```
#INC


#### Field Value

**Type:** System.Boolean

### _loosenessLevel

```csharp
private float _loosenessLevel
```
#INC


#### Field Value

**Type:** System.Single

### _spineRenderer

```csharp
private SkeletonRenderer _spineRenderer
```
#INC


#### Field Value

**Type:** Spine.Unity.SkeletonRenderer

### _targetModel

```csharp
private UnitModel _targetModel
```
#INC


#### Field Value

**Type:** Global.UnitModel

## Methods

### Init(SkeletonRenderer, UnitModel, float)

```csharp
public void Init(SkeletonRenderer spineRenderer, UnitModel target, float scale = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` |  |
| `target` | `Global.UnitModel` |  |
| `scale` | `System.Single` |  |

### Update()

```csharp
public void Update()
```
#INC


### UpdateAnimationQuality()

```csharp
public void UpdateAnimationQuality()
```
#INC


### UpdateCheckInCamera()

```csharp
public void UpdateCheckInCamera()
```
#INC

