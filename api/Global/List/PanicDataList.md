---
uid: Global.PanicDataList
canonical_path: /api/Global/List/PanicDataList
---

# Class PanicDataList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicDataList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PanicDataList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicDataList()

```csharp
public PanicDataList()
```

## Fields

### _instance

```csharp
private static PanicDataList _instance
```

#### Field Value

**Type:** Global.PanicDataList

### isLoaded

```csharp
private bool isLoaded
```

#### Field Value

**Type:** System.Boolean

### list

```csharp
private List<PanicData> list
```

#### Field Value

**Type:** System.Collections.Generic.List{PanicData}

## Properties

### count

```csharp
private int count { get; }
```

#### Property Value

**Type:** System.Int32

### instance

```csharp
public static PanicDataList instance { get; }
```

#### Property Value

**Type:** Global.PanicDataList

## Methods

### GetPanicData(int)

```csharp
public PanicData GetPanicData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.PanicData

### GetPanicData(string)

```csharp
public PanicData GetPanicData(string lifeStyle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lifeStyle` | `System.String` |  |

#### Returns

**Type:** Global.PanicData

### GetPanicData(WorkerModel)

```csharp
public PanicData GetPanicData(WorkerModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |

#### Returns

**Type:** Global.PanicData

### GetRandomPanicData(string)

```csharp
public PanicData GetRandomPanicData(string lifeStyle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lifeStyle` | `System.String` |  |

#### Returns

**Type:** Global.PanicData

### Init(PanicData[])

```csharp
public void Init(PanicData[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.PanicData[]` |  |

### IsLoaded()

```csharp
public bool IsLoaded()
```

#### Returns

**Type:** System.Boolean
