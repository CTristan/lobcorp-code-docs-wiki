---
uid: KetherBoss.EnergyConcentrateEffect
canonical_path: /api/KetherBoss/EnergyConcentrateEffect
---

# Class EnergyConcentrateEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EnergyConcentrateEffect : KetherLastEffectBase
```

uh. maybe a big charging thing? i'd have to rewatch day 50

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → EnergyConcentrateEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [OnStart()](/api/KetherBoss/KetherLastEffectBase#onstart), [FixedUpdate()](/api/KetherBoss/KetherLastEffectBase#fixedupdate), [Update()](/api/KetherBoss/KetherLastEffectBase#update), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EnergyConcentrateEffect(KetherLastBossBase)

```csharp
public EnergyConcentrateEffect(KetherLastBossBase bossBase)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _emit

```csharp
private MinMax _emit
```
#INC


#### Field Value

**Type:** Global.MinMax

### _rate

```csharp
private float _rate
```
#INC


#### Field Value

**Type:** System.Single

### _rateDelta

```csharp
private static float _rateDelta
```
#INC


#### Field Value

**Type:** System.Single

### _shape

```csharp
private MinMax _shape
```
#INC


#### Field Value

**Type:** Global.MinMax

### _speedMax

```csharp
private MinMax _speedMax
```
#INC


#### Field Value

**Type:** Global.MinMax

### _speedMin

```csharp
private MinMax _speedMin
```
#INC


#### Field Value

**Type:** Global.MinMax

### parent

```csharp
private Transform parent
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### particle

```csharp
private ParticleSystem particle
```
#INC


#### Field Value

**Type:** UnityEngine.ParticleSystem

### particleSrc

```csharp
private const string particleSrc = "Effect/SefiraBoss/Kether/EnergyConcentration"
```
#INC


#### Field Value

**Type:** System.String

## Methods

### LoadParticle()

```csharp
public void LoadParticle()
```
#INC


### SetRate(float)

```csharp
public void SetRate(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### TurnOn()

```csharp
public void TurnOn()
```
#INC

