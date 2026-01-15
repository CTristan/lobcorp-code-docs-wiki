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

#### Field Value

**Type:** System.Int32

### _duskAdditionDay

```csharp
public static int _duskAdditionDay
```

#### Field Value

**Type:** System.Int32

### _endingDay

```csharp
public static int _endingDay
```

#### Field Value

**Type:** System.Int32

### _fixerAddtionDay

```csharp
public static int _fixerAddtionDay
```

#### Field Value

**Type:** System.Int32

### _midnightAdditionDay

```csharp
public static int _midnightAdditionDay
```

#### Field Value

**Type:** System.Int32

### _noonAdditionDay

```csharp
public static int _noonAdditionDay
```

#### Field Value

**Type:** System.Int32

### _scanvengerAttidionDay

```csharp
public static int _scanvengerAttidionDay
```

#### Field Value

**Type:** System.Int32

## Methods

### CreateFixerOrdeal(OrdealLevel)

```csharp
private static OrdealBase CreateFixerOrdeal(OrdealLevel level)
```

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

#### Returns

**Type:** Global.OrdealBase

### CreateRandomDusk()

```csharp
private static OrdealBase CreateRandomDusk()
```

#### Returns

**Type:** Global.OrdealBase

### CreateRandomMidnight()

```csharp
private static OrdealBase CreateRandomMidnight()
```

#### Returns

**Type:** Global.OrdealBase

### CreateRandomNoon(int)

```csharp
private static OrdealBase CreateRandomNoon(int day)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{OrdealBase}
