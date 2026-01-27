---
uid: KetherBoss.KetherLowerBossBase
canonical_path: /api/KetherBoss/KetherLowerBossBase
---

# Class KetherLowerBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherLowerBossBase : KetherBossBase
```
Day 49 suppression


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherLowerBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss/KetherBossBase#oncleared), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Misc/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Misc/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherLowerBossBase()

```csharp
public KetherLowerBossBase()
```
#INC


## Fields

### _binah

```csharp
private BinahBossBase _binah
```
#INC


#### Field Value

**Type:** Global.BinahBossBase

### _chokhmah

```csharp
private ChokhmahBossBase _chokhmah
```
#INC


#### Field Value

**Type:** Global.ChokhmahBossBase

### _clearConfirm

```csharp
private bool _clearConfirm
```
#INC


#### Field Value

**Type:** System.Boolean

### _clearEnergyValue

```csharp
private float _clearEnergyValue
```
#INC


#### Field Value

**Type:** System.Single

### _effect

```csharp
private GameObject _effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _levelReached

```csharp
private bool _levelReached
```
#INC


#### Field Value

**Type:** System.Boolean

### _rotationCurve

```csharp
private float _rotationCurve
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

### bgm0

```csharp
private const string bgm0 = "Sounds/BGM/Boss/Event/49/1_Tilarids - 090909090"
```
#INC


#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Sounds/BGM/Boss/Event/49/2_Haunted Streets_1"
```
#INC


#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Sounds/BGM/Boss/Event/49/3_Tilarids - circle-rombed oxygen"
```
#INC


#### Field Value

**Type:** System.String

### ClearQliphothLevel

```csharp
private const int ClearQliphothLevel = 10
```
#INC


#### Field Value

**Type:** System.Int32

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

### effectSrc

```csharp
private const string effectSrc = "Effect/SefiraBoss/DustCameraAttachedEffect"
```
#INC


#### Field Value

**Type:** System.String

### rotationValue

```csharp
private const float rotationValue = 18
```
#INC


#### Field Value

**Type:** System.Single

### superComputer

```csharp
private CameraFilterPack_AAA_SuperComputer superComputer
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_AAA_SuperComputer

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Methods

### EffectInit()

```csharp
public void EffectInit()
```
#INC


### GetDescType(float)

```csharp
public override SefiraBossDescType GetDescType(float defaultProb = 0.5)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defaultProb` | `System.Single` |  |

#### Returns

**Type:** Global.SefiraBossDescType

### IsCleared()

```csharp
public override bool IsCleared()
```
#INC


#### Returns

**Type:** System.Boolean

### IsStartEmergencyBgm()

```csharp
public override bool IsStartEmergencyBgm()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOverloadActivated(int)

```csharp
public override void OnOverloadActivated(int currentLevel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC
#code-generated


### RotationUpdate()

```csharp
private void RotationUpdate()
```
#INC


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

