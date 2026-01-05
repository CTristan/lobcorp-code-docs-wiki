# Class OrdealBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OrdealBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OrdealBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OrdealBase()

```csharp
public OrdealBase()
```

## Fields

### isStarted

```csharp
public bool isStarted
```

#### Field Value

**Type:** System.Boolean

### level

```csharp
public OrdealLevel level
```

#### Field Value

**Type:** Global.OrdealLevel

### OrdealColor

```csharp
public Color OrdealColor
```

#### Field Value

**Type:** UnityEngine.Color

### ordealRewards

```csharp
public readonly int[] ordealRewards
```

#### Field Value

**Type:** System.Int32[]

### startTime

```csharp
public int startTime
```

#### Field Value

**Type:** System.Int32

## Properties

### canTakeRewards

```csharp
public bool canTakeRewards { protected get; set; }
```

#### Property Value

**Type:** System.Boolean

### OrdealTypeText

```csharp
public virtual string OrdealTypeText { get; }
```

#### Property Value

**Type:** System.String

## Methods

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```

### GetRiskLevel(OrdealCreatureModel)

```csharp
public virtual RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** Global.RiskLevel

### IsStartable()

```csharp
public virtual bool IsStartable()
```

#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnGameInit()

```csharp
public virtual void OnGameInit()
```

### OnOrdealStart()

```csharp
public virtual void OnOrdealStart()
```

### OrdealEnd()

```csharp
public virtual void OrdealEnd()
```

### OrdealNameText(OrdealCreatureModel)

```csharp
public virtual string OrdealNameText(OrdealCreatureModel ordeal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** System.String

### OrdealTypo(string, Color, bool, int)

```csharp
public virtual void OrdealTypo(string ordealName, Color color, bool isStart = true, int reward = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordealName` | `System.String` |  |
| `color` | `UnityEngine.Color` |  |
| `isStart` | `System.Boolean` |  |
| `reward` | `System.Int32` |  |

### SetRiskLevel(RiskLevel)

```csharp
public void SetRiskLevel(RiskLevel value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `Global.RiskLevel` |  |
