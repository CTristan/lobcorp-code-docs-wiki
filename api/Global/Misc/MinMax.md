---
uid: Global.MinMax
canonical_path: /api/Global/Misc/MinMax
---

# Class MinMax

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MinMax
```
Holds a minimum and maximum, and provides some methods to use them.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MinMax

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MinMax(float, float)

```csharp
public MinMax(float min, float max)
```
Constructs a MinMax with minimum `min` and maximum `max`.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |

## Fields

### max

```csharp
public float max
```

#### Field Value

**Type:** System.Single

### min

```csharp
public float min
```

#### Field Value

**Type:** System.Single

## Methods

### GetLerp(float)

```csharp
public float GetLerp(float rate)
```
Gets the linear interpolation between `min` and `max` at the value of `rate`.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetMedian()

```csharp
public float GetMedian()
```
Gets the average of `min` and `max`.


#### Returns

**Type:** System.Single

### GetRandomFloat()

```csharp
public float GetRandomFloat()
```
Produces a random float between `min` and `max`.


#### Returns

**Type:** System.Single

### GetRandomInt()

```csharp
public int GetRandomInt()
```
Produces a random integer between `min` and `max`.


#### Returns

**Type:** System.Int32
