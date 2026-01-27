---
uid: KetherBoss.MoveCameraEffect
canonical_path: /api/KetherBoss/MoveCameraEffect
---

# Class MoveCameraEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveCameraEffect : KetherLastEffectBase
```
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → MoveCameraEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [OnStart()](/api/KetherBoss/KetherLastEffectBase#onstart), [FixedUpdate()](/api/KetherBoss/KetherLastEffectBase#fixedupdate), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoveCameraEffect(KetherLastBossBase)

```csharp
public MoveCameraEffect(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _cameraAttached

```csharp
private GameObject _cameraAttached
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _cameraYStd

```csharp
private float _cameraYStd
```
#INC


#### Field Value

**Type:** System.Single

### _speedMultiplyTimer

```csharp
private Timer _speedMultiplyTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### particleSrc

```csharp
private const string particleSrc = "Effect/SefiraBoss/Kether/CameraConcentration"
```
#INC


#### Field Value

**Type:** System.String

### speed

```csharp
private MinMax speed
```
#INC


#### Field Value

**Type:** Global.MinMax

### startMoving

```csharp
private bool startMoving
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### LoadParticle()

```csharp
private void LoadParticle()
```
#INC


### OnArrived()

```csharp
public void OnArrived()
```
#INC


### StartEffect()

```csharp
public void StartEffect()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC
#code-generated

