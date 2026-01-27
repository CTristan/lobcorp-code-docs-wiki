---
uid: KetherBoss.FadeoutEffect
canonical_path: /api/KetherBoss/FadeoutEffect
---

# Class FadeoutEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FadeoutEffect : KetherLastEffectBase
```

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → FadeoutEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [Update()](/api/KetherBoss/KetherLastEffectBase#update), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FadeoutEffect(KetherLastBossBase)

```csharp
public FadeoutEffect(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _bloom_amount

```csharp
private static MinMax _bloom_amount
```
#INC


#### Field Value

**Type:** Global.MinMax

### _bloom_glow

```csharp
private static MinMax _bloom_glow
```
#INC


#### Field Value

**Type:** Global.MinMax

### _brightness

```csharp
private static MinMax _brightness
```
#INC


#### Field Value

**Type:** Global.MinMax

### _cam

```csharp
private Camera _cam
```
#INC


#### Field Value

**Type:** UnityEngine.Camera

### _lifeTimer

```csharp
private Timer _lifeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### bloom

```csharp
private CameraFilterPack_Blur_Bloom bloom
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Blur_Bloom

### brightness

```csharp
private CameraFilterPack_Colors_Brightness brightness
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Colors_Brightness

## Properties

### Camera

```csharp
public Camera Camera { get; }
```

#### Property Value

**Type:** UnityEngine.Camera

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated

