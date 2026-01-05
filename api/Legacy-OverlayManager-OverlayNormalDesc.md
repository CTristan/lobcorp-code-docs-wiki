# Class OverlayManager.OverlayNormalDesc

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayNormalDesc
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayNormalDesc

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OverlayNormalDesc()

```csharp
public OverlayNormalDesc()
```

## Fields

### lib

```csharp
public Dictionary<string, OverlayManager.OverlayNormalDescElement> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,Legacy.OverlayManager.OverlayNormalDescElement}

## Methods

### AddElement(string, OverlayNormalDescElement)

```csharp
public void AddElement(string key, OverlayManager.OverlayNormalDescElement desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `desc` | `Legacy.OverlayManager.OverlayNormalDescElement` |  |

### GetData(string)

```csharp
public OverlayManager.OverlayNormalDescElement GetData(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Legacy.OverlayManager.OverlayNormalDescElement

### SetOverlayObject(OverlayObject, string, string)

```csharp
public void SetOverlayObject(OverlayObject target, string key, string childKey)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |
| `childKey` | `System.String` |  |

### SetOverlayObject(OverlayObject, string, string, bool)

```csharp
public void SetOverlayObject(OverlayObject target, string key, string childKey, bool hasDetail)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |
| `childKey` | `System.String` |  |
| `hasDetail` | `System.Boolean` |  |
