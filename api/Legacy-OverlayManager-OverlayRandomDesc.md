# Class OverlayManager.OverlayRandomDesc

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayRandomDesc
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayRandomDesc

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OverlayRandomDesc()

```csharp
public OverlayRandomDesc()
```

## Fields

### lib

```csharp
public Dictionary<string, OverlayManager.OverlayRandomDescElement> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,Legacy.OverlayManager.OverlayRandomDescElement}

## Methods

### AddElement(string, OverlayRandomDescElement)

```csharp
public void AddElement(string key, OverlayManager.OverlayRandomDescElement element)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `element` | `Legacy.OverlayManager.OverlayRandomDescElement` |  |

### GetData(string)

```csharp
public OverlayManager.OverlayRandomDescElement GetData(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Legacy.OverlayManager.OverlayRandomDescElement

### SetOverlayObject(OverlayObject, string)

```csharp
public void SetOverlayObject(OverlayObject target, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |

### SetOverlayObject(OverlayObject, string, int)

```csharp
public void SetOverlayObject(OverlayObject target, string key, int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |
| `index` | `System.Int32` |  |
