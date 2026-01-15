---
uid: Global.AgentInfoWindow.WorkerPrimaryStatUI
canonical_path: /api/Global/UI/AgentInfoWindowWorkerPrimaryStatUI
---

# Class AgentInfoWindow.WorkerPrimaryStatUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentInfoWindow.WorkerPrimaryStatUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentInfoWindow.WorkerPrimaryStatUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerPrimaryStatUI()

```csharp
public WorkerPrimaryStatUI()
```

## Fields

### Icon

```csharp
public Image Icon
```

#### Field Value

**Type:** UnityEngine.UI.Image

### list

```csharp
public List<AgentInfoWindow.WorkerPrimaryStatUnit> list
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentInfoWindow.WorkerPrimaryStatUnit}

### StatName

```csharp
public Text StatName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### type

```csharp
public RwbpType type
```

#### Field Value

**Type:** Global.RwbpType

## Methods

### SetStat(AgentModel)

```csharp
public void SetStat(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
