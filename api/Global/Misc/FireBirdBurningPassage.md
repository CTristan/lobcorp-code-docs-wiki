---
uid: Global.FireBird.BurningPassage
canonical_path: /api/Global/Misc/FireBirdBurningPassage
---

# Class FireBird.BurningPassage

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FireBird.BurningPassage
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FireBird.BurningPassage

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BurningPassage(PassageObjectModel, GameObject, FireBird)

```csharp
public BurningPassage(PassageObjectModel passage, GameObject filter, FireBird script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
| `filter` | `UnityEngine.GameObject` |  |
| `script` | `Global.FireBird` |  |

## Fields

### defaultRemain

```csharp
private const float defaultRemain = 1
```

#### Field Value

**Type:** System.Single

### filter

```csharp
private GameObject filter
```

#### Field Value

**Type:** UnityEngine.GameObject

### isEnable

```csharp
private bool isEnable
```

#### Field Value

**Type:** System.Boolean

### list

```csharp
private List<FireBird.BurningPassage.DamagedUnit> list
```

#### Field Value

**Type:** System.Collections.Generic.List{FireBird.BurningPassage.DamagedUnit}

### passage

```csharp
private PassageObjectModel passage
```

#### Field Value

**Type:** Global.PassageObjectModel

### script

```csharp
private FireBird script
```

#### Field Value

**Type:** Global.FireBird

## Methods

### CheckDamaged(UnitModel)

```csharp
private bool CheckDamaged(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### Destroy()

```csharp
public void Destroy()
```

### GetPassage()

```csharp
public PassageObjectModel GetPassage()
```

#### Returns

**Type:** Global.PassageObjectModel

### Process()

```csharp
public void Process()
```
