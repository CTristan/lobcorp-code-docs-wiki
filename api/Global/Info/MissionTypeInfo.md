---
uid: Global.MissionTypeInfo
canonical_path: /api/Global/Info/MissionTypeInfo
---

# Class MissionTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MissionTypeInfo
```
Holds information about a mission type. Used to construct a [Mission](/api/Global/Misc/Mission).

Includes:
- Prerequisites
- Clear/fail conditions
- Sephirah this belongs to
- Text

See also [MissionTypeList](/api/Global/List/MissionTypeList)

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MissionTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MissionTypeInfo()

```csharp
public MissionTypeInfo()
```
#INC
#code-generated


## Fields

### clear

```csharp
public string clear
```
#INC


#### Field Value

**Type:** System.String

### conditions

```csharp
public List<MissionConditionTypeInfo> conditions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MissionConditionTypeInfo}

### desc

```csharp
public string desc
```
#INC


#### Field Value

**Type:** System.String

### diag

```csharp
public string diag
```
#INC


#### Field Value

**Type:** System.String

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### intro

```csharp
public string intro
```
#INC


#### Field Value

**Type:** System.String

### isGlobal

```csharp
public bool isGlobal
```
#INC


#### Field Value

**Type:** System.Boolean

### requires

```csharp
public List<MissionPrerequisite> requires
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MissionPrerequisite}

### sefira

```csharp
public SefiraEnum sefira
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### sefira_Level

```csharp
public int sefira_Level
```
#INC


#### Field Value

**Type:** System.Int32

### sefira_Name

```csharp
public string sefira_Name
```
#INC


#### Field Value

**Type:** System.String

### shortDesc

```csharp
public string shortDesc
```
#INC


#### Field Value

**Type:** System.String

### title

```csharp
public string title
```
#INC


#### Field Value

**Type:** System.String
