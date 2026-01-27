---
uid: Global.RandomEventBase
canonical_path: /api/Global/Misc/RandomEventBase
---

# Class RandomEventBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventBase
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventBase

## Derived
[BoomerCircusEvent](/api/Global/Event/BoomerCircusEvent), [BugsForFoodEvent](/api/Global/Event/BugsForFoodEvent), [FallingLegEvent](/api/Global/Event/FallingLegEvent), [FloodRestArmEvent](/api/Global/Event/FloodRestArmEvent), [HordeOfBugs](/api/Global/Misc/HordeOfBugs)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RandomEventBase()

```csharp
public RandomEventBase()
```

## Fields

### _isEnabled

```csharp
protected bool _isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### enableCheckConditions

```csharp
public List<RandomEventBase.Condition> enableCheckConditions
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase.Condition}

### instanceId

```csharp
public long instanceId
```
#INC


#### Field Value

**Type:** System.Int64

### metaInfo

```csharp
public RandomEventInfo metaInfo
```
#INC


#### Field Value

**Type:** Global.RandomEventInfo

### rank

```csharp
public RandomEventRank rank
```
#INC


#### Field Value

**Type:** Global.RandomEventRank

### rootGameObject

```csharp
public GameObject rootGameObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### rootObjectId

```csharp
public const long rootObjectId = 1000
```
#INC


#### Field Value

**Type:** System.Int64

### rootObjectSrc

```csharp
public const string rootObjectSrc = "StandingItem/RandomEventRoot"
```
#INC


#### Field Value

**Type:** System.String

### rootStanding

```csharp
public RandomEventRoot rootStanding
```
#INC


#### Field Value

**Type:** Global.RandomEventRoot

### type

```csharp
public RandomEventType type
```
#INC


#### Field Value

**Type:** Global.RandomEventType

## Properties

### HasRootObject

```csharp
public bool HasRootObject { get; }
```

#### Property Value

**Type:** System.Boolean

### IsEnabled

```csharp
public bool IsEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

### MetaDataId

```csharp
public virtual long MetaDataId { get; }
```

#### Property Value

**Type:** System.Int64

### RootTransform

```csharp
public Transform RootTransform { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### CheckCondition()

```csharp
public virtual void CheckCondition()
```
#INC


### CheckEquivalent(string)

```csharp
public bool CheckEquivalent(string script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### GenerateCondition()

```csharp
public virtual void GenerateCondition()
```
#INC


### GenerateCondition(ConditionInfo, ref List<int>)

```csharp
public RandomEventBase.Condition GenerateCondition(RandomEventInfo.ConditionInfo info, ref List<int> cont)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.RandomEventInfo.ConditionInfo` |  |
| `cont` | `System.Collections.Generic.List{System.Int32}` |  |

#### Returns

**Type:** Global.RandomEventBase.Condition

### GenerateTypo(string)

```csharp
public virtual void GenerateTypo(string message)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `message` | `System.String` |  |

### GenerateTypo(TypoType)

```csharp
public virtual void GenerateTypo(RandomEventBase.TypoType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RandomEventBase.TypoType` |  |

### GenerateTypo(TypoType, string)

```csharp
public virtual void GenerateTypo(RandomEventBase.TypoType type, string sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RandomEventBase.TypoType` |  |
| `sound` | `System.String` |  |

### GetCondition(string)

```csharp
public static EnableCondition GetCondition(string condition)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `condition` | `System.String` |  |

#### Returns

**Type:** Global.EnableCondition

### GetTimerCondition()

```csharp
public RandomEventBase.Condition GetTimerCondition()
```

#### Returns

**Type:** Global.RandomEventBase.Condition

### IsDuplicatable()

```csharp
public bool IsDuplicatable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeRootObject()

```csharp
public void MakeRootObject()
```
#INC


### ManualDisable()

```csharp
public virtual void ManualDisable()
```
#INC


### ManualDisable(string)

```csharp
public virtual void ManualDisable(string sound)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `System.String` |  |

### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnDisable()

```csharp
public virtual void OnDisable()
```
#INC


### OnEnable()

```csharp
public virtual void OnEnable()
```
#INC


### OnEnd()

```csharp
public virtual void OnEnd()
```
#INC


### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```
#INC


### OnInit()

```csharp
public virtual void OnInit()
```
#INC
#code-generated


### OnUpdate()

```csharp
public virtual void OnUpdate()
```
#INC


### SetTimerConditionTime(float)

```csharp
public void SetTimerConditionTime(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
