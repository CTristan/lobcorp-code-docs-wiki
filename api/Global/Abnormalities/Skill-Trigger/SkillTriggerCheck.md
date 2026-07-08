---
uid: Global.SkillTriggerCheck
canonical_path: /api/Global/Misc/SkillTriggerCheck
---
# Class SkillTriggerCheck
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTriggerCheck
```
> This section may have incomplete or incorrect information.
{.is-warning}

Activates [SkillTrigger](/api/Global/Misc/SkillTrigger)s on entering a room.

Seems like they intended to have it check on room exit as well, but since this whole system is only "used" by [Beauty and the Beast](/api/Global/Misc/BeautyBeast), I guess they never implemented that. ^\[weird\]^



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTriggerCheck

## Constructors
### SkillTriggerCheck()
```csharp
public SkillTriggerCheck()
```


## Fields
### creatureBaseType
```csharp
private Type creatureBaseType
```


#### Field Value
**Type:** System.Type

### onEnterRoom
```csharp
public List<SkillTrigger> onEnterRoom
```


#### Field Value
**Type:** System.Collections.Generic.List{SkillTrigger}

### onExitRoom
```csharp
public List<SkillTrigger> onExitRoom
```


#### Field Value
**Type:** System.Collections.Generic.List{SkillTrigger}

### script
```csharp
private CreatureBase script
```


#### Field Value
**Type:** Global.CreatureBase

### total
```csharp
public List<SkillTrigger> total
```


#### Field Value
**Type:** System.Collections.Generic.List{SkillTrigger}

## Methods
### OnActivated()
```csharp
public void OnActivated()
```


### roomEnterCheck(UseSkill)
```csharp
public void roomEnterCheck(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### SetScript(CreatureBase)
```csharp
public void SetScript(CreatureBase script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CreatureBase` |  |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)




