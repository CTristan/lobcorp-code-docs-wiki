---
uid: Global.SkillTypeInfo
canonical_path: /api/Global/Info/SkillTypeInfo
---

# Class SkillTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTypeInfo
```
Holds information about work type.

Has some legacy work constants, but most of the time things just check the [RwbpType](/api/Global/Type/RwbpType) or the id.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkillTypeInfo()

```csharp
public SkillTypeInfo()
```
#INC
#code-generated


## Fields

### Amusements

```csharp
public const long Amusements = 4
```
#INC


#### Field Value

**Type:** System.Int64

### calledName

```csharp
public string calledName
```
#INC


#### Field Value

**Type:** System.String

### Cleanliness

```csharp
public const long Cleanliness = 2
```
#INC


#### Field Value

**Type:** System.Int64

### Consensus

```csharp
public const long Consensus = 3
```
#INC


#### Field Value

**Type:** System.Int64

### id

```csharp
public long id
```
#INC


#### Field Value

**Type:** System.Int64

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### Nutrition

```csharp
public const long Nutrition = 1
```
#INC


#### Field Value

**Type:** System.Int64

### Violence

```csharp
public const long Violence = 5
```
#INC


#### Field Value

**Type:** System.Int64

## Properties

### rwbpType

```csharp
public RwbpType rwbpType { get; }
```

#### Property Value

**Type:** Global.RwbpType
