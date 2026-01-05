# Class ExplodeGutEffect.GutElements

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ExplodeGutEffect.GutElements
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ExplodeGutEffect.GutElements

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GutElements()

```csharp
public GutElements()
```

## Fields

### currentData

```csharp
public ExplodeGutManager.ExplodeGutData currentData
```

#### Field Value

**Type:** Global.ExplodeGutManager.ExplodeGutData

### elasticFactor

```csharp
public float elasticFactor
```

#### Field Value

**Type:** System.Single

### forceFixed

```csharp
public float forceFixed
```

#### Field Value

**Type:** System.Single

### forceMultiplier

```csharp
public float forceMultiplier
```

#### Field Value

**Type:** System.Single

### initialVector

```csharp
public Vector3 initialVector
```

#### Field Value

**Type:** UnityEngine.Vector3

### script

```csharp
public ExplodeGutEffect script
```

#### Field Value

**Type:** Global.ExplodeGutEffect

### spriteParent

```csharp
public GameObject spriteParent
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### gameObjecct

```csharp
public GameObject gameObjecct { get; }
```

#### Property Value

**Type:** UnityEngine.GameObject

### IsEnabled

```csharp
public bool IsEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

### spriteRenderer

```csharp
public SpriteRenderer spriteRenderer { get; }
```

#### Property Value

**Type:** UnityEngine.SpriteRenderer

### transform

```csharp
public Transform transform { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### Execute(Timer)

```csharp
public void Execute(Timer currentTimer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentTimer` | `Global.Timer` |  |

### MakeTrace()

```csharp
public void MakeTrace()
```

### SetEmission(bool)

```csharp
public void SetEmission(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetSprite(Sprite)

```csharp
public void SetSprite(Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### SetState(bool)

```csharp
public void SetState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### Shoot(Vector3)

```csharp
public void Shoot(Vector3 initialPosition)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `initialPosition` | `UnityEngine.Vector3` |  |

### StopEffect()

```csharp
public void StopEffect()
```
