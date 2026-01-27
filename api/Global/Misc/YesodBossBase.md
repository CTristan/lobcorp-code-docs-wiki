---
uid: Global.YesodBossBase
canonical_path: /api/Global/Misc/YesodBossBase
---

# Class YesodBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YesodBossBase : SefiraBossBase
```

Yesod's core suppression.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → YesodBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/Global/Misc/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Misc/SefiraBossBase#getdesctype-float), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### YesodBossBase()

```csharp
public YesodBossBase()
```
#INC


## Fields

### _phase

```csharp
private int _phase
```
#INC


#### Field Value

**Type:** System.Int32

### _startEffectTimer

```csharp
private Timer _startEffectTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### animSrc

```csharp
private const string animSrc = "YesodCoreAnim"
```
#INC


#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Yesod/1_Tilarids - untitled9877645623413123325"
```
#INC


#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Yesod/2_Tilarids - Faded"
```
#INC


#### Field Value

**Type:** System.String

### cameraScript

```csharp
private YesodBossCameraScript cameraScript
```
#INC


#### Field Value

**Type:** Global.YesodBossCameraScript

### changeQliphothLevel

```csharp
private const int changeQliphothLevel = 3
```
#INC


#### Field Value

**Type:** System.Int32

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 6
```
#INC


#### Field Value

**Type:** System.Int32

### descDelay

```csharp
private const float descDelay = 15
```
#INC


#### Field Value

**Type:** System.Single

### glitch3

```csharp
private CameraFilterPack_FX_Glitch3 glitch3
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_FX_Glitch3

### model

```csharp
private SefiraBossCreatureModel model
```
#INC


#### Field Value

**Type:** Global.SefiraBossCreatureModel

### noiseDefaultValue

```csharp
private const float noiseDefaultValue = 0.075
```
#INC


#### Field Value

**Type:** System.Single

### noiseTv

```csharp
private CameraFilterPack_Noise_TV noiseTv
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Noise_TV

### phaseSound

```csharp
private const string phaseSound = "SefiraBoss/Boss_Yesod"
```
#INC


#### Field Value

**Type:** System.String

### pixelisation

```csharp
private CameraFilterPack_Pixel_Pixelisation pixelisation
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_Pixel_Pixelisation

### totalEnergy

```csharp
private float totalEnergy
```
#INC


#### Field Value

**Type:** System.Single

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

### yesodBase

```csharp
private const string yesodBase = "YesodCoreScript"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### Script

```csharp
private YesodCoreScript Script { get; }
```

#### Property Value

**Type:** Global.YesodCoreScript

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### GetDescFreq()

```csharp
public override float GetDescFreq()
```
#INC


#### Returns

**Type:** System.Single

### IsCleared()

```csharp
public override bool IsCleared()
```
#INC


#### Returns

**Type:** System.Boolean

### OnChangePhase()

```csharp
public override void OnChangePhase()
```
#INC


### OnCleared()

```csharp
public override void OnCleared()
```
#INC


### OnKetherStart()

```csharp
public override void OnKetherStart()
```
#INC


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


### SetCameraScript(YesodBossCameraScript)

```csharp
public void SetCameraScript(YesodBossCameraScript cameraScript)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cameraScript` | `Global.YesodBossCameraScript` |  |

### StartEffect()

```csharp
public void StartEffect()
```
#INC

