# Class CreatureTypeInfo.CreatureDataList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureTypeInfo.CreatureDataList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureTypeInfo.CreatureDataList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureDataList()

```csharp
public CreatureDataList()
```

## Fields

### itemName

```csharp
public string itemName
```

#### Field Value

**Type:** System.String

## Methods

### AddData(CreatureData)

```csharp
public void AddData(CreatureTypeInfo.CreatureData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.CreatureTypeInfo.CreatureData` |  |

### GetAllData(ref List<object>, ref List<int>)

```csharp
public bool GetAllData(ref List<object> objects, ref List<int> levels)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `objects` | `System.Collections.Generic.List{System.Object}` |  |
| `levels` | `System.Collections.Generic.List{System.Int32}` |  |

#### Returns

**Type:** System.Boolean

### GetCount()

```csharp
public int GetCount()
```

#### Returns

**Type:** System.Int32

### GetData(int)

```csharp
public object GetData(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Object

### GetData<T>(int)

```csharp
public T GetData<T>(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** {T}

### GetDataTemp()

```csharp
public object GetDataTemp()
```

#### Returns

**Type:** System.Object

### GetLevel(int)

```csharp
public int GetLevel(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32
