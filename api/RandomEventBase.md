# Class RandomEventBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Int64

### metaInfo

```csharp
public RandomEventInfo metaInfo
```

#### Field Value

**Type:** Global.RandomEventInfo

### rank

```csharp
public RandomEventRank rank
```

#### Field Value

**Type:** Global.RandomEventRank

### rootGameObject

```csharp
public GameObject rootGameObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### rootObjectId

```csharp
public const long rootObjectId = 1000
```

#### Field Value

**Type:** System.Int64

### rootObjectSrc

```csharp
public const string rootObjectSrc = "StandingItem/RandomEventRoot"
```

#### Field Value

**Type:** System.String

### rootStanding

```csharp
public RandomEventRoot rootStanding
```

#### Field Value

**Type:** Global.RandomEventRoot

### type

```csharp
public RandomEventType type
```

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

### CheckEquivalent(string)

```csharp
public bool CheckEquivalent(string script)
```

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

#### Returns

**Type:** System.Boolean

### MakeRootObject()

```csharp
public void MakeRootObject()
```

### ManualDisable()

```csharp
public virtual void ManualDisable()
```

### ManualDisable(string)

```csharp
public virtual void ManualDisable(string sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `System.String` |  |

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnDisable()

```csharp
public virtual void OnDisable()
```

### OnEnable()

```csharp
public virtual void OnEnable()
```

### OnEnd()

```csharp
public virtual void OnEnd()
```

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```

### OnInit()

```csharp
public virtual void OnInit()
```

### OnUpdate()

```csharp
public virtual void OnUpdate()
```

### SetTimerConditionTime(float)

```csharp
public void SetTimerConditionTime(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
