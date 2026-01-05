# Class ItemObjectManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ItemObjectManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ItemObjectManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ItemObjectManager()

```csharp
public ItemObjectManager()
```

## Fields

### dataList

```csharp
public List<ItemObjectData> dataList
```

#### Field Value

**Type:** System.Collections.Generic.List{ItemObjectData}

## Properties

### instance

```csharp
public static ItemObjectManager instance { get; }
```

#### Property Value

**Type:** Global.ItemObjectManager

### IsInit

```csharp
public bool IsInit { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public ItemObjectData GetData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.ItemObjectData

### Init(ItemObjectData[])

```csharp
public void Init(ItemObjectData[] data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.ItemObjectData[]` |  |

### Init(ReadOnlyCollection<ItemObjectData>)

```csharp
public void Init(ReadOnlyCollection<ItemObjectData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.ObjectModel.ReadOnlyCollection{ItemObjectData}` |  |
