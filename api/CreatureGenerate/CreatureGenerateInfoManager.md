---
title: CreatureGenerateInfoManager
description: 
published: true
date: 2026-07-16T16:36:30.786Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:18.860Z
---

# Class CreatureGenerateInfoManager
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateInfoManager
```
> This section may have incomplete or incorrect information.
{.is-warning}

With [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI), handles abnormality extraction:

- Loads information from `xml/CreatureGenInfo.xml` to determine door probabilities based on the day
- Stores lists of abnormalities by risk level ([`ActivateStateList`](/api/CreatureGenerate/ActivateStateList))
- Updates lists to maintain selectable abnormalities

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureGenerateInfoManager

## Constructors
### CreatureGenerateInfoManager()
```csharp
public CreatureGenerateInfoManager()
```

## Fields
### \_genDay
```csharp
private int _genDay
```
The effective day for the abnormality selection. See `CalculateDay` for when this is not the same as the current day.

#### Field Value
**Type:** System.Int32

### \_genKit
```csharp
private bool _genKit
```
A flag indicating whether today is a tool abnormality day.

#### Field Value
**Type:** System.Boolean

### \_instance
```csharp
private static CreatureGenerateInfoManager _instance
```
The `CreatureGenerateInfoManager` instance for the singleton pattern.

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateInfoManager

### \_isInitiated
```csharp
private bool _isInitiated
```
Flag indicating if this class has been initialized.

#### Field Value
**Type:** System.Boolean

### \_isLoadedDayData
```csharp
private bool _isLoadedDayData
```
Flag indicating if the abnormality selection data has been loaded.

#### Field Value
**Type:** System.Boolean

### activateStateDic
```csharp
public Dictionary<RiskLevel, ActivateStateList> activateStateDic
```
Dictionary matching each risk level to its [ActivateStateList](/api/CreatureGenerate/ActivateStateList).

#### Field Value
**Type:** System.Collections.Generic.Dictionary{RiskLevel,CreatureGenerate.ActivateStateList}

### CreatureList
```csharp
public Dictionary<RiskLevel, List<long>> CreatureList
```
Dictionary matching each risk level to the list of all abnormalities of that risk level.

#### Field Value
**Type:** System.Collections.Generic.Dictionary{RiskLevel,System.Collections.Generic.List{System.Int64}}

### dayGenInfoDic
```csharp
public Dictionary<int, CreatureGenerateModel> dayGenInfoDic
```
A dictionary associating most days with a [CreatureGenerateModel](/api/CreatureGenerate/CreatureGenerateModel) describing the probabilities and restrictions for the day.

#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.Int32,CreatureGenerate.CreatureGenerateModel}

### DebugPrefix
```csharp
private const string DebugPrefix = "<color=#FF2323>[CreatureGenerate]</color> "
```
The prefix to prepend to all logs from this script.

#### Field Value
**Type:** System.String

### GenerateCommonActionList
```csharp
public List<string> GenerateCommonActionList
```
Contains the actions `"remove"` and `"only"`, used to restrict abnormalities on certain days.

#### Field Value
**Type:** System.Collections.Generic.List{System.String}

### GenerateCommonActionString
```csharp
public static readonly string[] GenerateCommonActionString
```
Contains the actions `"remove"` and `"only"`, used to initialize `GenerateCommonActionList`.

#### Field Value
**Type:** System.String[]

### SelectData
```csharp
public Dictionary<int, CreatureSelectData> SelectData
```
Loaded, but unused.

#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.Int32,CreatureGenerate.CreatureSelectData}

### XMLFileSrc
```csharp
private const string XMLFileSrc = "xml/CreatureGenInfo"
```
The location of the extraction information for each day.

#### Field Value
**Type:** System.String

## Properties
### GenDay
```csharp
public int GenDay { get; }
```
Read-only property exposing `_genDay`.

#### Property Value
**Type:** System.Int32

### GenKit
```csharp
public bool GenKit { get; set; }
```
Flag indicating if today is a tool abnormality day. Exposes `_genKit` with no extra behaviour. 

#### Property Value
**Type:** System.Boolean

### Instance
```csharp
public static CreatureGenerateInfoManager Instance { get; }
```
Get-only property for the `CreatureGenerateInfoManager` instance for the singleton pattern.

#### Property Value
**Type:** CreatureGenerate.CreatureGenerateInfoManager

### IsInitiated
```csharp
public bool IsInitiated { get; }
```
Unused get-only flag indicating if this class has been initialized. Exposes `_isInitiated`.


#### Property Value
**Type:** System.Boolean

### IsloadedDayData
```csharp
public bool IsloadedDayData { get; }
```
Returns true if the data is loaded, otherwise tries to load it and returns if it succeeded. Calls `LoadStaticData`.

#### Property Value
**Type:** System.Boolean

## Methods
### CalculateDay()
```csharp
public void CalculateDay()
```
Calculates the effective day for the abnormality extraction. Usually the current day.

###### Details
Sets `_genDay` to the current day.

Also, calculates how many abnormalities should be in the facility as `num2`. This is calculated as `day - day/5`. On Days 21-25, also add extra abnormalities (`day - 20`) to account for the double extraction days.

If the current day is a multiple of 5, set `_genDay` to the current day plus one. :interrobang: If not, and if there are more abnormalities in the facility than there should be, set `_genDay` to the current day plus one. Otherwise, keep `_genDay` as the current day.


### CheckCreatureUseState()
```csharp
private void CheckCreatureUseState()
```
Called by `OnDayChanged`. Updates each `ActivateStateModel` to reflect the abnormalities which can be selected today.

###### Details
Runs `ActivateStateModel::DayUpdate` and `ActivateStateModel::CheckUsableState` on each `ActivateStateModel` in `list`. See [ActivateStateModel](/api/CreatureGenerate/ActivateStateModel) for the what those do.

### CheckGenerationIgnore(long)
```csharp
private bool CheckGenerationIgnore(long id)
```
Always returns false.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` | Ignored. |

#### Returns
**Type:** System.Boolean

### CheckKitCreatureRemains()
```csharp
public bool CheckKitCreatureRemains()
```
Returns true if there are tool abnormalities not currently in the facility. Always true during normal gameplay.

#### Returns
**Type:** System.Boolean

### DebugCheck(int)
```csharp
public void DebugCheck(int day)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

### GetCreature()
```csharp
public List<long> GetCreature()
```
Returns a list of three different abnormalities which can be selected today, fewer if there are not enough available, or else `null` if there is no data for today.

###### Details
Using `genDay` (see `CalculateDay` for when this is not the current day), gets the [`CreatureGenerateModel`](/api/CreatureGenerate/CreatureGenerateModel) for today from `dayGenInfoDic` and stores it in `value`. If it succeeds, gets the three abnormalities by calling [`value.SetCreature`](/api/CreatureGenerate/CreatureGenerateModel). If it fails, it instead returns null.

:interrobang: When trying to call `value.SetCreature` produces a [`ProbCheckExeption`](/api/CreatureGenerate/CreatureGenerateInfoManager/CreatureGenerateInfoManager-ProbCheckExeption), instead tries again using `genDay` set to `-2` (a fall-back with valid data). If another `ProbCheckExeption` is thrown, logs an error and returns :interrobang: whatever is in the `CreatureGenerateModel::creature` value. No code throws the `ProbCheckExeption`, so this cannot ever run.

#### Returns
**Type:** System.Collections.Generic.List{System.Int64}

### GetCreatureNew()
```csharp
public List<long> GetCreatureNew()
```
Unused.

#### Returns
**Type:** System.Collections.Generic.List{System.Int64}

### GetCreatureState(RiskLevel, out ActivateStateList)
```csharp
public bool GetCreatureState(RiskLevel risk, out ActivateStateList list)
```
Sets `list` to the [`ActivateStateList`](/api/CreatureGenerate/ActivateStateList) associated with `risk`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `risk` | `Global.RiskLevel` | The risk level of the list to fetch. |
| `list` | `CreatureGenerate.ActivateStateList` | The resulting list. |

#### Returns
**Type:** System.Boolean

### HasUniqueAction(string[], out int)
```csharp
public bool HasUniqueAction(string[] split, out int index)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `split` | `System.String[]` |  |
| `index` | `System.Int32` |  |

#### Returns
**Type:** System.Boolean

### Init()
```csharp
public void Init()
```
Initializes this class and updates it with the current information.

###### Details
Initializes the list of abnormalities (`CreatureGenerateInfoManager::InitCreatureList`).

Clears `activateStateDic`, the dictionary which associates each risk level to its [`ActivateStateList`](/api/CreatureGenerate/ActivateStateList).

Sets the `_isInitiated` flag to indicate this class has been initialized.

Gets all abnormalities (see [`CreatureGenerateInfo`](/api/Global/Abnormality-Extraction/CreatureGenerateInfo)), then for each of them:
- Gets its data (see [`CreatureTypeInfo::GetData`](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo))
- Gets its risk level
- Checks if it is present in the facility, to be stored in its [`ActivateStateModel`](/api/CreatureGenerate/ActivateStateModel)
- Makes a new [`ActivateStateModel`](/api/CreatureGenerate/ActivateStateModel) for this abnormality
- Stores it in `activateStateDic` in the [`ActivateStateList`](/api/CreatureGenerate/ActivateStateList) with the same risk level
- If no [`ActivateStateList`](/api/CreatureGenerate/ActivateStateList) exists with that risk level, create a new one and add this abnormality, then store it in `activateStateDic`

Updates the state of each abnormality (see `CheckCreatureUseState`).

Checks if the data for the days has been loaded; if not, loads it (see `IsloadedDayData`). Then logs `"Loaded"`. If this fails, logs the error `"Load Fail"`.
	
### InitCreatureList()
```csharp
public void InitCreatureList()
```
Initializes the dictionary `CreatureList`, associating each risk level with the abnormality of that type.

###### Details

Clears any pre-existing data.

Gets a list of all abnormality info as [`CreatureTypeInfo`](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo) from [`CreatureTypeList::GetList`](/api/Global/Abnormalities/CreatureTypeList).

For each abnormality:
- If the risk level of the abnormality does not already exist in `CreatureList`, add a new list for that risk level.
- Add this abnormality to the list associated to its risk level.

### IsUsedCreature(long)
```csharp
private bool IsUsedCreature(long id)
```
Returns true if the abnormality with the given ID is present in the facility.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` | The abnormality to check. |

#### Returns
**Type:** System.Boolean

### LoadDoor(string, out CreatureGenerateDoor)
```csharp
private bool LoadDoor(string parsed, out CreatureGenerateDoor door)
```
Parses a door from `parsed` and puts it in `door`, logging the exception if it fails.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` | The string to parse. |
| `door` | `CreatureGenerate.CreatureGenerateDoor` | The resulting parsed door. |

#### Returns
**Type:** System.Boolean

### LoadStaticData()
```csharp
private bool LoadStaticData()
```
Loads the probabilities and exceptions for each day from `xml/CreatureGenInfo.txt` into `dayGenInfoDic`.

###### Details
Reads from `Assets/Resources/xml/CreatureGenInfo.txt`. This is an XML with the structure
- root
  - day
  	- day: string
    - door1: string
    - door2: string
    - door3: string
    - action: string
  - day ...

This XML is parsed into [`CreatureGenerateModel`](/api/CreatureGenerate/CreatureGenerateModel) and [`CreatureSelectData`](/api/CreatureGenerate/CreatureSelectData) instances, which are put into `dayGenInfoDic` and `SelectData` respectively. `SelectData` is not ever used.

This method parses by iterating over each `day` in `root`. The field `day` is parsed as an `int`, representing the zero-indexed value of the day.

`action` is parsed as either an `ONLY` or `REMOVE` action, followed by a list of abnormality IDs. This represents which abnormalities are exclusively available today, or which ones are not allowed today, respectively. Only one of these actions can be present on a given day.

Each `door` is parsed as a list of five probabilities between 0 and 1, one for each risk level. See [`CreatureGenerateDoor::Parse(string)`](/api/CreatureGenerate/CreatureGenerateDoor#parsestring) for details.

Once all of the data has been parsed for a day, if any of the doors were present in the file (regardless of their contents), the day is considered valid and the [`CreatureGenerateModel`](/api/CreatureGenerate/CreatureGenerateModel) and [`CreatureSelectData`](/api/CreatureGenerate/CreatureSelectData) instances are added to `dayGenInfoDic` and `SelectData` respectively.

#### Returns
**Type:** System.Boolean

### Log(string, bool)
```csharp
public static void Log(string text, bool isError = false)
```
Logs the given text to either `Debug.Log` or `Debug.LogError` depending on `isError`. Prepends `"[CreatureGenerate] "` to the message in the color `#FF2323`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` | The text to log. |
| `isError` | `System.Boolean` | Flag indicating if this log is an error. |

### OnDayChanged()
```csharp
public void OnDayChanged()
```
Updates each of the [`ActivateStateLists`](/api/CreatureGenerate/ActivateStateList) in `activateStateDic` for the day. Called by [`CreatureSelectUI::GetCreatureList`](/api/Global/Abnormality-Extraction/CreatureSelectUI).

###### Details
Calls  [`ActivateStateList::DayUpdate`](/api/CreatureGenerate/ActivateStateList) and  [`ActivateStateLists::CheckUsableState`](/api/CreatureGenerate/ActivateStateList) on each of the  [`ActivateStateLists`](/api/CreatureGenerate/ActivateStateList).


### OnUsed(long)
```csharp
public void OnUsed(long id)
```
Marks the given abnormality as present in the facility. Note that this does *not* work on days without valid data, as they incorrectly ignore this flag.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` | The abnormality ID to mark as used. |

### ParseDoor(string)
```csharp
private List<float> ParseDoor(string text)
```
Parses a string into a list of floats; used for constructing `SelectData`, which **is not used** once constructed.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` | The string to parse. |

#### Returns
**Type:** System.Collections.Generic.List{System.Single}

### Print()
```csharp
public void Print()
```
Does nothing.

### RemoveAction(long)
```csharp
public void RemoveAction(long id)
```
Unused. See [`CreatureGenerateDoor::RemoveAction`](/api/CreatureGenerate/CreatureGenerateDoor#removeactionparams-object).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









