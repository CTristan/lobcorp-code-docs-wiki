---
uid: Legacy.OverlayManager.OverlayRandomDescElement
canonical_path: /api/Legacy/OverlayManager/OverlayRandomDescElement
---

# Class OverlayManager.OverlayRandomDescElement

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayRandomDescElement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayRandomDescElement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OverlayRandomDescElement(string, string[])

```csharp
public OverlayRandomDescElement(string level, string[] randomDesc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.String` |  |
| `randomDesc` | `System.String[]` |  |

## Fields

### description

```csharp
private List<string> description
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### levelString

```csharp
public string levelString
```

#### Field Value

**Type:** System.String

## Properties

### Length

```csharp
public int Length { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetDesc(int)

```csharp
public string GetDesc(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetRandomDescIndex()

```csharp
public int GetRandomDescIndex()
```

#### Returns

**Type:** System.Int32
