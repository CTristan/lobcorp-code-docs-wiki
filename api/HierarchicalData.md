# Class HierarchicalData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HierarchicalData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → HierarchicalData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### HierarchicalData()

```csharp
public HierarchicalData()
```

## Fields

### _H_index

```csharp
protected int _H_index
```

#### Field Value

**Type:** System.Int32

## Properties

### HierachicalIndex

```csharp
public int HierachicalIndex { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Comparer(HierarchicalData)

```csharp
public int Comparer(HierarchicalData compared)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `compared` | `Global.HierarchicalData` |  |

#### Returns

**Type:** System.Int32

### Comparer(HierarchicalData, HierarchicalData)

```csharp
public static int Comparer(HierarchicalData a, HierarchicalData b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.HierarchicalData` |  |
| `b` | `Global.HierarchicalData` |  |

#### Returns

**Type:** System.Int32

### GetHierachicalName()

```csharp
public string GetHierachicalName()
```

#### Returns

**Type:** System.String

### InitialSetting()

```csharp
public void InitialSetting()
```

### isUpperHierarchy(HierarchicalData)

```csharp
public bool isUpperHierarchy(HierarchicalData compared)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `compared` | `Global.HierarchicalData` |  |

#### Returns

**Type:** System.Boolean

### SetHierarchicalIndex(int)

```csharp
public virtual void SetHierarchicalIndex(int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |
