---
uid: Global.MapObjectModel
canonical_path: /api/Global/Model/MapObjectModel
---

# Class MapObjectModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapObjectModel : ObjectModelBase
```

Represents an object which is part of a room now. Seems to only be used by [BloodMapObjectModel](/api/Global/Model/BloodMapObjectModel).

#INC


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ObjectModelBase](/api/Global/Object/ObjectModelBase) → MapObjectModel

## Derived
[BloodMapObjectModel](/api/Global/Model/BloodMapObjectModel)

## Inherited Members
[position](/api/Global/Object/ObjectModelBase#position), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapObjectModel()

```csharp
public MapObjectModel()
```

## Fields

### horrorPoint

```csharp
public int horrorPoint
```
#INC


#### Field Value

**Type:** System.Int32

### metaInfo

```csharp
public MapObjectTypeInfo metaInfo
```
#INC
#code-generated


#### Field Value

**Type:** Global.MapObjectTypeInfo

### passage

```csharp
public PassageObjectModel passage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel
