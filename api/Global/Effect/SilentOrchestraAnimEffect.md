---
uid: Global.SilentOrchestraAnim.Effect
canonical_path: /api/Global/Effect/SilentOrchestraAnimEffect
---

# Class SilentOrchestraAnim.Effect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim.Effect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SilentOrchestraAnim.Effect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### current

```csharp
private SilentOrchestraAnim.Effect.EffectImage current
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Effect.EffectImage

### currentRangeTarget

```csharp
private Image currentRangeTarget
```

#### Field Value

**Type:** UnityEngine.UI.Image

### effects

```csharp
public SilentOrchestraAnim.Effect.EffectImage[] effects
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Effect.EffectImage[]

### index

```csharp
private int index
```

#### Field Value

**Type:** System.Int32

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

## Properties

### rootScale

```csharp
private Vector3 rootScale { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

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
