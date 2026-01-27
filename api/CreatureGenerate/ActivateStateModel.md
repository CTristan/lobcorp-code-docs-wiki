---
uid: CreatureGenerate.ActivateStateModel
canonical_path: /api/CreatureGenerate/ActivateStateModel
---

# Class ActivateStateModel

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ActivateStateModel
```
Stores the state of an abnormality for extraction (risk level, id, if it exists in the facility, if it has been removed (?), and if it's a tool abnormality).

See [ActivateStateList](/api/CreatureGenerate/ActivateStateList)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ActivateStateModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ActivateStateModel()

```csharp
public ActivateStateModel()
```

## Fields

### id

```csharp
public long id
```
#INC


#### Field Value

**Type:** System.Int64

### isKit

```csharp
public bool isKit
```
#INC


#### Field Value

**Type:** System.Boolean

### isRemoved

```csharp
public bool isRemoved
```
#INC


#### Field Value

**Type:** System.Boolean

### isUsed

```csharp
public bool isUsed
```
#INC


#### Field Value

**Type:** System.Boolean

### riskLevel

```csharp
public RiskLevel riskLevel
```
#INC
#code-generated


#### Field Value

**Type:** Global.RiskLevel
