---
title: ActivateStateList
description: 
published: true
date: 2026-07-16T20:50:19.716Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:08.931Z
---

# Class ActivateStateList
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ActivateStateList
```
Contains a list of abnormalities of a given risk level, stored as [`ActivateStateModels`](/api/CreatureGenerate/ActivateStateModel), for the purposes of abnormality extraction. Each `ActivateStateModel` contains the abnormality ID and some flags regarding whether this abnormality can be extracted.

See [Abnormality Extraction](/abnormality-extraction) for an overview of the extraction system.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ActivateStateList

## Constructors
### ActivateStateList()
```csharp
public ActivateStateList()
```
Default constructor.
## Fields
### list
```csharp
public List<ActivateStateModel> list
```
A list of [`ActivateStateModels`](/api/CreatureGenerate/ActivateStateModel) representing each abnormality of a given risk level, together with some flags giving information about its availability for the day.

#### Field Value
**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### riskLevel
```csharp
public RiskLevel riskLevel
```
The risk level of the abnormalities in this `ActivateStateList`.

#### Field Value
**Type:** Global.RiskLevel

### Usable
```csharp
public List<ActivateStateModel> Usable
```
A list of selectable abnormalities (those which are not in the facility, removed for this day, or selected in a previous extraction).

#### Field Value
**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

## Properties
### CurrentDay
```csharp
private int CurrentDay { get; }
```
The current day.

#### Property Value
**Type:** System.Int32

### LevelEnabled
```csharp
public bool LevelEnabled { get; }
```
Returns true if there are abnormalities available of this risk level today.

#### Property Value
**Type:** System.Boolean

### Max
```csharp
public int Max { get; }
```
Unused.

#### Property Value
**Type:** System.Int32

### UsableCount
```csharp
public int UsableCount { get; }
```
Alias for `Usable.Count`. The number of selectable abnormalities for the day.

#### Property Value
**Type:** System.Int32

## Methods
### Add(ActivateStateModel)
```csharp
public void Add(ActivateStateModel model)
```
Adds `model` to `list`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `CreatureGenerate.ActivateStateModel` | The `ActivateStateModel` to add. |

### CheckUsableState()
```csharp
public void CheckUsableState()
```
Re-calculates `Usable`, the list of selectable abnormalities for the day. See [`GetUsableCreatures`](/api/CreatureGenerate/ActivateStateList#getusablecreatures).

### DayUpdate()
```csharp
public void DayUpdate()
```
Refreshes `list`, marking all abnormalities in the facility and in the queue as used and marking all abnormalities as not removed for the day.

### GetRandomCreature()
```csharp
public ActivateStateModel GetRandomCreature()
```
Returns a random selectable abnormality (from `Usable`). If this risk level is disabled, return null.

#### Returns
**Type:** CreatureGenerate.ActivateStateModel

### GetUsableCreatures()
```csharp
public List<ActivateStateModel> GetUsableCreatures()
```
Marks every abnormality in the facility and in the queue as used. For each remaining abnormality not marked as removed, adds them to `Usable` if it is a tool and today is a tool day, or if it is not a tool and today is not a tool day.

[Yang](/api/Global/Abnormalities/Yin-and-Yang/Yang/Yang) is never added unless [Yin](/api/Global/Abnormalities/Yin-and-Yang/Yin/Yin) is present.

[WhiteNight](/api/WhiteNightSpace/DeathAngel) is never added to this list, but [Plague Doctor](/api/WhiteNightSpace/PlagueDoctor) can be added if WhiteNight is not in the facility.

#### Returns
**Type:** System.Collections.Generic.List{CreatureGenerate.ActivateStateModel}

### OnUsed(long)
```csharp
public void OnUsed(long id)
```
Marks the given abnormality as used.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` | The ID of the abnormality to mark as used. |

### RemoveAction(long)
```csharp
public void RemoveAction(long id)
```
Marks the given abnormality as removed.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` | The ID of the abnormality to remove today. |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









