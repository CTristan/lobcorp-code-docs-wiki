---
uid: KetherBoss.FireLightEffect
canonical_path: /api/KetherBoss/FireLightEffect
---

# Class FireLightEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FireLightEffect : KetherLastEffectBase
```

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → FireLightEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [OnStart()](/api/KetherBoss/KetherLastEffectBase#onstart), [Update()](/api/KetherBoss/KetherLastEffectBase#update), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FireLightEffect(KetherLastBossBase)

```csharp
public FireLightEffect(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _effectTime

```csharp
private static float[] _effectTime
```
#INC


#### Field Value

**Type:** System.Single[]

### _particle

```csharp
private GameObject _particle
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

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

### execution

```csharp
private FireLightEffect.Execution execution
```

#### Field Value

**Type:** KetherBoss.FireLightEffect.Execution

### glow

```csharp
private CameraFilterPack_Glow_Glow_Color glow
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Glow_Glow_Color

### particleSrc

```csharp
private const string particleSrc = "Effect/SefiraBoss/Kether/KetherLightColumn"
```
#INC


#### Field Value

**Type:** System.String

### timer

```csharp
private Timer timer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### ExecutionEnd()

```csharp
private void ExecutionEnd()
```
#INC


### ExecutionStart()

```csharp
private void ExecutionStart()
```
#INC


### ExecutionUpdate()

```csharp
private void ExecutionUpdate()
```
#INC


### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### LoadLigthColumn()

```csharp
private void LoadLigthColumn()
```
#INC


### StartEffect()

```csharp
public void StartEffect()
```
#INC

