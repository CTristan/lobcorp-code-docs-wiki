# Class PanicDataList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicDataList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PanicDataList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PanicDataList()

```csharp
public PanicDataList()
```

## Properties

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
