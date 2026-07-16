---
title: CreatureGenerateModel
description: 
published: true
date: 2026-07-16T21:17:51.105Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:21.432Z
---

# Class CreatureGenerateModel
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateModel : CreatureGenerateData
```
> This section may have incomplete or incorrect information.
{.is-warning}


Represents the three doors during an extraction, and the restrictions for the day. `ONLY` restricts to the listed abnormalities, and `REMOVE` removes certain abnormalities for the day.

See [Abnormality Extraction](/abnormality-extraction) for how this system works.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate/CreatureGenerateData) → CreatureGenerateModel

## Constructors
### CreatureGenerateModel()
```csharp
public CreatureGenerateModel()
```
Default constructor.
## Fields
### creature
```csharp
public List<long> creature
```
The list of abnormalities in the selection.

#### Field Value
**Type:** System.Collections.Generic.List{System.Int64}

### day
```csharp
public int day
```
The current day. Note that there are no `CreatureGenerateModels` for every fifth day, and any day after Day 45.

#### Field Value
**Type:** System.Int32

### door1
```csharp
public CreatureGenerateDoor door1
```
The first door, with probabilities for each risk level. See also [CreatureGenerateDoor](/api/CreatureGenerate/CreatureGenerateDoor).

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateDoor

### door2
```csharp
public CreatureGenerateDoor door2
```
The second door, with probabilities for each risk level. See also [CreatureGenerateDoor](/api/CreatureGenerate/CreatureGenerateDoor).

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateDoor

### door3
```csharp
public CreatureGenerateDoor door3
```
The third door, with probabilities for each risk level. See also [CreatureGenerateDoor](/api/CreatureGenerate/CreatureGenerateDoor).

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateDoor

### stop
```csharp
public bool stop
```
Flag indicating whether the door probabilities need to be calculated. False when an `ONLY` action has happened (e.g., on Day 1).

#### Field Value
**Type:** System.Boolean

## Methods
### OnlyAction(params object[])
```csharp
public override void OnlyAction(params object[] ids)
```
Logs the ID of the given abnormalities, then adds them to today's selection. Only used on Day 1. Also, sets a flag preventing further abnormalities from being presented today.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### ParseActionNode(string)
```csharp
public CreatureGenerateData.ActionData ParseActionNode(string nodeText)
```
Returns an [`ActionData`](/api/CreatureGenerate/CreatureGenerateData/CreatureGenerateData-ActionData) containing a delegate for either `OnlyAction` or `RemoveAction` if the string contains a valid action, or else `null`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nodeText` | `System.String` | A string containing the action and a list of abnormality IDs to parse. |

#### Returns
**Type:** CreatureGenerate.CreatureGenerateData.ActionData

### Print()
```csharp
public void Print()
```
Logs information about the day. Unused.

### RemoveAction(params object[])
```csharp
public override void RemoveAction(params object[] ids)
```
Removes the list of abnormalities from the usable abnormalities for the day. See also [`CreatureGenerateInfoManager::RemoveAction(long)`](/api/CreatureGenerate/CreatureGenerateInfoManager#removeactionlong).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` | An array of `long` abnormality IDs to remove for the day. |

### SetCreature()
```csharp
public void SetCreature()
```
Populates `creature` with a list of at most 3 selectable abnormalities for the day.

###### Details

Executes the `ONLY` or `REMOVE` action if needed (see [`RemoveAction`](/api/CreatureGenerate/CreatureGenerateModel#removeactionparams-object) and [`OnlyAction`](/api/CreatureGenerate/CreatureGenerateModel#onlyactionparams-object). If `ONLY` was run, then stops.

Otherwise, execute actions on all of the doors (which does nothing) and gets an abnormality for each door (see [`CreatureGenerateDoor::SetCreature`](/api/CreatureGenerate/CreatureGenerateDoor#setcreature)). For each non-null abnormality (ID not `-1`), add that abnormality to `creature`.

## Inherited Members
[split](/api/CreatureGenerate/CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate/CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate/CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate/CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate/CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate/CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









