---
uid: Global.SilentOrchestraAnim.UI
canonical_path: /api/Global/UI/SilentOrchestraAnimUI
---

# Class SilentOrchestraAnim.UI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim.UI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SilentOrchestraAnim.UI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UI()

```csharp
public UI()
```

## Fields

### currentTypoState

```csharp
public SilentOrchestraAnim.UI.TypoState currentTypoState
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.UI.TypoState

### CurtainAnim

```csharp
public Animator CurtainAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### displaying

```csharp
public float displaying
```

#### Field Value

**Type:** System.Single

### fadeIn

```csharp
[Space(10)]
public float fadeIn
```

#### Field Value

**Type:** System.Single

### fadeOut

```csharp
public float fadeOut
```

#### Field Value

**Type:** System.Single

### root

```csharp
public GameObject root
```

#### Field Value

**Type:** UnityEngine.GameObject

### RootCanvas

```csharp
public Canvas RootCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### textCanvasGroup

```csharp
public CanvasGroup textCanvasGroup
```

#### Field Value

**Type:** UnityEngine.CanvasGroup

### TypoAnim

```csharp
public Animator TypoAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### TypoImage

```csharp
public Image TypoImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### typoSprite

```csharp
public Sprite[] typoSprite
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### TypoText

```csharp
public Text TypoText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### unscaledTimer

```csharp
private UnscaledTimer unscaledTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

## Methods

### Init()

```csharp
public void Init()
```

### SetActivate(bool)

```csharp
public void SetActivate(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetNextType()

```csharp
private void SetNextType()
```

### TypoEffect(int)

```csharp
public void TypoEffect(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### TypoInit()

```csharp
public void TypoInit()
```

### Update()

```csharp
public void Update()
```
