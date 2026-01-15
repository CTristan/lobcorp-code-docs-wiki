---
uid: Global.PlayerModel
canonical_path: /api/Global/Model/PlayerModel
---

# Class PlayerModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlayerModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PlayerModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PlayerModel()

```csharp
private PlayerModel()
```

## Fields

### _instance

```csharp
private static PlayerModel _instance
```

#### Field Value

**Type:** Global.PlayerModel

### _ketherGameOver

```csharp
private bool _ketherGameOver
```

#### Field Value

**Type:** System.Boolean

### _memoryInit

```csharp
private bool _memoryInit
```

#### Field Value

**Type:** System.Boolean

### addedCreature

```csharp
public Queue<long> addedCreature
```

#### Field Value

**Type:** System.Collections.Generic.Queue{System.Int64}

### currentEmergencyLevel

```csharp
public EmergencyLevel currentEmergencyLevel
```

#### Field Value

**Type:** Global.EmergencyLevel

### day

```csharp
private int day
```

#### Field Value

**Type:** System.Int32

### emergencyController

```csharp
public static PlayerModel.EmergencyController emergencyController
```

#### Field Value

**Type:** Global.PlayerModel.EmergencyController

### First

```csharp
private const int First = 10
```

#### Field Value

**Type:** System.Int32

### nullcreature

```csharp
private const long nullcreature = 100005
```

#### Field Value

**Type:** System.Int64

### orchestra

```csharp
private const long orchestra = 100019
```

#### Field Value

**Type:** System.Int64

### playerSpot

```csharp
public Vector3 playerSpot
```

#### Field Value

**Type:** UnityEngine.Vector3

### Second

```csharp
private const int Second = 20
```

#### Field Value

**Type:** System.Int32

### Third

```csharp
private const int Third = 30
```

#### Field Value

**Type:** System.Int32

## Properties

### instance

```csharp
public static PlayerModel instance { get; }
```

#### Property Value

**Type:** Global.PlayerModel

### ketherGameOver

```csharp
public bool ketherGameOver { get; }
```

#### Property Value

**Type:** System.Boolean

### memoryInit

```csharp
public bool memoryInit { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddWaitingCreature(long)

```csharp
public void AddWaitingCreature(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### CopyWaitingCreatures()

```csharp
public List<long> CopyWaitingCreatures()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### GetDay()

```csharp
public int GetDay()
```

#### Returns

**Type:** System.Int32

### GetOpenedAreaCount()

```csharp
public int GetOpenedAreaCount()
```

#### Returns

**Type:** System.Int32

### GetOpenedAreaList()

```csharp
public Sefira[] GetOpenedAreaList()
```

#### Returns

**Type:** Global.Sefira[]

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWaitingCreature(out long)

```csharp
public bool GetWaitingCreature(out long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public void Init()
```

### InitAddingCreatures()

```csharp
public void InitAddingCreatures()
```

### IsWaitingCreature(long)

```csharp
public bool IsWaitingCreature(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### IsWaitingCreatureExist()

```csharp
public bool IsWaitingCreatureExist()
```

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### Nextday()

```csharp
public void Nextday()
```

### Remember()

```csharp
public void Remember()
```

### SetDay(int)

```csharp
public void SetDay(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

### SetKetherGameOver()

```csharp
public void SetKetherGameOver()
```

### TempMakeCreature()

```csharp
private void TempMakeCreature()
```

### UnlimitMode(string)

```csharp
public void UnlimitMode(string saveVer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveVer` | `System.String` |  |
