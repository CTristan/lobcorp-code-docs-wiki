---
uid: BinahBoss.BinahPhaseExecution
canonical_path: /api/BinahBoss/BinahPhaseExecution
---

# Class BinahPhaseExecution

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class BinahPhaseExecution
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahPhaseExecution

## Derived
[FirstPhase](/api/BinahBoss/FirstPhase), [SecondPhase](/api/BinahBoss/SecondPhase), [ThirdPhase](/api/BinahBoss/ThirdPhase)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahPhaseExecution(BinahCoreScript)

```csharp
public BinahPhaseExecution(BinahCoreScript binah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### binah

```csharp
public BinahCoreScript binah
```

#### Field Value

**Type:** Global.BinahCoreScript

### overloadActivated

```csharp
public bool overloadActivated
```

#### Field Value

**Type:** System.Boolean

### overloadTimer

```csharp
public Timer overloadTimer
```

#### Field Value

**Type:** Global.Timer

### overloadTypeList

```csharp
public List<OverloadType> overloadTypeList
```

#### Field Value

**Type:** System.Collections.Generic.List{OverloadType}

## Properties

### BinahHasOverload

```csharp
public bool BinahHasOverload { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### FixedUpdate()

```csharp
public abstract void FixedUpdate()
```

### GetNextAction(List<UnitModel>)

```csharp
public abstract BinahAction GetNextAction(List<UnitModel> near)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** BinahBoss.BinahAction

### GetOverloadType()

```csharp
public virtual OverloadType GetOverloadType()
```

#### Returns

**Type:** Global.OverloadType

### HaltOverload()

```csharp
public virtual void HaltOverload()
```

### OnOverloadEnd()

```csharp
public virtual void OnOverloadEnd()
```

### OnPrevSuppressed()

```csharp
public abstract void OnPrevSuppressed()
```

### StartTimer(float)

```csharp
public virtual void StartTimer(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

### Update()

```csharp
public abstract void Update()
```
