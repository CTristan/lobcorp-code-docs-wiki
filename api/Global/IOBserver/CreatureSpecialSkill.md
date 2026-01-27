---
uid: Global.CreatureSpecialSkill
canonical_path: /api/Global/IOBserver/CreatureSpecialSkill
---

# Class CreatureSpecialSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSpecialSkill : IObserver
```

Seems to be used for Red Shoes and Singing Machine's possessions, and maybe literally nothing else. But it shows up all over the place because Red Shoes is strange.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSpecialSkill

## Derived
[RedShoesSkill](/api/Global/Creature/RedShoesSkill), [SingingMachineSkill](/api/Global/Creature/SingingMachineSkill)

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSpecialSkill()

```csharp
public CreatureSpecialSkill()
```
#INC
#code-generated


### CreatureSpecialSkill(CreatureModel)

```csharp
public CreatureSpecialSkill(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

## Fields

### Activated

```csharp
public bool Activated
```
#INC


#### Field Value

**Type:** System.Boolean

### model

```csharp
public CreatureModel model
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### sefira

```csharp
public Sefira sefira
```
#INC


#### Field Value

**Type:** Global.Sefira

## Methods

### Activate()

```csharp
public virtual void Activate()
```
#INC


### DeActivate()

```csharp
public virtual void DeActivate()
```
#INC


### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnObserveLevelChanged()

```csharp
public virtual void OnObserveLevelChanged()
```
#INC


### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public virtual void OnStageStart()
```
#INC


### SkillActivate()

```csharp
public virtual void SkillActivate()
```
#INC


### SkillActivate(WorkerModel)

```csharp
public virtual void SkillActivate(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
