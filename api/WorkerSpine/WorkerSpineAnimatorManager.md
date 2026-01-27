---
uid: WorkerSpine.WorkerSpineAnimatorManager
canonical_path: /api/WorkerSpine/WorkerSpineAnimatorManager
---

# Class WorkerSpineAnimatorManager

**Namespace:** [WorkerSpine](/api/WorkerSpine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpineAnimatorManager
```
For loading and getting spine animations?
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpineAnimatorManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpineAnimatorManager()

```csharp
public WorkerSpineAnimatorManager()
```

## Fields

### _instance

```csharp
private static WorkerSpineAnimatorManager _instance
```
#INC


#### Field Value

**Type:** WorkerSpine.WorkerSpineAnimatorManager

### _isLoaded

```csharp
private bool _isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### basicspecial

```csharp
public static WorkerSpineAnimatorData basicspecial
```

#### Field Value

**Type:** WorkerSpine.WorkerSpineAnimatorData

### idDic

```csharp
private Dictionary<int, WorkerSpineAnimatorData> idDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,WorkerSpine.WorkerSpineAnimatorData}

### nameDic

```csharp
private Dictionary<string, WorkerSpineAnimatorData> nameDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,WorkerSpine.WorkerSpineAnimatorData}

## Properties

### instance

```csharp
public static WorkerSpineAnimatorManager instance { get; }
```

#### Property Value

**Type:** WorkerSpine.WorkerSpineAnimatorManager

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ApplyDataSkel(SkeletonRenderer, string)

```csharp
public void ApplyDataSkel(SkeletonRenderer renderer, string Path)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderer` | `Spine.Unity.SkeletonRenderer` |  |
| `Path` | `System.String` |  |

### extractAgentAnimationData(List<WorkerSpineAnimatorData>)

```csharp
public void extractAgentAnimationData(List<WorkerSpineAnimatorData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSpine.WorkerSpineAnimatorData}` |  |

### extractCreatureData()

```csharp
public void extractCreatureData()
```

### FindNewSkinandSkel(WorkerSpineAnimatorData, Dictionary<string, object>, Dictionary<string, string>, Dictionary<string, object>, Dictionary<string, string>)

```csharp
public void FindNewSkinandSkel(WorkerSpineAnimatorData data, Dictionary<string, object> dic, Dictionary<string, string> dic2, Dictionary<string, object> dic_c, Dictionary<string, string> dic2_c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.WorkerSpineAnimatorData` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `dic2` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `dic_c` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `dic2_c` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |

### FindNewSkinandSkel(WorkerSpineAnimatorData, Dictionary<string, string>, Dictionary<string, string>, Dictionary<string, string>, Dictionary<string, string>)

```csharp
public void FindNewSkinandSkel(WorkerSpineAnimatorData data, Dictionary<string, string> dic, Dictionary<string, string> dic2, Dictionary<string, string> dic_c, Dictionary<string, string> dic2_c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.WorkerSpineAnimatorData` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `dic2` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `dic_c` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `dic2_c` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |

### FNSS_skel(WorkerSpineAnimatorData, byte[])

```csharp
public void FNSS_skel(WorkerSpineAnimatorData data, byte[] nskel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.WorkerSpineAnimatorData` |  |
| `nskel` | `System.Byte[]` |  |

### FNSS_skel(WorkerSpineAnimatorData, string)

```csharp
public void FNSS_skel(WorkerSpineAnimatorData data, string nskel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.WorkerSpineAnimatorData` |  |
| `nskel` | `System.String` |  |

### FNSS_skin(WorkerSpineAnimatorData, string)

```csharp
public void FNSS_skin(WorkerSpineAnimatorData data, string dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.WorkerSpineAnimatorData` |  |
| `dir` | `System.String` |  |

### GetClipInfo(WorkerSpineAnimatorData)

```csharp
public void GetClipInfo(WorkerSpineAnimatorData workerSpineAnimatorData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workerSpineAnimatorData` | `WorkerSpine.WorkerSpineAnimatorData` |  |

### GetData(int)

```csharp
public WorkerSpineAnimatorData GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSpine.WorkerSpineAnimatorData

### GetData(string)

```csharp
public WorkerSpineAnimatorData GetData(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** WorkerSpine.WorkerSpineAnimatorData

### GetDataWithCheck(int, out WorkerSpineAnimatorData)

```csharp
public bool GetDataWithCheck(int id, out WorkerSpineAnimatorData output)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `output` | `WorkerSpine.WorkerSpineAnimatorData` |  |

#### Returns

**Type:** System.Boolean

### GetDataWithCheck(string, out WorkerSpineAnimatorData)

```csharp
public bool GetDataWithCheck(string name, out WorkerSpineAnimatorData output)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `output` | `WorkerSpine.WorkerSpineAnimatorData` |  |

#### Returns

**Type:** System.Boolean

### Init(List<WorkerSpineAnimatorData>)

```csharp
public void Init(List<WorkerSpineAnimatorData> data)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSpine.WorkerSpineAnimatorData}` |  |

### OutPutSkeletonRenderer(CreatureTypeInfo, SkeletonRenderer)

```csharp
public void OutPutSkeletonRenderer(CreatureTypeInfo info, SkeletonRenderer renderer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.CreatureTypeInfo` |  |
| `renderer` | `Spine.Unity.SkeletonRenderer` |  |

### OutPutSkeletonRendererChild(CreatureTypeInfo, SkeletonRenderer)

```csharp
public void OutPutSkeletonRendererChild(CreatureTypeInfo info, SkeletonRenderer renderer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.CreatureTypeInfo` |  |
| `renderer` | `Spine.Unity.SkeletonRenderer` |  |
