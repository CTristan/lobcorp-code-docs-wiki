---
uid: Global.StoryScriptValue
canonical_path: /api/Global/Misc/StoryScriptValue
---

# Class StoryScriptValue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryScriptValue
```
A variable to be used in the story script.

Can be VARIABLE or CONSTANT.

Used with .


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryScriptValue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryScriptValue(int)

```csharp
public StoryScriptValue(int value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

### StoryScriptValue(string)

```csharp
public StoryScriptValue(string id)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

## Fields

### id

```csharp
public string id
```
#INC


#### Field Value

**Type:** System.String

### value

```csharp
public int value
```
#INC


#### Field Value

**Type:** System.Int32

### valueType

```csharp
public StoryScriptValue.ValueType valueType
```

#### Field Value

**Type:** Global.StoryScriptValue.ValueType
