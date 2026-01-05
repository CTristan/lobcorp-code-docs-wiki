# Class GeburahPhaseExectuion

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class GeburahPhaseExectuion
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GeburahPhaseExectuion

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GeburahPhaseExectuion(GeburahCoreScript)

```csharp
public GeburahPhaseExectuion(GeburahCoreScript geburah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### geburah

```csharp
public GeburahCoreScript geburah
```

#### Field Value

**Type:** Global.GeburahCoreScript

### isPrevAttack

```csharp
public bool isPrevAttack
```

#### Field Value

**Type:** System.Boolean

## Methods

### FixedUpdate()

```csharp
public abstract void FixedUpdate()
```

### GetNextAction(List<UnitModel>)

```csharp
public abstract GeburahAction GetNextAction(List<UnitModel> near)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** GeburahBoss.GeburahAction

### GetRandomMoveNode()

```csharp
public virtual MapNode GetRandomMoveNode()
```

#### Returns

**Type:** Global.MapNode

### GetRandomNode()

```csharp
public virtual MapNode GetRandomNode()
```

#### Returns

**Type:** Global.MapNode

### OnPrevSuppressed()

```csharp
public virtual void OnPrevSuppressed()
```

### Update()

```csharp
public abstract void Update()
```
