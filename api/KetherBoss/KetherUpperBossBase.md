---
uid: KetherBoss.KetherUpperBossBase
canonical_path: /api/KetherBoss/KetherUpperBossBase
---

# Class KetherUpperBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherUpperBossBase : KetherBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherUpperBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Misc/SefiraBossBase#onketherstart), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Misc/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherUpperBossBase()

```csharp
public KetherUpperBossBase()
```

## Fields

### _glitch

```csharp
private CameraFilterPack_FX_Glitch3 _glitch
```

#### Field Value

**Type:** Global.CameraFilterPack_FX_Glitch3

### _hodReduceVal

```csharp
private const float _hodReduceVal = 50
```

#### Field Value

**Type:** System.Single

### _phase

```csharp
private KetherUpperBossBase.KetherUpperPhase _phase
```

#### Field Value

**Type:** KetherBoss.KetherUpperBossBase.KetherUpperPhase

### _phaseShiftEffectTime

```csharp
private float _phaseShiftEffectTime
```

#### Field Value

**Type:** System.Single

### _phaseShiftTimer

```csharp
private UnscaledTimer _phaseShiftTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _pixelisation

```csharp
private CameraFilterPack_Pixel_Pixelisation _pixelisation
```

#### Field Value

**Type:** Global.CameraFilterPack_Pixel_Pixelisation

### bgm0

```csharp
private const string bgm0 = "Sounds/BGM/Boss/Event/47/1_Tilarids - Red Dots"
```

#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Sounds/BGM/Boss/Event/47/2_Tilarids - Faded"
```

#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Sounds/BGM/Boss/Event/47/3_Theme_-_Retro_Time_ALT(Mix)"
```

#### Field Value

**Type:** System.String

### bgm3

```csharp
private const string bgm3 = "Sounds/BGM/Boss/Event/47/4_Tilarids - Blue Dots"
```

#### Field Value

**Type:** System.String

### bgm4

```csharp
private const string bgm4 = "Sounds/BGM/Boss/Event/47/5_Tilarids - Violation Of Black Colors"
```

#### Field Value

**Type:** System.String

### bufList

```csharp
public List<HodBossBuf> bufList
```

#### Field Value

**Type:** System.Collections.Generic.List{HodBossBuf}

### cameraScript

```csharp
private YesodBossCameraScript cameraScript
```

#### Field Value

**Type:** Global.YesodBossCameraScript

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 6
```

#### Field Value

**Type:** System.Int32

### superComputer

```csharp
private CameraFilterPack_AAA_SuperComputer superComputer
```

#### Field Value

**Type:** Global.CameraFilterPack_AAA_SuperComputer

### totalEnergy

```csharp
private float totalEnergy
```

#### Field Value

**Type:** System.Single

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties

### Phase

```csharp
public KetherUpperBossBase.KetherUpperPhase Phase { get; }
```

#### Property Value

**Type:** KetherBoss.KetherUpperBossBase.KetherUpperPhase

## Methods

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

#### Returns

**Type:** System.Boolean

### IsReadyToClose()

```csharp
public override bool IsReadyToClose()
```

#### Returns

**Type:** System.Boolean

### IsStartEmergencyBgm()

```csharp
public override bool IsStartEmergencyBgm()
```

#### Returns

**Type:** System.Boolean

### OnCleared()

```csharp
public override void OnCleared()
```

### OnOverloadActivated(int)

```csharp
public override void OnOverloadActivated(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnPhaseShift()

```csharp
private void OnPhaseShift()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### SetCameraScript(YesodBossCameraScript)

```csharp
public void SetCameraScript(YesodBossCameraScript cameraScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cameraScript` | `Global.YesodBossCameraScript` |  |

### SetHodBufValue(float)

```csharp
public void SetHodBufValue(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### Update()

```csharp
public override void Update()
```
