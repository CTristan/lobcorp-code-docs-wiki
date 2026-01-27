---
uid: Global.OrdealGenInfo
canonical_path: /api/Global/Info/OrdealGenInfo
---

# Class OrdealGenInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OrdealGenInfo
```
Contains information about when each level of ordeal, as well as certain special ordeals, become available.

Provides several methods for generating a random ordeal.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OrdealGenInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OrdealGenInfo()

```csharp
public OrdealGenInfo()
```

## Fields

### _dawnAdditionDay

```csharp
public static int _dawnAdditionDay
```
#INC


#### Field Value

**Type:** System.Int32

### _duskAdditionDay

```csharp
public static int _duskAdditionDay
```
#INC


#### Field Value

**Type:** System.Int32

### _endingDay

```csharp
public static int _endingDay
```
#INC


#### Field Value

**Type:** System.Int32

### _fixerAddtionDay

```csharp
public static int _fixerAddtionDay
```
#INC


#### Field Value

**Type:** System.Int32

### _midnightAdditionDay

```csharp
public static int _midnightAdditionDay
```
#INC


#### Field Value

**Type:** System.Int32

### _noonAdditionDay

```csharp
public static int _noonAdditionDay
```
#INC


#### Field Value

**Type:** System.Int32

### _scanvengerAttidionDay

```csharp
public static int _scanvengerAttidionDay
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### CreateFixerOrdeal(OrdealLevel)

```csharp
private static OrdealBase CreateFixerOrdeal(OrdealLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

#### Returns

**Type:** Global.OrdealBase

### CreateRandomDawn()

```csharp
private static OrdealBase CreateRandomDawn()
```
#INC
#code-generated


#### Returns

**Type:** Global.OrdealBase

### CreateRandomDusk()

```csharp
private static OrdealBase CreateRandomDusk()
```
#INC


#### Returns

**Type:** Global.OrdealBase

### CreateRandomMidnight()

```csharp
private static OrdealBase CreateRandomMidnight()
```
#INC


#### Returns

**Type:** Global.OrdealBase

### CreateRandomNoon(int)

```csharp
private static OrdealBase CreateRandomNoon(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** Global.OrdealBase

### GenerateOrdeals(int)

```csharp
public static List<OrdealBase> GenerateOrdeals(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{OrdealBase}
