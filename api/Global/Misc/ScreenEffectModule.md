---
uid: Global.ScreenEffectModule
canonical_path: /api/Global/Misc/ScreenEffectModule
---

# Class ScreenEffectModule

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ScreenEffectModule
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ScreenEffectModule

## Derived
[BloodyEffect](/api/Global/Effect/BloodyEffect)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ScreenEffectModule()

```csharp
public ScreenEffectModule()
```

## Fields

### _sequenceChanged

```csharp
private bool _sequenceChanged
```

#### Field Value

**Type:** System.Boolean

### anim

```csharp
[HideInInspector]
public Animator anim
```

#### Field Value

**Type:** UnityEngine.Animator

### AnimParam

```csharp
public string AnimParam
```

#### Field Value

**Type:** System.String

### currentSprite

```csharp
private Sprite currentSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### defaultDisplayTime

```csharp
public float defaultDisplayTime
```

#### Field Value

**Type:** System.Single

### del

```csharp
private AutoTimer.TargetMethod del
```

#### Field Value

**Type:** Global.AutoTimer.TargetMethod

### displayedImage

```csharp
private Image displayedImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### displayTime

```csharp
private float displayTime
```

#### Field Value

**Type:** System.Single

### effectType

```csharp
public UIEffectType effectType
```

#### Field Value

**Type:** Global.UIEffectType

### fps

```csharp
public int fps
```

#### Field Value

**Type:** System.Int32

### fpsElapsed

```csharp
private float fpsElapsed
```

#### Field Value

**Type:** System.Single

### hasAnim

```csharp
public bool hasAnim
```

#### Field Value

**Type:** System.Boolean

### hasSequence

```csharp
public bool hasSequence
```

#### Field Value

**Type:** System.Boolean

### id

```csharp
public long id
```

#### Field Value

**Type:** System.Int64

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### shouldLoad

```csharp
public bool shouldLoad
```

#### Field Value

**Type:** System.Boolean

### spriteList

```csharp
private List<Sprite> spriteList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### SpriteSrc

```csharp
public string SpriteSrc
```

#### Field Value

**Type:** System.String

### timer

```csharp
private AutoTimer timer
```

#### Field Value

**Type:** Global.AutoTimer

### updateCalled

```csharp
private AutoTimer.TargetMethod updateCalled
```

#### Field Value

**Type:** Global.AutoTimer.TargetMethod

### useDefaultAnim

```csharp
public bool useDefaultAnim
```

#### Field Value

**Type:** System.Boolean

## Properties

### CurrentSprite

```csharp
public Sprite CurrentSprite { get; }
```

#### Property Value

**Type:** UnityEngine.Sprite

### fpsTotal

```csharp
private float fpsTotal { get; }
```

#### Property Value

**Type:** System.Single

### sequenceChanged

```csharp
public bool sequenceChanged { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AnimBoolMessage(string, bool)

```csharp
public virtual void AnimBoolMessage(string target, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.String` |  |
| `state` | `System.Boolean` |  |

### Disable()

```csharp
public virtual void Disable()
```

### Enable()

```csharp
public virtual void Enable()
```

### GetAnimParam()

```csharp
private string GetAnimParam()
```

#### Returns

**Type:** System.String

### Init(Image)

```csharp
public virtual void Init(Image SpriteDisplayedImage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `SpriteDisplayedImage` | `UnityEngine.UI.Image` |  |

### StartEffect()

```csharp
public virtual void StartEffect()
```

### StartEffect(float)

```csharp
public virtual void StartEffect(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### Update()

```csharp
public virtual void Update()
```
