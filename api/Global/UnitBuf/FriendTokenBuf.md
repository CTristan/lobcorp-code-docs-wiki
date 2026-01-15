---
uid: Global.FriendTokenBuf
canonical_path: /api/Global/UnitBuf/FriendTokenBuf
---

# Class FriendTokenBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FriendTokenBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → FriendTokenBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FriendTokenBuf(GalaxyBoy)

```csharp
public FriendTokenBuf(GalaxyBoy creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.GalaxyBoy` |  |

## Fields

### _damageFactor

```csharp
private const float _damageFactor = 4
```

#### Field Value

**Type:** System.Single

### _deadCounterReduce

```csharp
private const int _deadCounterReduce = 4
```

#### Field Value

**Type:** System.Int32

### _healthRecoverFactor

```csharp
private const float _healthRecoverFactor = 0.65
```

#### Field Value

**Type:** System.Single

### _healthRecoverTimer

```csharp
private Timer _healthRecoverTimer
```

#### Field Value

**Type:** Global.Timer

### _instantKillCheckFreq

```csharp
private const float _instantKillCheckFreq = 20
```

#### Field Value

**Type:** System.Single

### _mentalRecoverFactor

```csharp
private const float _mentalRecoverFactor = 0.65
```

#### Field Value

**Type:** System.Single

### _mentalRecoverTimer

```csharp
private Timer _mentalRecoverTimer
```

#### Field Value

**Type:** Global.Timer

### _qlipothActivatedEventTimer

```csharp
private Timer _qlipothActivatedEventTimer
```

#### Field Value

**Type:** Global.Timer

### _recoverDebufActviated

```csharp
private bool _recoverDebufActviated
```

#### Field Value

**Type:** System.Boolean

### _recoverFreq

```csharp
private const float _recoverFreq = 5
```

#### Field Value

**Type:** System.Single

### _workEnterCheck

```csharp
private bool _workEnterCheck
```

#### Field Value

**Type:** System.Boolean

### agentModel

```csharp
private AgentModel agentModel
```

#### Field Value

**Type:** Global.AgentModel

### baseCreature

```csharp
private GalaxyBoy baseCreature
```

#### Field Value

**Type:** Global.GalaxyBoy

## Properties

### CurrentQlipoth

```csharp
private int CurrentQlipoth { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### DamageInvoke()

```csharp
private void DamageInvoke()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
