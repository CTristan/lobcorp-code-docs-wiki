---
uid: Global.AngelaMessage
canonical_path: /api/Global/Misc/AngelaMessage
---

# Class AngelaMessage

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AngelaMessage
```
Represents one of Angela's messages (one unit of yap)

See [AngelaConversation](/api/Global/Misc/AngelaConversation)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AngelaMessage

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AngelaMessage(AngelaMessageState, AngelaMessagePos, AngelaMessageUnit[])

```csharp
public AngelaMessage(AngelaMessageState state, AngelaMessagePos pos, AngelaMessageUnit[] ary)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.AngelaMessageState` |  |
| `pos` | `Global.AngelaMessagePos` |  |
| `ary` | `Global.AngelaMessageUnit[]` |  |

## Fields

### defaultFormat

```csharp
public string defaultFormat
```
#INC


#### Field Value

**Type:** System.String

### list

```csharp
public List<AngelaMessageUnit> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AngelaMessageUnit}

### pos

```csharp
public AngelaMessagePos pos
```
#INC


#### Field Value

**Type:** Global.AngelaMessagePos

### state

```csharp
public AngelaMessageState state
```
#INC


#### Field Value

**Type:** Global.AngelaMessageState

## Methods

### GetUnit()

```csharp
public virtual AngelaMessageUnit GetUnit()
```
#INC


#### Returns

**Type:** Global.AngelaMessageUnit

### GetUnit(int)

```csharp
public virtual AngelaMessageUnit GetUnit(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AngelaMessageUnit

### PrintData()

```csharp
public void PrintData()
```
#INC

