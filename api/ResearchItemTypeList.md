# Class ResearchItemTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static ResearchItemTypeList instance { get; }
```

#### Property Value

**Type:** Global.ResearchItemTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public ResearchItemTypeInfo GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ResearchItemTypeInfo

### GetDataBySefira(string)

```csharp
public List<ResearchItemTypeInfo> GetDataBySefira(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemTypeInfo}

### GetList()

```csharp
public ReadOnlyCollection<ResearchItemTypeInfo> GetList()
```

#### Returns

**Type:** System.Collections.ObjectModel.ReadOnlyCollection{ResearchItemTypeInfo}

### Init(ReadOnlyCollection<ResearchItemTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<ResearchItemTypeInfo> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.ObjectModel.ReadOnlyCollection{ResearchItemTypeInfo}` |  |
