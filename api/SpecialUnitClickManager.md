# Class SpecialUnitClickManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpecialUnitClickManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpecialUnitClickManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** Global.SpecialUnitClickManager

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

#### Returns

**Type:** System.Collections.Generic.List{UnityEngine.EventSystems.RaycastResult}

### GetMouseRaycast(ref Vector3)

```csharp
public List<RaycastResult> GetMouseRaycast(ref Vector3 pos)
```

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
