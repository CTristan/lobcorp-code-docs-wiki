---
uid: Global.BossBirdAnim.NarrationUI
canonical_path: /api/Global/UI/BossBirdAnimNarrationUI
---

# Class BossBirdAnim.NarrationUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdAnim.NarrationUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BossBirdAnim.NarrationUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### NarrationUI()

```csharp
public NarrationUI()
```

## Fields

### _fadeoutEvent

```csharp
private BossBirdAnim.NarrationUI.FadeOutEvent _fadeoutEvent
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.FadeOutEvent

### canvasGroup

```csharp
public CanvasGroup canvasGroup
```

#### Field Value

**Type:** UnityEngine.CanvasGroup

### currentDisplaying

```csharp
private BossBirdAnim.NarrationData currentDisplaying
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationData

### displayState

```csharp
public BossBirdAnim.NarrationUI.NarrationDisplayState displayState
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.NarrationDisplayState

### endEvent

```csharp
private BossBirdAnim.NarrationUI.NarrationEndEvent endEvent
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.NarrationEndEvent

### FadeInGrad

```csharp
public Gradient FadeInGrad
```

#### Field Value

**Type:** UnityEngine.Gradient

### FadeInTime

```csharp
public float FadeInTime
```

#### Field Value

**Type:** System.Single

### FadeOutGrad

```csharp
public Gradient FadeOutGrad
```

#### Field Value

**Type:** UnityEngine.Gradient

### FadeOutTime

```csharp
public float FadeOutTime
```

#### Field Value

**Type:** System.Single

### imageRendered

```csharp
public Image imageRendered
```

#### Field Value

**Type:** UnityEngine.UI.Image

### isWaitingNext

```csharp
private bool isWaitingNext
```

#### Field Value

**Type:** System.Boolean

### narrationImages

```csharp
public List<BossBirdAnim.NarrationUI.NarrationImage> narrationImages
```

#### Field Value

**Type:** System.Collections.Generic.List{BossBirdAnim.NarrationUI.NarrationImage}

### narrationText

```csharp
public Text narrationText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### narrationTimer

```csharp
public UnscaledTimer narrationTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### root

```csharp
public GameObject root
```

#### Field Value

**Type:** UnityEngine.GameObject

### tempSave

```csharp
private BossBirdAnim.NarrationUI.NarrationEndEvent tempSave
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.NarrationEndEvent

### wait

```csharp
private BossBirdAnim.NarrationData wait
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationData

### waitQueue

```csharp
private Queue<BossBirdAnim.NarrationData> waitQueue
```

#### Field Value

**Type:** System.Collections.Generic.Queue{BossBirdAnim.NarrationData}

## Properties

### fadeOutEvent

```csharp
public BossBirdAnim.NarrationUI.FadeOutEvent fadeOutEvent { get; set; }
```

#### Property Value

**Type:** Global.BossBirdAnim.NarrationUI.FadeOutEvent

### IsWaitingNext

```csharp
public bool IsWaitingNext { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetImage(NarrationState)

```csharp
private BossBirdAnim.NarrationUI.NarrationImage GetImage(BossBird.NarrationState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.BossBird.NarrationState` |  |

#### Returns

**Type:** Global.BossBirdAnim.NarrationUI.NarrationImage

### GetTotalTime(float)

```csharp
private float GetTotalTime(float displayTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `displayTime` | `System.Single` |  |

#### Returns

**Type:** System.Single

### OnUpdate()

```csharp
public void OnUpdate()
```

### SetNarration(NarrationData)

```csharp
public void SetNarration(BossBirdAnim.NarrationData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBirdAnim.NarrationData` |  |

### SetNarration(string, float, NarrationEndEvent)

```csharp
public void SetNarration(string text, float time, BossBirdAnim.NarrationUI.NarrationEndEvent endEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `time` | `System.Single` |  |
| `endEvent` | `Global.BossBirdAnim.NarrationUI.NarrationEndEvent` |  |

### SetState(bool)

```csharp
public void SetState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
