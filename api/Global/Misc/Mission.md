---
uid: Global.Mission
canonical_path: /api/Global/Misc/Mission
---

# Class Mission

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Mission
```
Represents a mission.

See [MissionManager](/api/Global/IOBserver/MissionManager)

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Mission

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Mission()

```csharp
public Mission()
```
#INC
#code-generated


### Mission(MissionTypeInfo)

```csharp
public Mission(MissionTypeInfo metadata)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadata` | `Global.MissionTypeInfo` |  |

## Fields

### baseConditions

```csharp
public List<Condition> baseConditions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### checkedObjects

```csharp
public List<object> checkedObjects
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Object}

### conditions

```csharp
public List<Condition> conditions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### doneConditions

```csharp
public List<bool> doneConditions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Boolean}

### failConditions

```csharp
public List<Condition> failConditions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### isCleared

```csharp
public bool isCleared
```
#INC


#### Field Value

**Type:** System.Boolean

### isInProcess

```csharp
public bool isInProcess
```
#INC


#### Field Value

**Type:** System.Boolean

### metaInfo

```csharp
public MissionTypeInfo metaInfo
```
#INC


#### Field Value

**Type:** Global.MissionTypeInfo

### successCondition

```csharp
public Condition successCondition
```
#INC


#### Field Value

**Type:** Global.Condition

## Properties

### isGlobal

```csharp
public bool isGlobal { get; }
```

#### Property Value

**Type:** System.Boolean

### sefira_Name

```csharp
public string sefira_Name { get; }
```

#### Property Value

**Type:** System.String

## Methods

### CheckAgent(AgentModel)

```csharp
private bool CheckAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### CheckConditions(string, params object[])

```csharp
public void CheckConditions(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### CheckCreature(CreatureModel)

```csharp
private bool CheckCreature(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

#### Returns

**Type:** System.Boolean

### CheckDefault(Condition)

```csharp
private bool CheckDefault(Condition condition)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `condition` | `Global.Condition` |  |

#### Returns

**Type:** System.Boolean

### CheckEquipment(EquipmentModel)

```csharp
private bool CheckEquipment(EquipmentModel equip)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `equip` | `Global.EquipmentModel` |  |

#### Returns

**Type:** System.Boolean

### CheckOrdeal(OrdealBase)

```csharp
private bool CheckOrdeal(OrdealBase ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |

#### Returns

**Type:** System.Boolean

### CheckSuccess()

```csharp
private bool CheckSuccess()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckWork(UseSkill)

```csharp
private bool CheckWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Init(MissionTypeInfo)

```csharp
public void Init(MissionTypeInfo metadata)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadata` | `Global.MissionTypeInfo` |  |

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnDisabled()

```csharp
public void OnDisabled()
```
#INC


### OnEnabled()

```csharp
public void OnEnabled()
```
#INC

