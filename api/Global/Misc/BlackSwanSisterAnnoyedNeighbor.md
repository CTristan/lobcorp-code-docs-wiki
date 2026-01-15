---
uid: Global.BlackSwanSister.AnnoyedNeighbor
canonical_path: /api/Global/Misc/BlackSwanSisterAnnoyedNeighbor
---

# Class BlackSwanSister.AnnoyedNeighbor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackSwanSister.AnnoyedNeighbor
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BlackSwanSister.AnnoyedNeighbor

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnnoyedNeighbor(CreatureModel, float)

```csharp
public AnnoyedNeighbor(CreatureModel creature, float coolTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `coolTime` | `System.Single` |  |

## Fields

### coolTime

```csharp
private float coolTime
```

#### Field Value

**Type:** System.Single

### creature

```csharp
private CreatureModel creature
```

#### Field Value

**Type:** Global.CreatureModel

### enable

```csharp
private bool enable
```

#### Field Value

**Type:** System.Boolean

## Methods

### GetModel()

```csharp
public CreatureModel GetModel()
```

#### Returns

**Type:** Global.CreatureModel

### IsEnable()

```csharp
public bool IsEnable()
```

#### Returns

**Type:** System.Boolean

### Process()

```csharp
public void Process()
```
