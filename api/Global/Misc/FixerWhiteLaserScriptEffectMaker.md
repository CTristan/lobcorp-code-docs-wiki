---
uid: Global.FixerWhiteLaserScript.EffectMaker
canonical_path: /api/Global/Misc/FixerWhiteLaserScriptEffectMaker
---

# Class FixerWhiteLaserScript.EffectMaker

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class FixerWhiteLaserScript.EffectMaker
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FixerWhiteLaserScript.EffectMaker

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EffectMaker(GameObject, FixerWhite, GameObject)

```csharp
public EffectMaker(GameObject pivot, FixerWhite script, GameObject laser)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pivot` | `UnityEngine.GameObject` |  |
| `script` | `Global.FixerWhite` |  |
| `laser` | `UnityEngine.GameObject` |  |

## Fields

### _effectSrc

```csharp
private const string _effectSrc = "Effect/Creature/FixerWhite/FixerWhiteCloud"
```

#### Field Value

**Type:** System.String

### _makeEffectDist

```csharp
private const float _makeEffectDist = 10
```

#### Field Value

**Type:** System.Single

### dir

```csharp
private UnitDirection dir
```

#### Field Value

**Type:** Global.UnitDirection

### laser

```csharp
private GameObject laser
```

#### Field Value

**Type:** UnityEngine.GameObject

### modelPos

```csharp
private Vector3 modelPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### oldPos

```csharp
private Vector3 oldPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### pivot

```csharp
private GameObject pivot
```

#### Field Value

**Type:** UnityEngine.GameObject

### script

```csharp
private FixerWhite script
```

#### Field Value

**Type:** Global.FixerWhite

## Methods

### MakeEffect()

```csharp
public GameObject MakeEffect()
```

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffect_Linear()

```csharp
public void MakeEffect_Linear()
```

### Run()

```csharp
public void Run()
```

### SetPosition()

```csharp
public void SetPosition()
```
