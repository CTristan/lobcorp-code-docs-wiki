---
uid: Global.SpecialUnitClickManager
canonical_path: /api/Global/Misc/SpecialUnitClickManager
---

# Class SpecialUnitClickManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpecialUnitClickManager
```
OnLateUpdate gets called by [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager) but I don't think this is used...

#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpecialUnitClickManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpecialUnitClickManager()

```csharp
public SpecialUnitClickManager()
```

## Fields

### _instance

```csharp
public static SpecialUnitClickManager _instance
```
#INC


#### Field Value

**Type:** Global.SpecialUnitClickManager

### mouseRaycastResult

```csharp
private List<RaycastResult> mouseRaycastResult
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.EventSystems.RaycastResult}

## Properties

### instance

```csharp
public static SpecialUnitClickManager instance { get; }
```

#### Property Value

**Type:** Global.SpecialUnitClickManager

## Methods

### GetMouseRaycast()

```csharp
public List<RaycastResult> GetMouseRaycast()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnityEngine.EventSystems.RaycastResult}

### GetMouseRaycast(ref Vector3)

```csharp
public List<RaycastResult> GetMouseRaycast(ref Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnityEngine.EventSystems.RaycastResult}

### OnLateUpdate()

```csharp
public void OnLateUpdate()
```
#INC
#code-generated

