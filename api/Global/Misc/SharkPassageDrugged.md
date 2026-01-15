---
uid: Global.Shark.PassageDrugged
canonical_path: /api/Global/Misc/SharkPassageDrugged
---

# Class Shark.PassageDrugged

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Shark.PassageDrugged
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Shark.PassageDrugged

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PassageDrugged(PassageObjectModel, GameObject)

```csharp
public PassageDrugged(PassageObjectModel passage, GameObject filter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
| `filter` | `UnityEngine.GameObject` |  |

## Fields

### _filter

```csharp
private GameObject _filter
```

#### Field Value

**Type:** UnityEngine.GameObject

### _passage

```csharp
private PassageObjectModel _passage
```

#### Field Value

**Type:** Global.PassageObjectModel

### _passed

```csharp
private bool _passed
```

#### Field Value

**Type:** System.Boolean

## Properties

### IsPassed

```csharp
public bool IsPassed { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

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
