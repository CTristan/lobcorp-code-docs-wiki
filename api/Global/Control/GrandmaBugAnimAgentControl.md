---
uid: Global.GrandmaBugAnim.AgentControl
canonical_path: /api/Global/Control/GrandmaBugAnimAgentControl
---

# Class GrandmaBugAnim.AgentControl

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GrandmaBugAnim.AgentControl
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GrandmaBugAnim.AgentControl

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentControl()

```csharp
public AgentControl()
```

## Fields

### distance_x

```csharp
public float distance_x
```

#### Field Value

**Type:** System.Single

### distance_y

```csharp
public float distance_y
```

#### Field Value

**Type:** System.Single

### exploded

```csharp
private bool exploded
```

#### Field Value

**Type:** System.Boolean

### initalPosition

```csharp
public Vector2 initalPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### setter

```csharp
private SpriteLayerSetter setter
```

#### Field Value

**Type:** Global.SpriteLayerSetter

### spritechanged

```csharp
private bool spritechanged
```

#### Field Value

**Type:** System.Boolean

### targetPosition

```csharp
public Vector2 targetPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### targetWorker

```csharp
public WorkerModel targetWorker
```

#### Field Value

**Type:** Global.WorkerModel

### targetWorkerUnit

```csharp
public WorkerUnit targetWorkerUnit
```

#### Field Value

**Type:** Global.WorkerUnit

## Methods

### ChangeLayer()

```csharp
public void ChangeLayer()
```

### FixedExecute(float, float, float)

```csharp
public void FixedExecute(float elap, float yCurveVal, float max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elap` | `System.Single` |  |
| `yCurveVal` | `System.Single` |  |
| `max` | `System.Single` |  |

### MakeExplodeEffect()

```csharp
private void MakeExplodeEffect()
```

### SetSpriteLayerSetter(SpriteLayerSetter)

```csharp
public void SetSpriteLayerSetter(SpriteLayerSetter setter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `setter` | `Global.SpriteLayerSetter` |  |
