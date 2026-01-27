---
uid: Legacy.DeathAngelApostle
canonical_path: /api/Legacy/DeathAngelApostle
---

# Class DeathAngelApostle

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelApostle : ISerializablePlayData
```

Parent class for apostles for [WhiteNight](/api/Legacy/DeathAngel)'s advent.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeathAngelApostle

## Implements
[ISerializablePlayData](/api/Global/Misc/ISerializablePlayData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngelApostle()

```csharp
public DeathAngelApostle()
```

## Fields

### adventTarget

```csharp
public WorkerModel adventTarget
```

#### Field Value

**Type:** Global.WorkerModel

### angelFall0

```csharp
public const string angelFall0 = "creature/deathangel/Lucifer_yaduafinish_rise"
```

#### Field Value

**Type:** System.String

### angelFall1

```csharp
public const string angelFall1 = "creature/deathangel/Lucifer_yaduafinish_poof"
```

#### Field Value

**Type:** System.String

### dataSave

```csharp
public long dataSave
```

#### Field Value

**Type:** System.Int64

### hairSprite

```csharp
public Sprite hairSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### hairSpriteSrc

```csharp
public string hairSpriteSrc
```

#### Field Value

**Type:** System.String

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

### isAgent

```csharp
public bool isAgent
```

#### Field Value

**Type:** System.Boolean

### isBetrayer

```csharp
public bool isBetrayer
```

#### Field Value

**Type:** System.Boolean

### isCustomHair

```csharp
public bool isCustomHair
```

#### Field Value

**Type:** System.Boolean

### laserReady

```csharp
public const string laserReady = "creature/deathangel/Lucifer_Apostle_laserCharge"
```

#### Field Value

**Type:** System.String

### name

```csharp
public AgentName name
```

#### Field Value

**Type:** Global.AgentName

### onebadmanyGoolSkill

```csharp
private const long onebadmanyGoolSkill = 40003
```

#### Field Value

**Type:** System.Int64

### plagueDoctorSkill

```csharp
private const long plagueDoctorSkill = 40005
```

#### Field Value

**Type:** System.Int64

### replaceTarget

```csharp
public bool replaceTarget
```

#### Field Value

**Type:** System.Boolean

### standingSound

```csharp
public static string[] standingSound
```

#### Field Value

**Type:** System.String[]

## Methods

### Advent(DeathAngel, int)

```csharp
public DeathAngel.Apostle Advent(DeathAngel angel, int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angel` | `Legacy.DeathAngel` |  |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Legacy.DeathAngel.Apostle

### FindOtherTarget(int)

```csharp
public static List<WorkerModel> FindOtherTarget(int neededCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `neededCount` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadWorkerData()

```csharp
public void LoadWorkerData()
```

### SetAgent(AgentModel, bool)

```csharp
public void SetAgent(AgentModel agent, bool bet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `bet` | `System.Boolean` |  |

### SetWorker(WorkerModel)

```csharp
public void SetWorker(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
