---
uid: Global.MagicalGirl_2.AttackDelay
canonical_path: /api/Global/Misc/MagicalGirl2AttackDelay
---

# Class MagicalGirl_2.AttackDelay

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MagicalGirl_2.AttackDelay
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MagicalGirl_2.AttackDelay

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AttackDelay(UnitModel, float)

```csharp
public AttackDelay(UnitModel target, float remainDelay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `remainDelay` | `System.Single` |  |

## Fields

### enable

```csharp
private bool enable
```

#### Field Value

**Type:** System.Boolean

### remainDelay

```csharp
private float remainDelay
```

#### Field Value

**Type:** System.Single

### target

```csharp
private UnitModel target
```

#### Field Value

**Type:** Global.UnitModel

## Methods

### GetModel()

```csharp
public UnitModel GetModel()
```

#### Returns

**Type:** Global.UnitModel

### IsEnable()

```csharp
public bool IsEnable()
```

#### Returns

**Type:** System.Boolean

### Process()

```csharp
public void Process()
```
