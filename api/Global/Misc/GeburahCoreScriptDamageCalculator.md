---
uid: Global.GeburahCoreScript.DamageCalculator
canonical_path: /api/Global/Misc/GeburahCoreScriptDamageCalculator
---

# Class GeburahCoreScript.DamageCalculator

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahCoreScript.DamageCalculator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GeburahCoreScript.DamageCalculator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DamageCalculator()

```csharp
public DamageCalculator()
```

## Fields

### curCumlatiedDamage

```csharp
public float curCumlatiedDamage
```

#### Field Value

**Type:** System.Single

### damageFilled

```csharp
public GeburahCoreScript.DamageCalculator.OnDamageFilled damageFilled
```

#### Field Value

**Type:** Global.GeburahCoreScript.DamageCalculator.OnDamageFilled

### maxDamage

```csharp
public float maxDamage
```

#### Field Value

**Type:** System.Single

## Methods

### CurDamageInit()

```csharp
public void CurDamageInit()
```

### OnTakeDamage(float)

```csharp
public void OnTakeDamage(float damageValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageValue` | `System.Single` |  |

### SetMaxDamage(float)

```csharp
public void SetMaxDamage(float maxDamage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `maxDamage` | `System.Single` |  |
