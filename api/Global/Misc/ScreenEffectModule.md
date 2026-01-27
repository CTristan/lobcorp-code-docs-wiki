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
Manages a visual effect. Used by [UIEffectManager](/api/Global/Misc/UIEffectManager)

#INC 


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
#INC


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
#INC


#### Field Value

**Type:** System.String

### currentSprite

```csharp
private Sprite currentSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### defaultDisplayTime

```csharp
public float defaultDisplayTime
```
#INC


#### Field Value

**Type:** System.Single

### del

```csharp
private AutoTimer.TargetMethod del
```
#INC


#### Field Value

**Type:** Global.AutoTimer.TargetMethod

### displayedImage

```csharp
private Image displayedImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### displayTime

```csharp
private float displayTime
```
#INC


#### Field Value

**Type:** System.Single

### effectType

```csharp
public UIEffectType effectType
```
#INC


#### Field Value

**Type:** Global.UIEffectType

### fps

```csharp
public int fps
```
#INC


#### Field Value

**Type:** System.Int32

### fpsElapsed

```csharp
private float fpsElapsed
```
#INC


#### Field Value

**Type:** System.Single

### hasAnim

```csharp
public bool hasAnim
```
#INC


#### Field Value

**Type:** System.Boolean

### hasSequence

```csharp
public bool hasSequence
```
#INC


#### Field Value

**Type:** System.Boolean

### id

```csharp
public long id
```
#INC


#### Field Value

**Type:** System.Int64

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### shouldLoad

```csharp
public bool shouldLoad
```
#INC


#### Field Value

**Type:** System.Boolean

### spriteList

```csharp
private List<Sprite> spriteList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### SpriteSrc

```csharp
public string SpriteSrc
```
#INC


#### Field Value

**Type:** System.String

### timer

```csharp
private AutoTimer timer
```
#INC


#### Field Value

**Type:** Global.AutoTimer

### updateCalled

```csharp
private AutoTimer.TargetMethod updateCalled
```
#INC


#### Field Value

**Type:** Global.AutoTimer.TargetMethod

### useDefaultAnim

```csharp
public bool useDefaultAnim
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.String` |  |
| `state` | `System.Boolean` |  |

### Disable()

```csharp
public virtual void Disable()
```
#INC


### Enable()

```csharp
public virtual void Enable()
```
#INC


### GetAnimParam()

```csharp
private string GetAnimParam()
```
#INC


#### Returns

**Type:** System.String

### Init(Image)

```csharp
public virtual void Init(Image SpriteDisplayedImage)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `SpriteDisplayedImage` | `UnityEngine.UI.Image` |  |

### StartEffect()

```csharp
public virtual void StartEffect()
```
#INC


### StartEffect(float)

```csharp
public virtual void StartEffect(float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### Update()

```csharp
public virtual void Update()
```
#INC

