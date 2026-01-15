---
uid: Global.EffectInfo
canonical_path: /api/Global/Info/EffectInfo
---

# Class EffectInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EffectInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EffectInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EffectInfo()

```csharp
public EffectInfo()
```

## Fields

### EffectPrefix

```csharp
public const string EffectPrefix = "DamageInfo/"
```

#### Field Value

**Type:** System.String

### effectSrc

```csharp
public string effectSrc
```

#### Field Value

**Type:** System.String

### effectType

```csharp
public DamageInfo_EffectType effectType
```

#### Field Value

**Type:** Global.DamageInfo_EffectType

### invokedUnit

```csharp
public EffectInvokedUnit invokedUnit
```

#### Field Value

**Type:** Global.EffectInvokedUnit

### invokeOnce

```csharp
public bool invokeOnce
```

#### Field Value

**Type:** System.Boolean

### lifetime

```csharp
public float lifetime
```

#### Field Value

**Type:** System.Single

### relativePosition

```csharp
public Vector3 relativePosition
```

#### Field Value

**Type:** UnityEngine.Vector3

### rotation

```csharp
public float rotation
```

#### Field Value

**Type:** System.Single

### unscaled

```csharp
public bool unscaled
```

#### Field Value

**Type:** System.Boolean

## Methods

### MakeEffect(EffectInfo, MovableObjectNode)

```csharp
public static EffectInvoker MakeEffect(EffectInfo info, MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EffectInfo` |  |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.EffectInvoker

### MakeEffect(MovableObjectNode)

```csharp
public EffectInvoker MakeEffect(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.EffectInvoker
