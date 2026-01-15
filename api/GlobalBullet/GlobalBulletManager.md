---
uid: GlobalBullet.GlobalBulletManager
canonical_path: /api/GlobalBullet/GlobalBulletManager
---

# Class GlobalBulletManager

**Namespace:** [GlobalBullet](/api/GlobalBullet)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalBulletManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalBulletManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GlobalBulletManager()

```csharp
private GlobalBulletManager()
```

## Fields

### _funcs

```csharp
private Dictionary<GlobalBulletType, GlobalBulletManager.BulletFunc> _funcs
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{GlobalBullet.GlobalBulletType,GlobalBullet.GlobalBulletManager.BulletFunc}

### _instance

```csharp
private static GlobalBulletManager _instance
```

#### Field Value

**Type:** GlobalBullet.GlobalBulletManager

### coolTime

```csharp
public float coolTime
```

#### Field Value

**Type:** System.Single

### currentBullet

```csharp
public int currentBullet
```

#### Field Value

**Type:** System.Int32

### elapsedCoolTime

```csharp
public float elapsedCoolTime
```

#### Field Value

**Type:** System.Single

### initialMaxBullet

```csharp
public int initialMaxBullet
```

#### Field Value

**Type:** System.Int32

### maxBullet

```csharp
public int maxBullet
```

#### Field Value

**Type:** System.Int32

## Properties

### instance

```csharp
public static GlobalBulletManager instance { get; }
```

#### Property Value

**Type:** GlobalBullet.GlobalBulletManager

## Methods

### ActivateBullet(GlobalBulletType, List<UnitModel>)

```csharp
public bool ActivateBullet(GlobalBulletType type, List<UnitModel> targets)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `GlobalBullet.GlobalBulletType` |  |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** System.Boolean

### ExcuteBullet(UnitModel)

```csharp
private void ExcuteBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### RecoverHPBullet(UnitModel)

```csharp
private void RecoverHPBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecoverMentalBullet(UnitModel)

```csharp
private void RecoverMentalBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### Reload()

```csharp
public void Reload()
```

### ResistBBullet(UnitModel)

```csharp
private void ResistBBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistPBullet(UnitModel)

```csharp
private void ResistPBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistRBullet(UnitModel)

```csharp
private void ResistRBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistWBullet(UnitModel)

```csharp
private void ResistWBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SetMaxBullet(int)

```csharp
public void SetMaxBullet(int max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |

### SlowBullet(UnitModel)

```csharp
private void SlowBullet(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### UpdateMaxBullet()

```csharp
public void UpdateMaxBullet()
```

### UpdateUI()

```csharp
private void UpdateUI()
```
