# Class GlobalBulletManager

**Namespace:** [GlobalBullet](/api/GlobalBullet)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalBulletManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalBulletManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

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

### Reload()

```csharp
public void Reload()
```

### SetMaxBullet(int)

```csharp
public void SetMaxBullet(int max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |

### UpdateMaxBullet()

```csharp
public void UpdateMaxBullet()
```
