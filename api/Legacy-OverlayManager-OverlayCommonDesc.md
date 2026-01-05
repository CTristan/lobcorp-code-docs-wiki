# Class OverlayManager.OverlayCommonDesc

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayCommonDesc
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayCommonDesc

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OverlayCommonDesc()

```csharp
public OverlayCommonDesc()
```

## Fields

### lib

```csharp
public Dictionary<string, OverlayManager.OverlayCommonDescElement> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,Legacy.OverlayManager.OverlayCommonDescElement}

## Methods

### AddElement(string, OverlayCommonDescElement)

```csharp
public void AddElement(string key, OverlayManager.OverlayCommonDescElement desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `desc` | `Legacy.OverlayManager.OverlayCommonDescElement` |  |

### GetData(string)

```csharp
public OverlayManager.OverlayCommonDescElement GetData(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Legacy.OverlayManager.OverlayCommonDescElement

### SetOverlayObject(OverlayObject, string)

```csharp
public void SetOverlayObject(OverlayObject target, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |

### SetOverlayObjectSimple(OverlayObject, string)

```csharp
public void SetOverlayObjectSimple(OverlayObject target, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |
| `key` | `System.String` |  |
