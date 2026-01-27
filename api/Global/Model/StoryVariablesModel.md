---
uid: Global.StoryVariablesModel
canonical_path: /api/Global/Model/StoryVariablesModel
---

# Class StoryVariablesModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryVariablesModel
```
Holds variables used in the story. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryVariablesModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryVariablesModel()

```csharp
private StoryVariablesModel()
```
#INC
#code-generated


## Fields

### _globalVariables

```csharp
private Dictionary<string, int> _globalVariables
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### _instance

```csharp
private static StoryVariablesModel _instance
```
#INC


#### Field Value

**Type:** Global.StoryVariablesModel

### _localVariables

```csharp
private Dictionary<string, int> _localVariables
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### _predefinedVariables

```csharp
private Dictionary<string, StoryVariablesModel.PredefinedVar> _predefinedVariables
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,StoryVariablesModel.PredefinedVar}

### AGENT_DIE_COUNT

```csharp
public const string AGENT_DIE_COUNT = "AgentDieCount"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### instance

```csharp
public static StoryVariablesModel instance { get; }
```

#### Property Value

**Type:** Global.StoryVariablesModel

## Methods

### AddVariable(string, int)

```csharp
public void AddVariable(string id, int operand)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `operand` | `System.Int32` |  |

### ClearLocalVariables()

```csharp
public void ClearLocalVariables()
```
#INC


### GetVariable(string)

```csharp
public int GetVariable(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
public void Init()
```
#INC


### LoadData()

```csharp
public void LoadData()
```
#INC


### SaveData()

```csharp
public Dictionary<string, object> SaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### SetLocalVariable(string, int)

```csharp
public void SetLocalVariable(string id, int val)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `val` | `System.Int32` |  |
