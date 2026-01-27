---
uid: Global.Condition
canonical_path: /api/Global/Misc/Condition
---

# Class Condition

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Condition
```
Condition for mission completion, probably.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Condition

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Condition()

```csharp
public Condition()
```
#INC
#code-generated


## Fields

### current

```csharp
public int current
```
#INC


#### Field Value

**Type:** System.Int32

### metaInfo

```csharp
public MissionConditionTypeInfo metaInfo
```
#INC


#### Field Value

**Type:** Global.MissionConditionTypeInfo

## Properties

### condition_Category

```csharp
public ConditionCategory condition_Category { get; }
```

#### Property Value

**Type:** Global.ConditionCategory

### condition_Type

```csharp
public ConditionType condition_Type { get; }
```

#### Property Value

**Type:** Global.ConditionType

### goal

```csharp
public int goal { get; }
```

#### Property Value

**Type:** System.Int32

### goal_Type

```csharp
public GoalType goal_Type { get; }
```

#### Property Value

**Type:** Global.GoalType

### index

```csharp
public int index { get; }
```

#### Property Value

**Type:** System.Int32

### stat

```csharp
public int stat { get; }
```

#### Property Value

**Type:** System.Int32
