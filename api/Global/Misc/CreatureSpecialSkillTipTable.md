---
uid: Global.CreatureSpecialSkillTipTable
canonical_path: /api/Global/Misc/CreatureSpecialSkillTipTable
---

# Class CreatureSpecialSkillTipTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSpecialSkillTipTable
```
Stores these [CreatureSpecialSkillDesc](/api/Global/Misc/CreatureSpecialSkillDesc) objects...
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSpecialSkillTipTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSpecialSkillTipTable(long)

```csharp
public CreatureSpecialSkillTipTable(long creatureTypeId)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureTypeId` | `System.Int64` |  |

## Fields

### creatureTypeId

```csharp
public long creatureTypeId
```
#INC


#### Field Value

**Type:** System.Int64

### descList

```csharp
public List<CreatureSpecialSkillDesc> descList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureSpecialSkillDesc}

## Methods

### ActivateDesc(CreatureModel, string, params object[])

```csharp
public void ActivateDesc(CreatureModel model, string key, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `key` | `System.String` |  |
| `param` | `System.Object[]` |  |

### GetCopy()

```csharp
public CreatureSpecialSkillTipTable GetCopy()
```
#INC


#### Returns

**Type:** Global.CreatureSpecialSkillTipTable

### GetDesc(string)

```csharp
public CreatureSpecialSkillDesc GetDesc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureSpecialSkillDesc

### GetSaveGlobalData()

```csharp
public Dictionary<string, object> GetSaveGlobalData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Init()

```csharp
public void Init()
```
#INC


### LoadGlobalData(Dictionary<string, object>, int)

```csharp
public void LoadGlobalData(Dictionary<string, object> dic, int count)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `count` | `System.Int32` |  |

### OnCreatureNameRevealed(CreatureModel)

```csharp
public void OnCreatureNameRevealed(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
