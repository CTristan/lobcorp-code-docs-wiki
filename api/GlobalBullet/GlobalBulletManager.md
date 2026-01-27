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

Manager for how many bullets there are, when they're reloaded, when they're activated, and bullet effects



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalBulletManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GlobalBulletManager()

```csharp
private GlobalBulletManager()
```
#INC
#code-generated


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
#INC


#### Field Value

**Type:** GlobalBullet.GlobalBulletManager

### coolTime

```csharp
public float coolTime
```
#INC


#### Field Value

**Type:** System.Single

### currentBullet

```csharp
public int currentBullet
```
#INC


#### Field Value

**Type:** System.Int32

### elapsedCoolTime

```csharp
public float elapsedCoolTime
```
#INC


#### Field Value

**Type:** System.Single

### initialMaxBullet

```csharp
public int initialMaxBullet
```
#INC


#### Field Value

**Type:** System.Int32

### maxBullet

```csharp
public int maxBullet
```
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### RecoverHPBullet(UnitModel)

```csharp
private void RecoverHPBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecoverMentalBullet(UnitModel)

```csharp
private void RecoverMentalBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### Reload()

```csharp
public void Reload()
```
#INC


### ResistBBullet(UnitModel)

```csharp
private void ResistBBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistPBullet(UnitModel)

```csharp
private void ResistPBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistRBullet(UnitModel)

```csharp
private void ResistRBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ResistWBullet(UnitModel)

```csharp
private void ResistWBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SetMaxBullet(int)

```csharp
public void SetMaxBullet(int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |

### SlowBullet(UnitModel)

```csharp
private void SlowBullet(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### UpdateMaxBullet()

```csharp
public void UpdateMaxBullet()
```
#INC


### UpdateUI()

```csharp
private void UpdateUI()
```
#INC

