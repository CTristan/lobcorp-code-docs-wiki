---
uid: Global.PlayerModel.EmergencyController
canonical_path: /api/Global/Misc/PlayerModelEmergencyController
---

# Class PlayerModel.EmergencyController

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlayerModel.EmergencyController
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PlayerModel.EmergencyController

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EmergencyController()

```csharp
public EmergencyController()
```

## Fields

### _currentLevel

```csharp
private EmergencyLevel _currentLevel
```

#### Field Value

**Type:** Global.EmergencyLevel

### _currentScore

```csharp
private float _currentScore
```

#### Field Value

**Type:** System.Single

### ALEPH

```csharp
public static float ALEPH
```

#### Field Value

**Type:** System.Single

### emergecyID

```csharp
private List<long> emergecyID
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int64}

### HE

```csharp
public static float HE
```

#### Field Value

**Type:** System.Single

### Range

```csharp
public static int[] Range
```

#### Field Value

**Type:** System.Int32[]

### TETH

```csharp
public static float TETH
```

#### Field Value

**Type:** System.Single

### WAW

```csharp
public static float WAW
```

#### Field Value

**Type:** System.Single

### ZAYIN

```csharp
public static float ZAYIN
```

#### Field Value

**Type:** System.Single

## Properties

### currentLevel

```csharp
public EmergencyLevel currentLevel { get; set; }
```

#### Property Value

**Type:** Global.EmergencyLevel

### currentScore

```csharp
private float currentScore { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### AddScore(CreatureModel)

```csharp
public void AddScore(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### AddScore(float)

```csharp
public void AddScore(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### AddScore(RiskLevel)

```csharp
public void AddScore(RiskLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### Apply(long)

```csharp
public void Apply(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### Exit(long)

```csharp
public void Exit(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### GetCurrentScore()

```csharp
public float GetCurrentScore()
```

#### Returns

**Type:** System.Single

### GetLevelScore(RiskLevel)

```csharp
public float GetLevelScore(RiskLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns

**Type:** System.Single

### GetScore(CreatureModel)

```csharp
public float GetScore(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

#### Returns

**Type:** System.Single

### GetScore(RiskLevel)

```csharp
public float GetScore(RiskLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns

**Type:** System.Single

### Init()

```csharp
public void Init()
```

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### Print()

```csharp
public void Print()
```

### ReduceSore(float)

```csharp
public void ReduceSore(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetCurrentScore(float)

```csharp
public void SetCurrentScore(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetLevel()

```csharp
private void SetLevel()
```
