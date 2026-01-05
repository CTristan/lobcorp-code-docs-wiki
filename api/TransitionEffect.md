# Class TransitionEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TransitionEffect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TransitionEffect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TransitionEffect()

```csharp
public TransitionEffect()
```

## Fields

### bicScale

```csharp
public float bicScale
```

#### Field Value

**Type:** System.Single

### smallScale

```csharp
public float smallScale
```

#### Field Value

**Type:** System.Single

### TransitionCurve

```csharp
public AnimationCurve TransitionCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### TransitionTime

```csharp
public float TransitionTime
```

#### Field Value

**Type:** System.Single

### TransitionTimer

```csharp
public Timer TransitionTimer
```

#### Field Value

**Type:** Global.Timer

## Properties

### IsBigger

```csharp
public bool IsBigger { get; }
```

#### Property Value

**Type:** System.Boolean

### IsTrans

```csharp
public bool IsTrans { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### StartTransition(bool)

```csharp
public void StartTransition(bool isBigger)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isBigger` | `System.Boolean` |  |

### Update()

```csharp
public void Update()
```
