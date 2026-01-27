---
uid: Global.RabbitSquadData
canonical_path: /api/Global/Misc/RabbitSquadData
---

# Class RabbitSquadData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitSquadData
```
Holds the information for creating a [RabbitSquad](/api/Global/Misc/RabbitSquad).

Holds the squad ID, the department ID, [RabbitTeamData](/api/Global/Misc/RabbitTeamData) for the teams, the list of nodes to deactivate, and [RabbitTeleportData](/api/Global/Misc/RabbitTeleportData) for the teleports. #verify #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitSquadData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitSquadData()

```csharp
public RabbitSquadData()
```

## Fields

### id

```csharp
public int id
```
#INC
#code-generated


#### Field Value

**Type:** System.Int32

### sefira

```csharp
public SefiraEnum sefira
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### shutdownNodes

```csharp
public List<string> shutdownNodes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### teams

```csharp
public List<RabbitTeamData> teams
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeamData}

### teleports

```csharp
public List<RabbitTeleportData> teleports
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeleportData}
