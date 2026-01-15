---
uid: Legacy.OverlayManager.OverlayNormalDescElement
canonical_path: /api/Legacy/OverlayManager/OverlayNormalDescElement
---

# Class OverlayManager.OverlayNormalDescElement

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager.OverlayNormalDescElement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager.OverlayNormalDescElement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OverlayNormalDescElement(string, ElementData[])

```csharp
public OverlayNormalDescElement(string n, OverlayManager.OverlayNormalDescElement.ElementData[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `n` | `System.String` |  |
| `ary` | `Legacy.OverlayManager.OverlayNormalDescElement.ElementData[]` |  |

## Fields

### lib

```csharp
public Dictionary<string, OverlayManager.OverlayNormalDescElement.ElementData> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,Legacy.OverlayManager.OverlayNormalDescElement.ElementData}

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

## Methods

### AddElement(string, ElementData)

```csharp
private void AddElement(string key, OverlayManager.OverlayNormalDescElement.ElementData target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `target` | `Legacy.OverlayManager.OverlayNormalDescElement.ElementData` |  |

### GetNormalData(string)

```csharp
public OverlayManager.OverlayNormalDescElement.ElementData GetNormalData(string childKey)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `childKey` | `System.String` |  |

#### Returns

**Type:** Legacy.OverlayManager.OverlayNormalDescElement.ElementData
