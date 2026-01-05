# Class MapObjectTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapObjectTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapObjectTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static MapObjectTypeList instance { get; }
```

#### Property Value

**Type:** Global.MapObjectTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public MapObjectTypeInfo GetData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.MapObjectTypeInfo

### GetList()

```csharp
public MapObjectTypeInfo[] GetList()
```

#### Returns

**Type:** Global.MapObjectTypeInfo[]

### Init(MapObjectTypeInfo[])

```csharp
public void Init(MapObjectTypeInfo[] list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.MapObjectTypeInfo[]` |  |
