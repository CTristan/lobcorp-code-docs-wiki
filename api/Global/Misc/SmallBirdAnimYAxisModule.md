---
uid: Global.SmallBirdAnim.YAxisModule
canonical_path: /api/Global/Misc/SmallBirdAnimYAxisModule
---

# Class SmallBirdAnim.YAxisModule

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SmallBirdAnim.YAxisModule
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SmallBirdAnim.YAxisModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### YAxisModule()

```csharp
public YAxisModule()
```

## Fields

### axisRange

```csharp
public Vector2 axisRange
```

#### Field Value

**Type:** UnityEngine.Vector2

### birdEscapePos

```csharp
private Vector3 birdEscapePos
```

#### Field Value

**Type:** UnityEngine.Vector3

### currentYAxisTarget

```csharp
private float currentYAxisTarget
```

#### Field Value

**Type:** System.Single

### movementTimer

```csharp
private Timer movementTimer
```

#### Field Value

**Type:** Global.Timer

### startYAxis

```csharp
private float startYAxis
```

#### Field Value

**Type:** System.Single

### targetTransform

```csharp
private Transform targetTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### timeRange

```csharp
public Vector2 timeRange
```

#### Field Value

**Type:** UnityEngine.Vector2

## Methods

### Execute()

```csharp
public void Execute()
```

### Init(Transform)

```csharp
public void Init(Transform t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Transform` |  |

### Start()

```csharp
public void Start()
```

### Stop()

```csharp
public void Stop()
```
