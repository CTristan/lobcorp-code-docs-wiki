---
uid: Global.PanicData
canonical_path: /api/Global/Misc/PanicData
---
# Class PanicData
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicData
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}

Should be unused[^1].





[^1]: UseSkill.CheckLive() will call old panic code:
	    AgentModel.PanicByCreature(CreatureModel, SkillTypeInfo)
	if this work is not completed (closed = false) and the agent has 0 or less SP (agent.mental <= 0). This should never happen, but might in some edge case. This causes the agent to panic without ever calling Agent.Panic(). 
	
	Note that this doesn't *seem* to affect anything, but may have weird consequences.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PanicData

## Constructors
### PanicData()
```csharp
public PanicData()
```

## Fields
### PanicBuildCode
```csharp
public string PanicBuildCode
```


#### Field Value
**Type:** System.String

### PanicDesc
```csharp
public string PanicDesc
```


#### Field Value
**Type:** System.String

### PanicId
```csharp
public int PanicId
```


#### Field Value
**Type:** System.Int32

### PanicLifeStyle
```csharp
public string PanicLifeStyle
```


#### Field Value
**Type:** System.String

### PanicName
```csharp
public string PanicName
```


#### Field Value
**Type:** System.String

## Methods
### BuildDefaultPanicAction(WorkerModel)
```csharp
public PanicAction BuildDefaultPanicAction(WorkerModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

#### Returns
**Type:** Global.PanicAction

### BuildPanicAction(WorkerModel)
```csharp
public PanicAction BuildPanicAction(WorkerModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

#### Returns
**Type:** Global.PanicAction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)




