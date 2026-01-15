---
uid: Global.RestrictionTable.TableElement
canonical_path: /api/Global/Misc/RestrictionTableTableElement
---

# Class RestrictionTable.TableElement

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RestrictionTable.TableElement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RestrictionTable.TableElement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TableElement()

```csharp
public TableElement()
```

## Fields

### creatureID

```csharp
public long creatureID
```

#### Field Value

**Type:** System.Int64

### list

```csharp
public List<RestrictionTable.TableElement.Restriction> list
```

#### Field Value

**Type:** System.Collections.Generic.List{RestrictionTable.TableElement.Restriction}

## Methods

### GetRestriction()

```csharp
public RestrictionTable.TableElement.Restriction[] GetRestriction()
```

#### Returns

**Type:** Global.RestrictionTable.TableElement.Restriction[]

### GetRestrictionString()

```csharp
public List<string> GetRestrictionString()
```

#### Returns

**Type:** System.Collections.Generic.List{System.String}

### Init(CreatureModel)

```csharp
public void Init(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
