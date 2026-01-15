---
uid: Global.MagicalGirlTextEffect.InnerEffect
canonical_path: /api/Global/Effect/MagicalGirlTextEffectInnerEffect
---

# Class MagicalGirlTextEffect.InnerEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
protected class MagicalGirlTextEffect.InnerEffect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MagicalGirlTextEffect.InnerEffect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InnerEffect(float, float, SpriteRenderer)

```csharp
public InnerEffect(float startTime, float goalTime, SpriteRenderer target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startTime` | `System.Single` |  |
| `goalTime` | `System.Single` |  |
| `target` | `UnityEngine.SpriteRenderer` |  |

## Fields

### color

```csharp
private Color color
```

#### Field Value

**Type:** UnityEngine.Color

### goalTime

```csharp
public float goalTime
```

#### Field Value

**Type:** System.Single

### startTime

```csharp
public float startTime
```

#### Field Value

**Type:** System.Single

### targetRenderer

```csharp
public SpriteRenderer targetRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

## Methods

### Update(float)

```csharp
public void Update(float currentTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentTime` | `System.Single` |  |
