---
uid: Global.CharacterResourceDataModel
canonical_path: /api/Global/Model/CharacterResourceDataModel
---

# Class CharacterResourceDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CharacterResourceDataModel
```
I think this stores information about characters for the story, i.e. names, sprites, etc.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CharacterResourceDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CharacterResourceDataModel()

```csharp
private CharacterResourceDataModel()
```
#INC
#code-generated


## Fields

### _dic

```csharp
private Dictionary<string, CharacterResourceDataModel.CharacterResourceInfo> _dic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,CharacterResourceDataModel.CharacterResourceInfo}

### _instance

```csharp
private static CharacterResourceDataModel _instance
```
#INC


#### Field Value

**Type:** Global.CharacterResourceDataModel

## Properties

### instance

```csharp
public static CharacterResourceDataModel instance { get; }
```

#### Property Value

**Type:** Global.CharacterResourceDataModel

## Methods

### GetColor(string)

```csharp
public Color GetColor(string character)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Color

### GetName(string)

```csharp
public string GetName(string character)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** System.String

### GetPortrait(string)

```csharp
public Sprite GetPortrait(string character)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetSefiraPortrait(SefiraEnum, bool)

```csharp
public Sprite GetSefiraPortrait(SefiraEnum sefiraEnum, bool tipherethException = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |
| `tipherethException` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetSpine(string)

```csharp
public GameObject GetSpine(string character)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject
