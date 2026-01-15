---
uid: Global.Piano.Effect
canonical_path: /api/Global/Effect/PianoEffect
---

# Class Piano.Effect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class Piano.Effect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Piano.Effect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### FLAME

```csharp
public static string FLAME
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
