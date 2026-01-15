---
uid: Global.Yggdrasil.InfestedPassage
canonical_path: /api/Global/Misc/YggdrasilInfestedPassage
---

# Class Yggdrasil.InfestedPassage

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Yggdrasil.InfestedPassage
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Yggdrasil.InfestedPassage

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InfestedPassage(PassageObjectModel, GameObject, Yggdrasil)

```csharp
public InfestedPassage(PassageObjectModel passage, GameObject filter, Yggdrasil script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
| `filter` | `UnityEngine.GameObject` |  |
| `script` | `Global.Yggdrasil` |  |

## Fields

### dmgFreq

```csharp
private const float dmgFreq = 5
```

#### Field Value

**Type:** System.Single

### dmgTimer

```csharp
private Timer dmgTimer
```

#### Field Value

**Type:** Global.Timer

### filter

```csharp
private GameObject filter
```

#### Field Value

**Type:** UnityEngine.GameObject

### passage

```csharp
private PassageObjectModel passage
```

#### Field Value

**Type:** Global.PassageObjectModel

### script

```csharp
private Yggdrasil script
```

#### Field Value

**Type:** Global.Yggdrasil

## Properties

### model

```csharp
private CreatureModel model { get; }
```

#### Property Value

**Type:** Global.CreatureModel

## Methods

### Attack()

```csharp
private void Attack()
```

### AttackEffect()

```csharp
private void AttackEffect()
```

### Destroy()

```csharp
public void Destroy()
```

### GetSapNum()

```csharp
private int GetSapNum()
```

#### Returns

**Type:** System.Int32

### GetSaps()

```csharp
private CreatureModel[] GetSaps()
```

#### Returns

**Type:** Global.CreatureModel[]

### IsAvailable()

```csharp
public bool IsAvailable()
```

#### Returns

**Type:** System.Boolean

### Process()

```csharp
public void Process()
```
