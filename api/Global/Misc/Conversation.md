---
uid: Global.Conversation
canonical_path: /api/Global/Misc/Conversation
---

# Class Conversation

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Conversation
```
Holds sephirah yapping messages, for displaying in-game (e.g. upon agent death, abnormality escape...).

Loaded by [GameStaticDataLoader](/api/Global/Loader/GameStaticDataLoader) from ExternalData/xml/Language/en/SefiraDesc_en.xml, or the appropriate language xml.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Conversation

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Conversation()

```csharp
private Conversation()
```
#INC
#code-generated


## Fields

### _dic

```csharp
public Dictionary<int, List<SefiraMessage>> _dic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{SefiraMessage}}

### _instance

```csharp
private static Conversation _instance
```
#INC


#### Field Value

**Type:** Global.Conversation

### _isLoaded

```csharp
private bool _isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### instance

```csharp
public static Conversation instance { get; }
```

#### Property Value

**Type:** Global.Conversation

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetSefiraMessage(int, int, bool)

```csharp
public SefiraMessage GetSefiraMessage(int key, int type, bool isRobot)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.Int32` |  |
| `type` | `System.Int32` |  |
| `isRobot` | `System.Boolean` |  |

#### Returns

**Type:** Global.SefiraMessage

### GetSefiraMessage(int, int, int, bool)

```csharp
public SefiraMessage GetSefiraMessage(int key, int type, int tiphType, bool isRobot)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.Int32` |  |
| `type` | `System.Int32` |  |
| `tiphType` | `System.Int32` |  |
| `isRobot` | `System.Boolean` |  |

#### Returns

**Type:** Global.SefiraMessage

### Init(Dictionary<int, List<SefiraMessage>>)

```csharp
public void Init(Dictionary<int, List<SefiraMessage>> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{SefiraMessage}}` |  |
