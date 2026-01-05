# Class SefiraMovement

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraMovement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraMovement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SefiraMovement()

```csharp
public SefiraMovement()
```

## Fields

### ActiveControl

```csharp
public GameObject ActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### AreaName

```csharp
public Text AreaName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### FrameControl

```csharp
public Image FrameControl
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftArrow

```csharp
public Image LeftArrow
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightArrow

```csharp
public Image RightArrow
```

#### Field Value

**Type:** UnityEngine.UI.Image

### SefiraColor

```csharp
public List<Image> SefiraColor
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Image}

## Methods

### AreaInit()

```csharp
public void AreaInit()
```

### CheckContains(SefiraEnum)

```csharp
public bool CheckContains(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### MoveNextSefira(SefiraEnum, out SefiraEnum)

```csharp
public bool MoveNextSefira(SefiraEnum current, out SefiraEnum moved)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
| `moved` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### MovePrevSefira(SefiraEnum, out SefiraEnum)

```csharp
public bool MovePrevSefira(SefiraEnum current, out SefiraEnum moved)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
| `moved` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### SetCurrentSefira(SefiraEnum)

```csharp
public void SetCurrentSefira(SefiraEnum current)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
