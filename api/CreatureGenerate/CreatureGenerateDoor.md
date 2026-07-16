---
title: CreatureGenerateDoor
description: 
published: true
date: 2026-07-16T17:17:27.254Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:16.445Z
---

# Class CreatureGenerateDoor
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateDoor : CreatureGenerateData
```

Represents a door during abnormality extraction. See also [Abnormality Extraction](/abnormality-extraction).

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate/CreatureGenerateData) → CreatureGenerateDoor

## Constructors
### CreatureGenerateDoor()
```csharp
public CreatureGenerateDoor()
```
Constructs a new door with no data. See [`CreatureGenerateDoor::Parse(string)`](#parsestring).

## Fields
### Creature
```csharp
public long Creature
```
The selected abnormality.

#### Field Value
**Type:** System.Int64

### initialState
```csharp
public static bool[] initialState
```
Array with five `true` values, to initialize `probState`.

#### Field Value
**Type:** System.Boolean[]

### MAX
```csharp
public const int MAX = 5
```
Presumably used to cap the number of probabilities to 5 (to match the number of risk levels).

#### Field Value
**Type:** System.Int32

### prob
```csharp
public float[] prob
```
Five probabilities, one for each risk level.

#### Field Value
**Type:** System.Single[]

### probState
```csharp
public bool[] probState
```
Five flags, indicating if each risk level is present today (i.e. has a non-zero probability).

#### Field Value
**Type:** System.Boolean[]

### zeroAry
```csharp
public static readonly float[] zeroAry
```
An array of five `0f` values, to initialize `prob`.

#### Field Value
**Type:** System.Single[]

## Properties
### TotalProb
```csharp
public float TotalProb { get; }
```
Returns the sum of all probabilities (usually 1, but theoretically could be less).

#### Property Value
**Type:** System.Single

## Methods
### CheckProb()
```csharp
public void CheckProb()
```
Gets the `ActivateStateList` for each risk level and enables/disables that risk level if the list is enabled today (see [`ActivateStateList::LevelEnabled`](/api/CreatureGenerate/ActivateStateList#levelenabled)). If the list is null, logs the error `List is Null {#}`.

### GetList(int)
```csharp
public ActivateStateList GetList(int i)
```
Returns the `ActivateStateList` with risk level `i`, or else logs `"Failed to list"`. See [`CreatureGenerateInfoManager::GetCreatureState`](/api/CreatureGenerate/CreatureGenerateInfoManager#getcreaturestaterisklevel-out-activatestatelist).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` | The index of the risk level of the `ActivateStateList`. |

#### Returns
**Type:** CreatureGenerate.ActivateStateList

### OnlyAction(params object[])
```csharp
public override void OnlyAction(params object[] ids)
```
Does nothing. See [`CreatureGenerateModel::OnlyAction`](/api/CreatureGenerate/CreatureGenerateModel#onlyactionparams-object).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### Parse(string)
```csharp
public static CreatureGenerateDoor Parse(string parsed)
```
Parses a string with five comma-separated floats into a `CreatureGenerateDoor`.

###### Details
Puts the floats in the string into `prob`, then sets each flag in `probState` to true if the associated probability is non-zero.

:interrobang: Also makes a call to `CreatureGenerateDoor::ParseAction`, but does nothing with the result. This could change `parsed`, the string to parse, because it is passed by reference; but `ParseAction` only ever changes the string input in unreachable code.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` | A string containing five comma-separated floats to parse. |

#### Returns
**Type:** CreatureGenerate.CreatureGenerateDoor

### Print()
```csharp
public void Print()
```
Unused. Logs the probabilities in `prob`.

### RemoveAction(params object[])
```csharp
public override void RemoveAction(params object[] ids)
```
Does nothing. See [`CreatureGenerateModel::RemoveAction`](/api/CreatureGenerate/CreatureGenerateModel#removeactionparams-object).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### SetCreature()
```csharp
public void SetCreature()
```
Gets a random creature for the selection today and marks it as removed.

###### Details
Initializes `Creature` to `-1L`.

Runs `CreatureGenerateDoor::CheckProb` to enable all active risk levels today.

If the total probability is 0, returns immediately. Otherwise, gets a random float between 0 and the total probability.

For each enabled risk level, adds the probabilities until it exceeds the random value, then selects the last risk level. This effectively chooses a random float with probability equal to each risk level's probability, as expected.

`Creature` is then assigned to a random abnormality in that risk level's `ActivateStateList` (see [`ActivateStateList::GetRandomCreature`](/api/CreatureGenerate/ActivateStateList#getrandomcreature)) and removes that abnormality from the list to prevent it from being selected again.

## Inherited Members
[split](/api/CreatureGenerate/CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate/CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate/CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate/CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate/CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate/CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









