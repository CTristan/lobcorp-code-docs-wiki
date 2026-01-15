---
uid: Global.Result
canonical_path: /api/Global/Misc/Result
---

# Class Result

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Result
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Result

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Result(float, float)

```csharp
public Result(float start, float end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `start` | `System.Single` |  |
| `end` | `System.Single` |  |

## Fields

### checkedCreatures

```csharp
public List<CreatureModel> checkedCreatures
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### checkedWorkers

```csharp
public List<WorkerModel> checkedWorkers
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### creatureEscape

```csharp
public int[] creatureEscape
```

#### Field Value

**Type:** System.Int32[]

### time

```csharp
public float time
```

#### Field Value

**Type:** System.Single

### workerDie

```csharp
public int workerDie
```

#### Field Value

**Type:** System.Int32

### workerPanic

```csharp
public int workerPanic
```

#### Field Value

**Type:** System.Int32
