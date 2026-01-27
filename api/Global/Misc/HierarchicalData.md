---
uid: Global.HierarchicalData
canonical_path: /api/Global/Misc/HierarchicalData
---

# Class HierarchicalData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HierarchicalData
```
Theoretically, a class for having a list of 'priority' things; the only use case would be for prioritizing certain [uncontrollable actions](/api/Global/Action/UncontrollableAction). This property does not appear to be used, but uncontrollable actions still derive from this class...

#called-unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → HierarchicalData

## Derived
[UncontrollableAction](/api/Global/Action/UncontrollableAction)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.String

### InitialSetting()

```csharp
public void InitialSetting()
```
#INC
#code-generated


### isUpperHierarchy(HierarchicalData)

```csharp
public bool isUpperHierarchy(HierarchicalData compared)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |
