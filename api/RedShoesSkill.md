# Class RedShoesSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedShoesSkill : CreatureSpecialSkill, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureSpecialSkill](/api/CreatureSpecialSkill) → RedShoesSkill

## Inherited Members
[model](/api/CreatureSpecialSkill#model), [sefira](/api/CreatureSpecialSkill#sefira), [Activated](/api/CreatureSpecialSkill#activated), [SkillActivate(WorkerModel)](/api/CreatureSpecialSkill#skillactivate-workermodel), [Activate()](/api/CreatureSpecialSkill#activate), [DeActivate()](/api/CreatureSpecialSkill#deactivate), [OnNotice(string, params object[])](/api/CreatureSpecialSkill#onnotice-string-params-object), [OnObserveLevelChanged()](/api/CreatureSpecialSkill#onobservelevelchanged), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### isAcquired

```csharp
public bool isAcquired
```

#### Field Value

**Type:** System.Boolean

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
