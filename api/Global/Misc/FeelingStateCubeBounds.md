---
uid: Global.FeelingStateCubeBounds
canonical_path: /api/Global/Misc/FeelingStateCubeBounds
---

# Class FeelingStateCubeBounds

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FeelingStateCubeBounds
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FeelingStateCubeBounds

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FeelingStateCubeBounds()

```csharp
public FeelingStateCubeBounds()
```

## Fields

### upperBounds

```csharp
public int[] upperBounds
```

#### Field Value

**Type:** System.Int32[]

## Methods

### CalculateFeelingState(int)

```csharp
public CreatureFeelingState CalculateFeelingState(int energyCubeNum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `energyCubeNum` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureFeelingState

### GetLastBound()

```csharp
public int GetLastBound()
```

#### Returns

**Type:** System.Int32
