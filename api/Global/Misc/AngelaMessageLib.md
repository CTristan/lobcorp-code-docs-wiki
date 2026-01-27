---
uid: Global.AngelaMessageLib
canonical_path: /api/Global/Misc/AngelaMessageLib
---

# Class AngelaMessageLib

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AngelaMessageLib
```
Stores a list of [Angela's messages](/api/Global/Misc/AngelaMessage), to be grabbed by [AngelaConversation](/api/Global/Misc/AngelaConversation).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AngelaMessageLib

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AngelaMessageLib(AngelaMessage[])

```csharp
public AngelaMessageLib(AngelaMessage[] ary)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.AngelaMessage[]` |  |

## Fields

### list

```csharp
public List<AngelaMessage> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AngelaMessage}

## Methods

### GetMessage(AngelaMessageState)

```csharp
public virtual AngelaMessage GetMessage(AngelaMessageState targetState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetState` | `Global.AngelaMessageState` |  |

#### Returns

**Type:** Global.AngelaMessage
