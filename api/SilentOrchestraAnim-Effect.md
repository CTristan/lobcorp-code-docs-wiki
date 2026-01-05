# Class SilentOrchestraAnim.Effect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim.Effect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SilentOrchestraAnim.Effect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Effect()

```csharp
public Effect()
```

## Fields

### angluarVel

```csharp
public float angluarVel
```

#### Field Value

**Type:** System.Single

### effects

```csharp
public SilentOrchestraAnim.Effect.EffectImage[] effects
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Effect.EffectImage[]

### range

```csharp
public Image range
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RangeImage

```csharp
public Image[] RangeImage
```

#### Field Value

**Type:** UnityEngine.UI.Image[]

### root

```csharp
public Canvas root
```

#### Field Value

**Type:** UnityEngine.Canvas

## Methods

### ChangeRangeImage(int, float)

```csharp
public void ChangeRangeImage(int index, float timeScale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `timeScale` | `System.Single` |  |

### GetCurrentEffectRange()

```csharp
public Timer GetCurrentEffectRange()
```

#### Returns

**Type:** Global.Timer

### Init()

```csharp
public void Init()
```

### Rotate()

```csharp
public void Rotate()
```

### SetRange()

```csharp
public void SetRange()
```

### StartEffect()

```csharp
public void StartEffect()
```
