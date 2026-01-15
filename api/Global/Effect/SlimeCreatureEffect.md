---
uid: Global.SlimeCreature.Effect
canonical_path: /api/Global/Effect/SlimeCreatureEffect
---

# Class SlimeCreature.Effect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SlimeCreature.Effect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SlimeCreature.Effect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### ENRAGE_BUF

```csharp
public static string ENRAGE_BUF
```

#### Field Value

**Type:** System.String

### ENRAGE_START

```csharp
public static string ENRAGE_START
```

#### Field Value

**Type:** System.String

### ESCAPE

```csharp
public static string ESCAPE
```

#### Field Value

**Type:** System.String

### GIVE_LOVER_BUF

```csharp
public static string GIVE_LOVER_BUF
```

#### Field Value

**Type:** System.String

### LOVER_INFEST

```csharp
public static string LOVER_INFEST
```

#### Field Value

**Type:** System.String

### PAWN_INFEST

```csharp
public static string PAWN_INFEST
```

#### Field Value

**Type:** System.String

### PROJECTILE_DEBUF

```csharp
public static string PROJECTILE_DEBUF
```

#### Field Value

**Type:** System.String

### PROJECTILE_HIT

```csharp
public static string PROJECTILE_HIT
```

#### Field Value

**Type:** System.String

## Methods

### MakeEffect(string, GameObject)

```csharp
public static GameObject MakeEffect(string src, GameObject parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `parent` | `UnityEngine.GameObject` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffect(string, Vector3, float)

```csharp
public static GameObject MakeEffect(string src, Vector3 pos, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.GameObject
