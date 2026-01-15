---
uid: Global.MissionTypeList
canonical_path: /api/Global/List/MissionTypeList
---

# Class MissionTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MissionTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MissionTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MissionTypeList()

```csharp
private MissionTypeList()
```

## Fields

### _instance

```csharp
private static MissionTypeList _instance
```

#### Field Value

**Type:** Global.MissionTypeList

### _list

```csharp
private List<MissionTypeInfo> _list
```

#### Field Value

**Type:** System.Collections.Generic.List{MissionTypeInfo}

## Properties

### instance

```csharp
public static MissionTypeList instance { get; }
```

#### Property Value

**Type:** Global.MissionTypeList

## Methods

### GetData(int)

```csharp
public MissionTypeInfo GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.MissionTypeInfo

### GetList()

```csharp
public IList<MissionTypeInfo> GetList()
```

#### Returns

**Type:** System.Collections.Generic.IList{MissionTypeInfo}

### LoadData()

```csharp
public void LoadData()
```
