---
uid: Global.TipherethBossBase
canonical_path: /api/Global/Misc/TipherethBossBase
---

# Class TipherethBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TipherethBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → TipherethBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Misc/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TipherethBossBase()

```csharp
public TipherethBossBase()
```

## Fields

### _failTimerRun

```csharp
private bool _failTimerRun
```

#### Field Value

**Type:** System.Boolean

### _failureTimer

```csharp
private UnscaledTimer _failureTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _glowFilter

```csharp
private UnscaledTimer _glowFilter
```

#### Field Value

**Type:** Global.UnscaledTimer

### _minimunFailureTime

```csharp
private const float _minimunFailureTime = Infinity
```

#### Field Value

**Type:** System.Single

### _phase

```csharp
private int _phase
```

#### Field Value

**Type:** System.Int32

### _secondPhaseQliphothLevel

```csharp
private const int _secondPhaseQliphothLevel = 3
```

#### Field Value

**Type:** System.Int32

### _thirdPhaseQliphothLevel

```csharp
private const int _thirdPhaseQliphothLevel = 6
```

#### Field Value

**Type:** System.Int32

### animSrc

```csharp
private const string animSrc = "TipherethCoreAnim"
```

#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Tiphereth/1_Eternal"
```

#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Tiphereth/2_Dark Fantasy Scene"
```

#### Field Value

**Type:** System.String

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 10
```

#### Field Value

**Type:** System.Int32

### descDelay

```csharp
private const float descDelay = 15
```

#### Field Value

**Type:** System.Single

### glow

```csharp
private CameraFilterPack_Glow_Glow_Color glow
```

#### Field Value

**Type:** Global.CameraFilterPack_Glow_Glow_Color

### glowColor

```csharp
private const string glowColor = "#FFC50BFF"
```

#### Field Value

**Type:** System.String

### glowFilterTime

```csharp
private const float glowFilterTime = 3
```

#### Field Value

**Type:** System.Single

### model

```csharp
private SefiraBossCreatureModel model
```

#### Field Value

**Type:** Global.SefiraBossCreatureModel

### tipherethBase

```csharp
private const string tipherethBase = "TipherethCoreScript"
```

#### Field Value

**Type:** System.String

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties

### phase

```csharp
private int phase { get; set; }
```

#### Property Value

**Type:** System.Int32

### Script

```csharp
private TipherethCoreScript Script { get; }
```

#### Property Value

**Type:** Global.TipherethCoreScript

## Methods

### CalculateFailureTime()

```csharp
public void CalculateFailureTime()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GlowFilterUpdate()

```csharp
private void GlowFilterUpdate()
```

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

### OnChangePhase()

```csharp
public override void OnChangePhase()
```

### OnCleared()

```csharp
public override void OnCleared()
```

### OnKetherStart()

```csharp
public override void OnKetherStart()
```

### OnOverloadActivated(int)

```csharp
public override void OnOverloadActivated(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### StartGlowFilter()

```csharp
private void StartGlowFilter()
```

### Update()

```csharp
public override void Update()
```
