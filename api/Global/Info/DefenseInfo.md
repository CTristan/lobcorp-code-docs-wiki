---
uid: Global.DefenseInfo
canonical_path: /api/Global/Info/DefenseInfo
---

# Class DefenseInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DefenseInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DefenseInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DefenseInfo()

```csharp
public DefenseInfo()
```

## Fields

### B

```csharp
public float B
```

#### Field Value

**Type:** System.Single

### P

```csharp
public float P
```

#### Field Value

**Type:** System.Single

### R

```csharp
public float R
```

#### Field Value

**Type:** System.Single

### W

```csharp
public float W
```

#### Field Value

**Type:** System.Single

## Properties

### zero

```csharp
public static DefenseInfo zero { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

## Methods

### Copy()

```csharp
public DefenseInfo Copy()
```

#### Returns

**Type:** Global.DefenseInfo

### GetDefenseType(float)

```csharp
public DefenseInfo.Type GetDefenseType(float f)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `f` | `System.Single` |  |

#### Returns

**Type:** Global.DefenseInfo.Type

### GetDefenseType(RwbpType)

```csharp
public DefenseInfo.Type GetDefenseType(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** Global.DefenseInfo.Type

### GetMultiplier(RwbpType)

```csharp
public float GetMultiplier(RwbpType rwbpType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rwbpType` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Single
