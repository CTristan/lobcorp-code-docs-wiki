---
uid: Global.GameUtil
canonical_path: /api/Global/Misc/GameUtil
---

# Class GameUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameUtil
```
Holds the method which grabs values from dictionaries (TryGetValue), and some other mostly unused stuff.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GameUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GameUtil()

```csharp
public GameUtil()
```

## Fields

### h

```csharp
public static string h
```
#INC


#### Field Value

**Type:** System.String

### h2

```csharp
public static string h2
```
#INC


#### Field Value

**Type:** System.String

## Methods

### SetRendererAlpha(SpriteRenderer, float)

```csharp
public static void SetRendererAlpha(SpriteRenderer renderer, float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderer` | `UnityEngine.SpriteRenderer` |  |
| `alpha` | `System.Single` |  |

### TryGetValue<T>(Dictionary<string, object>, string, ref T)

```csharp
public static bool TryGetValue<T>(Dictionary<string, object> dic, string name, ref T field)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `field` | `{T}` |  |

#### Returns

**Type:** System.Boolean
