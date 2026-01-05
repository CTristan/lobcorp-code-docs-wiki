# Class RandomEventBase.Condition

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventBase.Condition
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventBase.Condition

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Condition()

```csharp
public Condition()
```

## Fields

### afterTimer

```csharp
public Timer afterTimer
```

#### Field Value

**Type:** Global.Timer

### condition

```csharp
public EnableCondition condition
```

#### Field Value

**Type:** Global.EnableCondition

### energy

```csharp
public float energy
```

#### Field Value

**Type:** System.Single

### isIterative

```csharp
public bool isIterative
```

#### Field Value

**Type:** System.Boolean

### prevCheck

```csharp
public List<RandomEventBase.Condition> prevCheck
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventBase.Condition}

### prob

```csharp
public float prob
```

#### Field Value

**Type:** System.Single

### probFreq

```csharp
public float probFreq
```

#### Field Value

**Type:** System.Single

### satisfied

```csharp
public bool satisfied
```

#### Field Value

**Type:** System.Boolean

### time

```csharp
public float time
```

#### Field Value

**Type:** System.Single

## Methods

### Check()

```csharp
public bool Check()
```

#### Returns

**Type:** System.Boolean

### Init(ConditionInfo)

```csharp
public void Init(RandomEventInfo.ConditionInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.RandomEventInfo.ConditionInfo` |  |

### Init(EnableCondition, params float[])

```csharp
public void Init(EnableCondition condition, params float[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `condition` | `Global.EnableCondition` |  |
| `param` | `System.Single[]` |  |

### SetTimer(float)

```csharp
public void SetTimer(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
