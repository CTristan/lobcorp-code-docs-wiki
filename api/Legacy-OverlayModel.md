# Class OverlayModel

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OverlayModel()

```csharp
public OverlayModel()
```

## Fields

### canvas

```csharp
[HideInInspector]
public Canvas canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### context

```csharp
public string context
```

#### Field Value

**Type:** System.String

### detailContext

```csharp
public string detailContext
```

#### Field Value

**Type:** System.String

### detailDelay

```csharp
public float detailDelay
```

#### Field Value

**Type:** System.Single

### eventTrigger

```csharp
[HideInInspector]
public EventTrigger eventTrigger
```

#### Field Value

**Type:** UnityEngine.EventSystems.EventTrigger

### isEnabled

```csharp
public bool isEnabled
```

#### Field Value

**Type:** System.Boolean

### layerID

```csharp
public int layerID
```

#### Field Value

**Type:** System.Int32

### pos

```csharp
public OverlayScript.OverlayPos pos
```

#### Field Value

**Type:** Legacy.OverlayScript.OverlayPos

### posData

```csharp
public Vector3[] posData
```

#### Field Value

**Type:** UnityEngine.Vector3[]

### rect

```csharp
[HideInInspector]
public RectTransform rect
```

#### Field Value

**Type:** UnityEngine.RectTransform

### status

```csharp
public OverlayModel.OverlayStatus status
```

#### Field Value

**Type:** Legacy.OverlayModel.OverlayStatus

## Methods

### OnOverlayDisabled()

```csharp
public void OnOverlayDisabled()
```

### OverlayEnter()

```csharp
public void OverlayEnter()
```

### OverlayHalt()

```csharp
public void OverlayHalt()
```

### OverlayHide()

```csharp
public void OverlayHide()
```

### OverlayItemInit(GameObject, string, string, float, bool)

```csharp
public void OverlayItemInit(GameObject target, string context, string detailContext, float detailTime, bool hasDetail)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `UnityEngine.GameObject` |  |
| `context` | `System.String` |  |
| `detailContext` | `System.String` |  |
| `detailTime` | `System.Single` |  |
| `hasDetail` | `System.Boolean` |  |

### PosUpdate()

```csharp
public void PosUpdate()
```

### SetAttatched(OverlayObject)

```csharp
public void SetAttatched(OverlayObject target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Legacy.OverlayObject` |  |

### SetText(string, string)

```csharp
public void SetText(string normal, string detail)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normal` | `System.String` |  |
| `detail` | `System.String` |  |

### Update()

```csharp
public void Update()
```
