---
uid: Global.Mhz_1_76.NoiseDmg
canonical_path: /api/Global/Misc/Mhz176NoiseDmg
---

# Class Mhz_1_76.NoiseDmg

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class Mhz_1_76.NoiseDmg
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Mhz_1_76.NoiseDmg

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### NoiseDmg(PassageObjectModel, GameObject)

```csharp
public NoiseDmg(PassageObjectModel p, GameObject go)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Global.PassageObjectModel` |  |
| `go` | `UnityEngine.GameObject` |  |

## Fields

### _dmgTimer

```csharp
public AutoTimer _dmgTimer
```

#### Field Value

**Type:** Global.AutoTimer

### _filterObject

```csharp
public GameObject _filterObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### _model

```csharp
public static CreatureModel _model
```

#### Field Value

**Type:** Global.CreatureModel

### _passage

```csharp
public PassageObjectModel _passage
```

#### Field Value

**Type:** Global.PassageObjectModel

## Methods

### DestroyNoise()

```csharp
public void DestroyNoise()
```

### GiveNoiseDmg()

```csharp
public void GiveNoiseDmg()
```
