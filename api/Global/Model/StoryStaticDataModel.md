---
uid: Global.StoryStaticDataModel
canonical_path: /api/Global/Model/StoryStaticDataModel
---

# Class StoryStaticDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryStaticDataModel
```
Holds the story scenes after loading. #verify 
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryStaticDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryStaticDataModel()

```csharp
private StoryStaticDataModel()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static StoryStaticDataModel _instance
```
#INC


#### Field Value

**Type:** Global.StoryStaticDataModel

### _loaded

```csharp
private bool _loaded
```
#INC


#### Field Value

**Type:** System.Boolean

### _scenes

```csharp
private Dictionary<string, StoryScriptScene> _scenes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,StoryScriptScene}

## Properties

### instance

```csharp
public static StoryStaticDataModel instance { get; }
```

#### Property Value

**Type:** Global.StoryStaticDataModel

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetSceneData(string)

```csharp
public StoryScriptScene GetSceneData(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.StoryScriptScene

### GetSceneList()

```csharp
public StoryScriptScene[] GetSceneList()
```
#INC


#### Returns

**Type:** Global.StoryScriptScene[]

### Init(Dictionary<string, StoryScriptScene>)

```csharp
public void Init(Dictionary<string, StoryScriptScene> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,StoryScriptScene}` |  |
