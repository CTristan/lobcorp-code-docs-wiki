---
uid: KetherBoss.CameraRotationEvent
canonical_path: /api/KetherBoss/CameraRotationEvent
---

# Class CameraRotationEvent

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CameraRotationEvent : KetherLastEffectBase
```

effect that rotates the camera during day 50. I assume

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → CameraRotationEvent

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [FixedUpdate()](/api/KetherBoss/KetherLastEffectBase#fixedupdate), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CameraRotationEvent(KetherLastBossBase)

```csharp
public CameraRotationEvent(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _effect

```csharp
private GameObject _effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _rotationTime

```csharp
private float _rotationTime
```
#INC


#### Field Value

**Type:** System.Single

### _rotationTimer

```csharp
private UnscaledTimer _rotationTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _rotationValue

```csharp
private MinMax _rotationValue
```
#INC


#### Field Value

**Type:** Global.MinMax

### curve

```csharp
private AnimationCurve curve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### earthQuake

```csharp
private CameraFilterPack_FX_EarthQuake earthQuake
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_FX_EarthQuake

### effectName

```csharp
private const string effectName = "CameraDust"
```
#INC


#### Field Value

**Type:** System.String

### effectSrc

```csharp
private const string effectSrc = "Effect/SefiraBoss/DustCameraAttachedEffect"
```
#INC


#### Field Value

**Type:** System.String

### rotationValue

```csharp
private const float rotationValue = 36
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated


### SetCameraRotation(float)

```csharp
public void SetCameraRotation(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### StartRotation(int)

```csharp
public void StartRotation(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### Update()

```csharp
public override void Update()
```
#INC

