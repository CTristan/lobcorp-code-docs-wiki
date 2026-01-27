---
uid: Global.SefiraCharacterManager
canonical_path: /api/Global/Misc/SefiraCharacterManager
---

# Class SefiraCharacterManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraCharacterManager
```
Manages [SefiraCharacterModel](/api/Global/Model/SefiraCharacterModel)s, which represent departments opened to a certain level. #verify 

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraCharacterManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraCharacterManager()

```csharp
private SefiraCharacterManager()
```
#INC
#code-generated


## Fields

### _characters

```csharp
private Dictionary<SefiraEnum, SefiraCharacterModel> _characters
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,SefiraCharacterModel}

### _charactersList

```csharp
private List<SefiraCharacterModel> _charactersList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraCharacterModel}

### _instance

```csharp
private static SefiraCharacterManager _instance
```
#INC


#### Field Value

**Type:** Global.SefiraCharacterManager

## Properties

### instance

```csharp
public static SefiraCharacterManager instance { get; }
```

#### Property Value

**Type:** Global.SefiraCharacterManager

## Methods

### AddSefiraInfo(SefiraEnum)

```csharp
private void AddSefiraInfo(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### GetList()

```csharp
public IList<SefiraCharacterModel> GetList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{SefiraCharacterModel}

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSefiraCharacter(SefiraEnum)

```csharp
public SefiraCharacterModel GetSefiraCharacter(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.SefiraCharacterModel

### Init()

```csharp
public void Init()
```
#INC


### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnOpenSefira(SefiraEnum)

```csharp
public void OnOpenSefira(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
