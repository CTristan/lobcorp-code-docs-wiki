---
uid: KetherBoss.WhiteFadeEffect
canonical_path: /api/KetherBoss/WhiteFadeEffect
---

# Class WhiteFadeEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WhiteFadeEffect : KetherLastEffectBase
```
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → WhiteFadeEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [Update()](/api/KetherBoss/KetherLastEffectBase#update), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WhiteFadeEffect(KetherLastBossBase)

```csharp
public WhiteFadeEffect(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _arrived

```csharp
private bool _arrived
```
#INC


#### Field Value

**Type:** System.Boolean

### _effectTime

```csharp
private float _effectTime
```
#INC


#### Field Value

**Type:** System.Single

### _timer

```csharp
private Timer _timer
```
#INC


#### Field Value

**Type:** Global.Timer

### brightness

```csharp
private CameraFilterPack_Colors_Brightness brightness
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Colors_Brightness

### curve

```csharp
private AnimationCurve curve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### terminateMovement

```csharp
private bool terminateMovement
```
#INC


#### Field Value

**Type:** System.Boolean

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


### StartEffect()

```csharp
public void StartEffect()
```
#INC

