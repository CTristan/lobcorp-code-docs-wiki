# Class WorkerSpineAnimatorData

**Namespace:** [WorkerSpine](/api/WorkerSpine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpineAnimatorData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpineAnimatorData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerSpineAnimatorData()

```csharp
public WorkerSpineAnimatorData()
```

### WorkerSpineAnimatorData(int, string)

```csharp
public WorkerSpineAnimatorData(int id, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `name` | `System.String` |  |

### WorkerSpineAnimatorData(int, string, string, string)

```csharp
public WorkerSpineAnimatorData(int id, string name, string animatorSrc, string skeletonSrc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `name` | `System.String` |  |
| `animatorSrc` | `System.String` |  |
| `skeletonSrc` | `System.String` |  |

## Fields

### animator

```csharp
public RuntimeAnimatorController animator
```

#### Field Value

**Type:** UnityEngine.RuntimeAnimatorController

### animatorSrc

```csharp
public string animatorSrc
```

#### Field Value

**Type:** System.String

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### skeletonData

```csharp
public SkeletonDataAsset skeletonData
```

#### Field Value

**Type:** Spine.Unity.SkeletonDataAsset

### skeletonSrc

```csharp
public string skeletonSrc
```

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

### MakeDefault(RuntimeAnimatorController, SkeletonDataAsset)

```csharp
public static WorkerSpineAnimatorData MakeDefault(RuntimeAnimatorController animator, SkeletonDataAsset dataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.RuntimeAnimatorController` |  |
| `dataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** WorkerSpine.WorkerSpineAnimatorData
