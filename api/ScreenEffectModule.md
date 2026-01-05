# Class ScreenEffectModule

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ScreenEffectModule
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ScreenEffectModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ScreenEffectModule()

```csharp
public ScreenEffectModule()
```

## Fields

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

### defaultDisplayTime

```csharp
public float defaultDisplayTime
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

### SpriteSrc

```csharp
public string SpriteSrc
```

#### Field Value

**Type:** System.String

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
