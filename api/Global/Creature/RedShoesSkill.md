---
uid: Global.RedShoesSkill
canonical_path: /api/Global/Creature/RedShoesSkill
---

# Class RedShoesSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedShoesSkill : CreatureSpecialSkill, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureSpecialSkill](/api/Global/IOBserver/CreatureSpecialSkill) → RedShoesSkill

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[model](/api/Global/IOBserver/CreatureSpecialSkill#model), [sefira](/api/Global/IOBserver/CreatureSpecialSkill#sefira), [Activated](/api/Global/IOBserver/CreatureSpecialSkill#activated), [SkillActivate(WorkerModel)](/api/Global/IOBserver/CreatureSpecialSkill#skillactivate-workermodel), [Activate()](/api/Global/IOBserver/CreatureSpecialSkill#activate), [DeActivate()](/api/Global/IOBserver/CreatureSpecialSkill#deactivate), [OnNotice(string, params object[])](/api/Global/IOBserver/CreatureSpecialSkill#onnotice-string-params-object), [OnObserveLevelChanged()](/api/Global/IOBserver/CreatureSpecialSkill#onobservelevelchanged), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RedShoesSkill(CreatureModel)

```csharp
public RedShoesSkill(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

## Fields

### attracted

```csharp
public bool attracted
```

#### Field Value

**Type:** System.Boolean

### attractTargetAgent

```csharp
public WorkerModel attractTargetAgent
```

#### Field Value

**Type:** Global.WorkerModel

### elapsed

```csharp
private float elapsed
```

#### Field Value

**Type:** System.Single

### frequencey

```csharp
private const float frequencey = 30
```

#### Field Value

**Type:** System.Single

### isAcquired

```csharp
public bool isAcquired
```

#### Field Value

**Type:** System.Boolean

### targetList

```csharp
private List<WorkerModel> targetList
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

## Methods

### Attract(WorkerModel)

```csharp
public void Attract(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AttractInIsolate(AgentModel)

```csharp
public void AttractInIsolate(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### DropShoes()

```csharp
public void DropShoes()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### FreeAttractedAgent(WorkerModel)

```csharp
public void FreeAttractedAgent(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### GetRedShoes(int)

```csharp
public void GetRedShoes(int startType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startType` | `System.Int32` |  |

### GetTargetList()

```csharp
private List<WorkerModel> GetTargetList()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### IObserver.OnNotice(string, params object[])

```csharp
void IObserver.OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### IsAtivatedForcely()

```csharp
public bool IsAtivatedForcely()
```

#### Returns

**Type:** System.Boolean

### OnInfectedTargetTerminated()

```csharp
public void OnInfectedTargetTerminated()
```

### OnKill()

```csharp
public void OnKill()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### SetSuppressed(List<AgentModel>)

```csharp
public void SetSuppressed(List<AgentModel> suppressors)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `suppressors` | `System.Collections.Generic.List{AgentModel}` |  |

### SkillActivate()

```csharp
public override void SkillActivate()
```

### TryAttract()

```csharp
public void TryAttract()
```
