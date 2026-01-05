# Class OverlayManager.OverlayRandomDescElement

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayRandomDescElement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayRandomDescElement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
