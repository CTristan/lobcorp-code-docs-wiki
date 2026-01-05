# Class StoryStaticDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryStaticDataModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryStaticDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Returns

**Type:** Global.StoryScriptScene[]

### Init(Dictionary<string, StoryScriptScene>)

```csharp
public void Init(Dictionary<string, StoryScriptScene> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,StoryScriptScene}` |  |
