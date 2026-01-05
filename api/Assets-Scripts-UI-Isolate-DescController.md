# Class DescController

**Namespace:** Assets . Scripts . UI . [Isolate](/api/Assets-Scripts-UI-Isolate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DescController
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DescController

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DescController()

```csharp
public DescController()
```

## Fields

### descList

```csharp
public List<IsolateDescription> descList
```

#### Field Value

**Type:** System.Collections.Generic.List{Assets.Scripts.UI.Isolate.IsolateDescription}

### maxmimumFont

```csharp
public int maxmimumFont
```

#### Field Value

**Type:** System.Int32

### minimumFont

```csharp
public int minimumFont
```

#### Field Value

**Type:** System.Int32

### minimumSpacing

```csharp
public float minimumSpacing
```

#### Field Value

**Type:** System.Single

### pivot

```csharp
public RectTransform pivot
```

#### Field Value

**Type:** UnityEngine.RectTransform

## Properties

### IsAvailable

```csharp
public bool IsAvailable { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Init(IsolateDescController)

```csharp
public void Init(IsolateDescController ctrl)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctrl` | `Assets.Scripts.UI.Isolate.IsolateDescController` |  |

### OnDisplay(string, int)

```csharp
public void OnDisplay(string str, int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |
| `id` | `System.Int32` |  |

### OnDisplayEnd(IsolateDescription)

```csharp
public void OnDisplayEnd(IsolateDescription i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Assets.Scripts.UI.Isolate.IsolateDescription` |  |

### Terminal()

```csharp
public void Terminal()
```
