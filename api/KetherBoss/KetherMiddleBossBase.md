---
uid: KetherBoss.KetherMiddleBossBase
canonical_path: /api/KetherBoss/KetherMiddleBossBase
---

# Class KetherMiddleBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherMiddleBossBase : KetherBossBase
```
Day 48 suppression


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherMiddleBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss/KetherBossBase#oncleared), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Misc/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Misc/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherMiddleBossBase()

```csharp
public KetherMiddleBossBase()
```
#INC


## Fields

### _artefactEffectTime

```csharp
private float _artefactEffectTime
```
#INC


#### Field Value

**Type:** System.Single

### _artefactEffectTimer

```csharp
private UnscaledTimer _artefactEffectTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _chesed

```csharp
private ChesedBossBase _chesed
```
#INC


#### Field Value

**Type:** Global.ChesedBossBase

### _clearEnergyValue

```csharp
private float _clearEnergyValue
```
#INC


#### Field Value

**Type:** System.Single

### _fade

```csharp
private MinMax _fade
```
#INC


#### Field Value

**Type:** Global.MinMax

### _fps

```csharp
private MinMax _fps
```
#INC


#### Field Value

**Type:** Global.MinMax

### _geburah

```csharp
private GeburahBossBase _geburah
```
#INC


#### Field Value

**Type:** Global.GeburahBossBase

### _movieEffectTime

```csharp
private float _movieEffectTime
```
#INC


#### Field Value

**Type:** System.Single

### _movieEffectTimer

```csharp
private UnscaledTimer _movieEffectTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _tiphereth

```csharp
private TipherethBossBase _tiphereth
```
#INC


#### Field Value

**Type:** Global.TipherethBossBase

### artefact

```csharp
private CameraFilterPack_TV_Artefact artefact
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Artefact

### bgm0

```csharp
private const string bgm0 = "Sounds/BGM/Boss/Event/48/1_Dark Fantasy Scene"
```
#INC


#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Sounds/BGM/Boss/Event/48/2_Tilarids - Insignia Decay"
```
#INC


#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Sounds/BGM/Boss/Event/48/3_Battle_-_Urgent_Encounter"
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

### fadeEffect

```csharp
private MinMax fadeEffect
```
#INC


#### Field Value

**Type:** Global.MinMax

### fpsEffect

```csharp
private MinMax fpsEffect
```
#INC


#### Field Value

**Type:** Global.MinMax

### movie

```csharp
private CameraFilterPack_TV_Old_Movie_2 movie
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Old_Movie_2

### tvOldEnableLevel

```csharp
private const int tvOldEnableLevel = 7
```
#INC


#### Field Value

**Type:** System.Int32

### tvOldEndLevel

```csharp
private const int tvOldEndLevel = 10
```
#INC


#### Field Value

**Type:** System.Int32

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

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


### Update()

```csharp
public override void Update()
```
#INC

