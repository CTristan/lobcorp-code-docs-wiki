---
uid: Poly2Tri.TriangulationConstraint
canonical_path: /api/Poly2Tri/TriangulationConstraint
---

# Class TriangulationConstraint

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TriangulationConstraint : Edge
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Edge](/api/Poly2Tri/Edge) → TriangulationConstraint

## Derived
[DTSweepConstraint](/api/Poly2Tri/DTSweepConstraint)

## Inherited Members
[mP](/api/Poly2Tri/Edge#mp), [mQ](/api/Poly2Tri/Edge#mq), [EdgeStart](/api/Poly2Tri/Edge#edgestart), [EdgeEnd](/api/Poly2Tri/Edge#edgeend), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TriangulationConstraint(TriangulationPoint, TriangulationPoint)

```csharp
public TriangulationConstraint(TriangulationPoint p1, TriangulationPoint p2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `Poly2Tri.TriangulationPoint` |  |
| `p2` | `Poly2Tri.TriangulationPoint` |  |

## Fields

### mContraintCode

```csharp
private uint mContraintCode
```

#### Field Value

**Type:** System.UInt32

## Properties

### ConstraintCode

```csharp
public uint ConstraintCode { get; }
```

#### Property Value

**Type:** System.UInt32

### P

```csharp
public TriangulationPoint P { get; set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

### Q

```csharp
public TriangulationPoint Q { get; set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

## Methods

### CalculateContraintCode()

```csharp
public void CalculateContraintCode()
```

### CalculateContraintCode(TriangulationPoint, TriangulationPoint)

```csharp
public static uint CalculateContraintCode(TriangulationPoint p, TriangulationPoint q)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `q` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.UInt32

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
