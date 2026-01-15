---
uid: Global.CameraMover.CameraForcelyMove
canonical_path: /api/Global/Camera/Mover/CameraMoverCameraForcelyMove
---

# Class CameraMover.CameraForcelyMove

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CameraMover.CameraForcelyMove
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CameraMover.CameraForcelyMove

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CameraForcelyMove()

```csharp
public CameraForcelyMove()
```

## Fields

### dest

```csharp
public Vector3 dest
```

#### Field Value

**Type:** UnityEngine.Vector3

### destOrtho

```csharp
public float destOrtho
```

#### Field Value

**Type:** System.Single

### orthoCheck

```csharp
private bool orthoCheck
```

#### Field Value

**Type:** System.Boolean

### script

```csharp
public CameraMover script
```

#### Field Value

**Type:** Global.CameraMover

### started

```csharp
public bool started
```

#### Field Value

**Type:** System.Boolean

### startOrtho

```csharp
public float startOrtho
```

#### Field Value

**Type:** System.Single

### startPos

```csharp
public Vector3 startPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### startTime

```csharp
private float startTime
```

#### Field Value

**Type:** System.Single

### time

```csharp
public float time
```

#### Field Value

**Type:** System.Single

## Properties

### transform

```csharp
private Transform transform { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### Init(CameraMover)

```csharp
public void Init(CameraMover script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CameraMover` |  |

### OnMoveEnd()

```csharp
public void OnMoveEnd()
```

### StartMoveByTime(Vector3, float, float)

```csharp
public void StartMoveByTime(Vector3 dest, float ortho, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dest` | `UnityEngine.Vector3` |  |
| `ortho` | `System.Single` |  |
| `time` | `System.Single` |  |

### Update()

```csharp
public void Update()
```
