---
uid: KetherBoss.BackGroundMoveEffect
canonical_path: /api/KetherBoss/BackGroundMoveEffect
---

# Class BackGroundMoveEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BackGroundMoveEffect : KetherLastEffectBase
```

Moves the background during day 50
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss/KetherLastEffectBase) → BackGroundMoveEffect

## Inherited Members
[bossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [type](/api/KetherBoss/KetherLastEffectBase#type), [OnStart()](/api/KetherBoss/KetherLastEffectBase#onstart), [OnDestroy()](/api/KetherBoss/KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss/KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss/KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BackGroundMoveEffect(KetherLastBossBase)

```csharp
public BackGroundMoveEffect(KetherLastBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _changeAction

```csharp
public BackGroundMoveEffect.ChangeBackgournd _changeAction
```

#### Field Value

**Type:** KetherBoss.BackGroundMoveEffect.ChangeBackgournd

### _initalSpeed

```csharp
private float _initalSpeed
```
#INC


#### Field Value

**Type:** System.Single

### _maxY

```csharp
private const float _maxY = 50000
```
#INC


#### Field Value

**Type:** System.Single

### _speed

```csharp
private float _speed
```
#INC


#### Field Value

**Type:** System.Single

### _speedFactor

```csharp
private const float _speedFactor = 5
```
#INC


#### Field Value

**Type:** System.Single

### _transform

```csharp
private Transform _transform
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### earthQuake

```csharp
private CameraFilterPack_FX_EarthQuake earthQuake
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_FX_EarthQuake

### endPosition

```csharp
private Vector3 endPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### eqLifetime

```csharp
private const float eqLifetime = 2
```
#INC


#### Field Value

**Type:** System.Single

### speedTimer

```csharp
private Timer speedTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### startPosition

```csharp
private Vector3 startPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### timer

```csharp
private Timer timer
```
#INC


#### Field Value

**Type:** Global.Timer

## Properties

### Tr

```csharp
private Transform Tr { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### ApplyFrameChangeEvent(ChangeBackgournd)

```csharp
public void ApplyFrameChangeEvent(BackGroundMoveEffect.ChangeBackgournd changeBackgournd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `changeBackgournd` | `KetherBoss.BackGroundMoveEffect.ChangeBackgournd` |  |

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### StartVertiaclMovement(float, bool)

```csharp
public void StartVertiaclMovement(float speed, bool eqEanble = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |
| `eqEanble` | `System.Boolean` |  |

### Update()

```csharp
public override void Update()
```
#INC
#code-generated

