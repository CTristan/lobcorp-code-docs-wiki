---
uid: KetherBoss.KetherZeroBossBase
canonical_path: /api/KetherBoss/KetherZeroBossBase
---

# Class KetherZeroBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherZeroBossBase : KetherBossBase, IObserver
```
Day 46 suppression


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherZeroBossBase

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss/KetherBossBase#oncleared), [Update()](/api/KetherBoss/KetherBossBase#update), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [OnOverloadActivated(int)](/api/KetherBoss/KetherBossBase#onoverloadactivated-int), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Misc/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Misc/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Misc/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherZeroBossBase()

```csharp
public KetherZeroBossBase()
```
#INC


## Fields

### _clawAppeared

```csharp
private bool _clawAppeared
```
#INC


#### Field Value

**Type:** System.Boolean

### _clawSuppressed

```csharp
private bool _clawSuppressed
```
#INC


#### Field Value

**Type:** System.Boolean

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 10
```
#INC


#### Field Value

**Type:** System.Int32

### fixerClaw

```csharp
private FixerClaw fixerClaw
```
#INC


#### Field Value

**Type:** Global.FixerClaw

### max

```csharp
private float max
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### IsCleared()

```csharp
public override bool IsCleared()
```
#INC


#### Returns

**Type:** System.Boolean

### IsReadyToClose()

```csharp
public override bool IsReadyToClose()
```
#INC


#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnFixerClawSuppressed()

```csharp
public void OnFixerClawSuppressed()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC
#code-generated

