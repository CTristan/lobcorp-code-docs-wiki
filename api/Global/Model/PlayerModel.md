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
Holds some state for the current playthrough.

Responsible for:
- Abnormality queue (for extraction)
- Day information (including changing days, saving and loading the current day, keeping track of Day 47-49 game overs, and memory repository days #inc)

Provides access to:
- The list of opened departments (see [SefiraManager](/api/Global/IOBserver/SefiraManager))
- Opening all departments for unlimited mode (called by [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager))

Also, has the EmergencyController in it, which controls the current trumpet.


## Methods

### Core
#### void Init()
Resets game-overs, memory repository, sets day to 0, and clears the queue of waiting creatures[^1]. #inc

[^1]: Does not use InitAddingCreatures
#### public Dictionary\<string, object> GetSaveData()
Returns a dictionary with one key, "day", with the value of the current day.
#### public void LoadData(Dictionary\<string, object> dic)
Unflags the Day 47-49 game over flag (and the unused memoryInit flag), then reads the day from the provided data.
### Abnormality Queue
#### public void InitAddingCreatures()
Clears the queue of waiting abnormalities. Used by title Day 1 resets and total resets. #INC 
#### public void AddWaitingCreature(long id)
Queues the abnormality with the given id.
Used by the [abnormality extraction UI](/api/Global/IANimatorEventCalled/CreatureSelectUI), [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager) (to load save data), and [ConsoleCommand](/api/Global/Misc/ConsoleCommand) for the fifo command.
#### public bool GetWaitingCreature(out long id)
If the queue is empty, returns false and sets id to -1.
Otherwise, removes the first abnormality from the queue and sets id to its id, then saves the new queue to file with [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager) (if the save file exists).
#### public List\<long> CopyWaitingCreatures()
Returns a list of the waiting abnormalities.
#### public bool IsWaitingCreaturesExist()
Returns true if there are enough abnormalities in the queue for the day.
Between days 20-24 and 45-49 (inclusive), this returns true if there are 2 or more abnormalities in the queue; on every other day, checks for at least 1 abnormality.
#### public bool IsWaitingCreature(long id)
Returns true if the given id belongs to an abnormality in the current queue.

### Day
#### public void SetDay(int day)
Sets the day to the given value and notifies all listeners of UpdateDay.
#### public void Nextday()
Increments the day, sets a flag in [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager) to indicate the day is no longer a loaded day (see [DeployUI](/api/Global/UI/DeployUI) for its only usage), and notifies all listeners of UpdateDay.
#### public int GetDay()
Returns the current day.
### Misc
#### public Sefira[] GetOpenedAreaList()
Returns an array of all opened departments, via [SefiraManager](/api/Global/IOBserver/SefiraManager).
#### public int GetOpenedAreaCount()
Returns the number of opened departments via [SefiraManager](/api/Global/IOBserver/SefiraManager).
#### public void SetKetherGameOver()
Sets the Day 47-49 game over flag.
#### public void UnlimitMode(string saveVer)
Opens all departments (or just the Asiyah and Briah ones, if the save file is old).
#### public void Remember()
Sets an unused 'memoryInit' flag.
### Unused
#### private void TempMakeCreature()
Debug tool to open Asiyah and Briah with abnormalities in them. Not used.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PlayerModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PlayerModel()

```csharp
private PlayerModel()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static PlayerModel _instance
```
#INC


#### Field Value

**Type:** Global.PlayerModel

### _ketherGameOver

```csharp
private bool _ketherGameOver
```
#INC


#### Field Value

**Type:** System.Boolean

### _memoryInit

```csharp
private bool _memoryInit
```
#INC


#### Field Value

**Type:** System.Boolean

### addedCreature

```csharp
public Queue<long> addedCreature
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{System.Int64}

### currentEmergencyLevel

```csharp
public EmergencyLevel currentEmergencyLevel
```
#INC


#### Field Value

**Type:** Global.EmergencyLevel

### day

```csharp
private int day
```
#INC


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
#INC


#### Field Value

**Type:** System.Int32

### nullcreature

```csharp
private const long nullcreature = 100005
```
#INC


#### Field Value

**Type:** System.Int64

### orchestra

```csharp
private const long orchestra = 100019
```
#INC


#### Field Value

**Type:** System.Int64

### playerSpot

```csharp
public Vector3 playerSpot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### Second

```csharp
private const int Second = 20
```
#INC


#### Field Value

**Type:** System.Int32

### Third

```csharp
private const int Third = 30
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### CopyWaitingCreatures()

```csharp
public List<long> CopyWaitingCreatures()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### GetDay()

```csharp
public int GetDay()
```
#INC


#### Returns

**Type:** System.Int32

### GetOpenedAreaCount()

```csharp
public int GetOpenedAreaCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetOpenedAreaList()

```csharp
public Sefira[] GetOpenedAreaList()
```
#INC


#### Returns

**Type:** Global.Sefira[]

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWaitingCreature(out long)

```csharp
public bool GetWaitingCreature(out long id)
```
#INC


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
#INC


### InitAddingCreatures()

```csharp
public void InitAddingCreatures()
```
#INC


### IsWaitingCreature(long)

```csharp
public bool IsWaitingCreature(long id)
```
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### Nextday()

```csharp
public void Nextday()
```
#INC


### Remember()

```csharp
public void Remember()
```
#INC


### SetDay(int)

```csharp
public void SetDay(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

### SetKetherGameOver()

```csharp
public void SetKetherGameOver()
```
#INC


### TempMakeCreature()

```csharp
private void TempMakeCreature()
```
#INC


### UnlimitMode(string)

```csharp
public void UnlimitMode(string saveVer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `saveVer` | `System.String` |  |
