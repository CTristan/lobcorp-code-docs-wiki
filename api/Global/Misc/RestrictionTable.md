---
uid: Global.RestrictionTable
canonical_path: /api/Global/Misc/RestrictionTable
---

# Class RestrictionTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RestrictionTable
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RestrictionTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RestrictionTable()

```csharp
public RestrictionTable()
```

## Fields

### _instance

```csharp
private static RestrictionTable _instance
```



#### Field Value

**Type:** Global.RestrictionTable

### list

```csharp
public List<RestrictionTable.TableElement> list
```

#### Field Value

**Type:** System.Collections.Generic.List{RestrictionTable.TableElement}

## Properties

### instance

```csharp
public static RestrictionTable instance { get; }
```

#### Property Value

**Type:** Global.RestrictionTable

## Methods

### AddCreature(CreatureModel)

```csharp
public void AddCreature(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### GetTableByCreature(CreatureModel)

```csharp
public RestrictionTable.TableElement GetTableByCreature(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

#### Returns

**Type:** Global.RestrictionTable.TableElement
