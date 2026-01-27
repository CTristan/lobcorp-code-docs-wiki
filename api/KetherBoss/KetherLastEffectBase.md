---
uid: KetherBoss.KetherLastEffectBase
canonical_path: /api/KetherBoss/KetherLastEffectBase
---

# Class KetherLastEffectBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherLastEffectBase
```
Parent class for day 50 effects


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → KetherLastEffectBase

## Derived
[BackGroundMoveEffect](/api/KetherBoss/BackGroundMoveEffect), [CameraRotationEvent](/api/KetherBoss/CameraRotationEvent), [EnergyConcentrateEffect](/api/KetherBoss/EnergyConcentrateEffect), [FadeoutEffect](/api/KetherBoss/FadeoutEffect), [FireLightEffect](/api/KetherBoss/FireLightEffect), [MoveCameraEffect](/api/KetherBoss/MoveCameraEffect), [WhiteFadeEffect](/api/KetherBoss/WhiteFadeEffect)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherLastEffectBase(KetherLastBossBase)

```csharp
public KetherLastEffectBase(KetherLastBossBase bossBase)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### bossBase

```csharp
private KetherLastBossBase bossBase
```
#INC


#### Field Value

**Type:** KetherBoss.KetherLastBossBase

### type

```csharp
protected KetherLastEffectType type
```
#INC


#### Field Value

**Type:** KetherBoss.KetherLastEffectType

## Properties

### BossBase

```csharp
public KetherLastBossBase BossBase { get; }
```

#### Property Value

**Type:** KetherBoss.KetherLastBossBase

## Methods

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnStart()

```csharp
public virtual void OnStart()
```
#INC


### Terminate()

```csharp
public virtual void Terminate()
```
#INC


### Update()

```csharp
public virtual void Update()
```
#INC

