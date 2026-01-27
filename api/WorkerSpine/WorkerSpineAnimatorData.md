---
uid: WorkerSpine.WorkerSpineAnimatorData
canonical_path: /api/WorkerSpine/WorkerSpineAnimatorData
---

# Class WorkerSpineAnimatorData

**Namespace:** [WorkerSpine](/api/WorkerSpine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpineAnimatorData
```
stores an animation source, and loads it?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpineAnimatorData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpineAnimatorData()

```csharp
public WorkerSpineAnimatorData()
```
#INC
#code-generated


### WorkerSpineAnimatorData(int, string)

```csharp
public WorkerSpineAnimatorData(int id, string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `name` | `System.String` |  |

### WorkerSpineAnimatorData(int, string, string, string)

```csharp
public WorkerSpineAnimatorData(int id, string name, string animatorSrc, string skeletonSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `name` | `System.String` |  |
| `animatorSrc` | `System.String` |  |
| `skeletonSrc` | `System.String` |  |

## Fields

### _isLoaded

```csharp
private bool _isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### animator

```csharp
public RuntimeAnimatorController animator
```
#INC


#### Field Value

**Type:** UnityEngine.RuntimeAnimatorController

### animatorSrc

```csharp
public string animatorSrc
```
#INC


#### Field Value

**Type:** System.String

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### skeletonData

```csharp
public SkeletonDataAsset skeletonData
```
#INC


#### Field Value

**Type:** Spine.Unity.SkeletonDataAsset

### skeletonSrc

```csharp
public string skeletonSrc
```
#INC


#### Field Value

**Type:** System.String

## Properties

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### LoadData()

```csharp
public void LoadData()
```
#INC


### MakeDefault(RuntimeAnimatorController, SkeletonDataAsset)

```csharp
public static WorkerSpineAnimatorData MakeDefault(RuntimeAnimatorController animator, SkeletonDataAsset dataAsset)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.RuntimeAnimatorController` |  |
| `dataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** WorkerSpine.WorkerSpineAnimatorData
