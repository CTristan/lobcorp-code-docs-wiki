---
title: CreatureGenerateData
description: 
published: true
date: 2026-07-16T22:32:33.762Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:13.816Z
---

# Class CreatureGenerateData
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateData
```
Parent class for some scripts relating to abnormality extraction. See [Abnormality Extraction](/abnormality-extraction) for a description of the abnormality extraction system.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureGenerateData

## Derived
[CreatureGenerateDoor](/api/CreatureGenerate/CreatureGenerateDoor), [CreatureGenerateModel](/api/CreatureGenerate/CreatureGenerateModel)

## Constructors
### CreatureGenerateData()
```csharp
public CreatureGenerateData()
```
Default constructor.

## Fields
### commonAction
```csharp
public CreatureGenerateData.ActionData commonAction
```
An [`ActionData`](/api/CreatureGenerate/CreatureGenerateData/CreatureGenerateData-ActionData), potentially holding an `ONLY` or `REMOVE` action.

#### Field Value
**Type:** CreatureGenerate.CreatureGenerateData.ActionData

### split
```csharp
public static char[] split
```
The character to split strings on when parsing doors and actions. Only contains `,`.

#### Field Value
**Type:** System.Char[]

### uniqueText
```csharp
public static string uniqueText
```
Unused.

#### Field Value
**Type:** System.String

## Methods
### IsCommonAction(string, out GenerateCommonAction)
```csharp
public static bool IsCommonAction(string parsed, out GenerateCommonAction action)
```
Tries to parse `parsed` into an action, accepting either `"only"` or `"remove"`. On success, passes the corresponding action (as the enum from [`GenerateCommonAction`](/api/CreatureGenerate/GenerateCommonAction)) into `action`. Otherwise, return false.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` | The string to parse (usually `"only"` or `"remove"`). |
| `action` | `CreatureGenerate.GenerateCommonAction` | The parsed action, or `ONLY` on failure. |

#### Returns
**Type:** System.Boolean

### IsUniqueAction(string)
```csharp
public static bool IsUniqueAction(string parsed)
```
Returns false.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` | Unused. |

#### Returns
**Type:** System.Boolean

### OnlyAction(params object[])
```csharp
public virtual void OnlyAction(params object[] ids)
```
A method to be run when an `ONLY` action is received. See [`CreatureGenerateModel::OnlyAction`](/api/CreatureGenerate/CreatureGenerateModel#onlyactionparams-object).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` | The IDs of the abnormalities to allow. |

### ParseAction(ref string, out ActionData)
```csharp
public bool ParseAction(ref string origin, out CreatureGenerateData.ActionData output)
```
Parses the given string as an action followed by a list of abnormality IDs.

###### Details
Splits the reference string `origin` into an array by commas, then tries to parse the first element as an action. :question: It then finds where that token is in the original string, and if it is not at index 0, makes `origin` end at the end of that token. This should never happen normally; instead `result` is set to `false`, :question: always.

The `action` delegate is then assigned to `OnlyAction` or `RemoveAction`, respectively.

Then, all remaining elements of the array are assumed to be abnormality IDs of type `long` and given as the parameters to the `action` delegate.

The method always returns false during normal gameplay, with `output` either `null` if the action was invalid or the appropriate action if it was successfully parsed.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` | The string to parse. |
| `output` | `CreatureGenerate.CreatureGenerateData.ActionData` | The [`ActionData`](/api/CreatureGenerate/CreatureGenerateData/CreatureGenerateData-ActionData) containing the action and the necessary parameters. |

#### Returns
**Type:** System.Boolean

### RemoveAction(params object[])
```csharp
public virtual void RemoveAction(params object[] ids)
```
A method to be run when a `REMOVE` action is received. See [`CreatureGenerateModel::RemoveAction`](/api/CreatureGenerate/CreatureGenerateModel#removeactionparams-object).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` | The IDs of the abnormalities to remove. |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









