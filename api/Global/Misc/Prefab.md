---
uid: Global.Prefab
canonical_path: /api/Global/Misc/Prefab
---

# Class Prefab

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Prefab
```
Helper for loading prefabs. (Note: Please use [ResourceCache](/api/Global/Misc/ResourceCache) instead of this.)
#INC 



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Prefab

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Prefab()

```csharp
public Prefab()
```

## Methods

### LoadPrefab(string)

```csharp
public static GameObject LoadPrefab(string name)
```
Loads the prefab with the given name from the prefabs folder and instantiates the game object.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject
