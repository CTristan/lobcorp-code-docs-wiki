---
uid: Global.SkillTypeList
canonical_path: /api/Global/List/SkillTypeList
---

# Class SkillTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTypeList
```
A list of [SkillTypeInfo](/api/Global/Info/SkillTypeInfo)s, mostly for abnormality work type. #verify 

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkillTypeList()

```csharp
private SkillTypeList()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static SkillTypeList _instance
```
#INC


#### Field Value

**Type:** Global.SkillTypeList

### _list

```csharp
private List<SkillTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SkillTypeInfo}

### _loaded

```csharp
private bool _loaded
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### instance

```csharp
public static SkillTypeList instance { get; }
```

#### Property Value

**Type:** Global.SkillTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public SkillTypeInfo GetData(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### GetDataByName(string)

```csharp
public SkillTypeInfo GetDataByName(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### GetList()

```csharp
public SkillTypeInfo[] GetList()
```
#INC


#### Returns

**Type:** Global.SkillTypeInfo[]

### GetNextSkill(SkillTypeInfo)

```csharp
public SkillTypeInfo GetNextSkill(SkillTypeInfo typeInfo)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `typeInfo` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### Init(SkillTypeInfo[])

```csharp
public void Init(SkillTypeInfo[] list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.SkillTypeInfo[]` |  |
