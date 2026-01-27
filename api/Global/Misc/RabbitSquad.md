---
uid: Global.RabbitSquad
canonical_path: /api/Global/Misc/RabbitSquad
---

# Class RabbitSquad

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitSquad
```
A collection of [rabbit teams](/api/Global/Misc/RabbitTeam) representing the rabbits in a given [operation area](/api/Global/Misc/RabbitOperationArea).

Also holds the list of disabled doors and portals created by the Rabbit Protocol in this operation area.

Also, holds a timer for the rabbits to leave if nothing happens for long enough #verify.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitSquad

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitSquad()

```csharp
public RabbitSquad()
```

## Fields

### clearCheckTimer

```csharp
public Timer clearCheckTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### sector

```csharp
public string sector
```
#INC


#### Field Value

**Type:** System.String

### sefira

```csharp
public SefiraEnum sefira
```
#INC
#code-generated


#### Field Value

**Type:** Global.SefiraEnum

### shutdownNodes

```csharp
public List<MapNode> shutdownNodes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### teams

```csharp
public List<RabbitTeam> teams
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeam}

### teleports

```csharp
public List<RabbitTeleportData> teleports
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeleportData}
