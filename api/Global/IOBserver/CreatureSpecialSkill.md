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

### CreatureSpecialSkill(CreatureModel)

```csharp
public CreatureSpecialSkill(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

## Fields

### Activated

```csharp
public bool Activated
```

#### Field Value

**Type:** System.Boolean

### model

```csharp
public CreatureModel model
```

#### Field Value

**Type:** Global.CreatureModel

### sefira

```csharp
public Sefira sefira
```

#### Field Value

**Type:** Global.Sefira

## Methods

### Activate()

```csharp
public virtual void Activate()
```

### DeActivate()

```csharp
public virtual void DeActivate()
```

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnObserveLevelChanged()

```csharp
public virtual void OnObserveLevelChanged()
```

### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```

### OnStageStart()

```csharp
public virtual void OnStageStart()
```

### SkillActivate()

```csharp
public virtual void SkillActivate()
```

### SkillActivate(WorkerModel)

```csharp
public virtual void SkillActivate(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
