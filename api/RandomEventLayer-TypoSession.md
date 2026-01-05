# Class RandomEventLayer.TypoSession

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventLayer.TypoSession
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventLayer.TypoSession

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TypoSession()

```csharp
public TypoSession()
```

## Fields

### color

```csharp
public Color color
```

#### Field Value

**Type:** UnityEngine.Color

### desc

```csharp
public string desc
```

#### Field Value

**Type:** System.String

### displayEnd

```csharp
public List<RandomEventLayer.TypoEvent> displayEnd
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventLayer.TypoEvent}

### displaying

```csharp
public float displaying
```

#### Field Value

**Type:** System.Single

### fadeIn

```csharp
public List<RandomEventLayer.TypoEvent> fadeIn
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventLayer.TypoEvent}

### fadeInRatio

```csharp
public float fadeInRatio
```

#### Field Value

**Type:** System.Single

### fadeInTime

```csharp
public float fadeInTime
```

#### Field Value

**Type:** System.Single

### fadeOutRatio

```csharp
public float fadeOutRatio
```

#### Field Value

**Type:** System.Single

### fadeOutTime

```csharp
public float fadeOutTime
```

#### Field Value

**Type:** System.Single

### HasDesc

```csharp
public bool HasDesc
```

#### Field Value

**Type:** System.Boolean

### HasName

```csharp
public bool HasName
```

#### Field Value

**Type:** System.Boolean

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### soundSrc

```csharp
public string soundSrc
```

#### Field Value

**Type:** System.String

### topText

```csharp
public string topText
```

#### Field Value

**Type:** System.String

### totalTime

```csharp
public float totalTime
```

#### Field Value

**Type:** System.Single

### types

```csharp
public string types
```

#### Field Value

**Type:** System.String

### useRatio

```csharp
public bool useRatio
```

#### Field Value

**Type:** System.Boolean

## Properties

### FadeOutStart

```csharp
public float FadeOutStart { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### SetRatio(float, float)

```csharp
public void SetRatio(float fadeIn, float fadeOut)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fadeIn` | `System.Single` |  |
| `fadeOut` | `System.Single` |  |

### SetTime()

```csharp
public void SetTime()
```

### SetTime(float)

```csharp
public void SetTime(float totalTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `totalTime` | `System.Single` |  |

### SetTime(float, float, float)

```csharp
public void SetTime(float fadein, float displaying, float fadeout)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fadein` | `System.Single` |  |
| `displaying` | `System.Single` |  |
| `fadeout` | `System.Single` |  |

### SetTypoEvent(TypoState, TypoEvent)

```csharp
public void SetTypoEvent(RandomEventLayer.TypoState state, RandomEventLayer.TypoEvent called)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.RandomEventLayer.TypoState` |  |
| `called` | `Global.RandomEventLayer.TypoEvent` |  |
