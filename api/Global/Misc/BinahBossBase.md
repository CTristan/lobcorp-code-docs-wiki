---
uid: Global.BinahBossBase
canonical_path: /api/Global/Misc/BinahBossBase
---

# Class BinahBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → BinahBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnOverloadActivated(int)](/api/Global/Misc/SefiraBossBase#onoverloadactivated-int), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahBossBase()

```csharp
public BinahBossBase()
```

## Fields

### _blizzard

```csharp
private bool _blizzard
```

#### Field Value

**Type:** System.Boolean

### _blizzardTimer

```csharp
private UnscaledTimer _blizzardTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _delayTimer

```csharp
private Timer _delayTimer
```

#### Field Value

**Type:** Global.Timer

### _effect_end

```csharp
private BinahBossBase.BlizzardValue _effect_end
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _effect_start

```csharp
private BinahBossBase.BlizzardValue _effect_start
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _effectValueGaging

```csharp
private static BinahBossBase.BlizzardValue _effectValueGaging
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _effectValueGroggy

```csharp
private static BinahBossBase.BlizzardValue _effectValueGroggy
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _endBlizzard

```csharp
private static BinahBossBase.BlizzardValue _endBlizzard
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _endMovie

```csharp
private static BinahBossBase.MovieValue _endMovie
```

#### Field Value

**Type:** Global.BinahBossBase.MovieValue

### _filterTimer

```csharp
private UnscaledTimer _filterTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _isInit

```csharp
private bool _isInit
```

#### Field Value

**Type:** System.Boolean

### _movie

```csharp
private bool _movie
```

#### Field Value

**Type:** System.Boolean

### _phase

```csharp
private int _phase
```

#### Field Value

**Type:** System.Int32

### _startBlizzard

```csharp
private static BinahBossBase.BlizzardValue _startBlizzard
```

#### Field Value

**Type:** Global.BinahBossBase.BlizzardValue

### _startMovie

```csharp
private static BinahBossBase.MovieValue _startMovie
```

#### Field Value

**Type:** Global.BinahBossBase.MovieValue

### animSrc

```csharp
private const string animSrc = "BinahCoreAnim"
```

#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Binah/1_Jukai"
```

#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Binah/2_Haunted Streets_1"
```

#### Field Value

**Type:** System.String

### binahBase

```csharp
private const string binahBase = "BinahCoreScript"
```

#### Field Value

**Type:** System.String

### blizzard

```csharp
private CameraFilterPack_Blizzard blizzard
```

#### Field Value

**Type:** Global.CameraFilterPack_Blizzard

### blizzardTransTime

```csharp
private float blizzardTransTime
```

#### Field Value

**Type:** System.Single

### FilterTransTime

```csharp
private float FilterTransTime
```

#### Field Value

**Type:** System.Single

### metaId

```csharp
private const long metaId = 400002
```

#### Field Value

**Type:** System.Int64

### model

```csharp
public SefiraBossCreatureModel model
```

#### Field Value

**Type:** Global.SefiraBossCreatureModel

### movie

```csharp
private CameraFilterPack_TV_Old_Movie_2 movie
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_Old_Movie_2

### startNode

```csharp
private const string startNode = "sefira-binah-5"
```

#### Field Value

**Type:** System.String

### textIds

```csharp
private static int[] textIds
```

#### Field Value

**Type:** System.Int32[]

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties

### Script

```csharp
public BinahCoreScript Script { get; }
```

#### Property Value

**Type:** Global.BinahCoreScript

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

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

### InitModel()

```csharp
public void InitModel()
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

### OnStageStart()

```csharp
public override void OnStageStart()
```

### StartBlizzardEffect()

```csharp
public void StartBlizzardEffect()
```

### StartBlizzardEffect(BlizzardEffect)

```csharp
public void StartBlizzardEffect(BinahBossBase.BlizzardEffect type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.BinahBossBase.BlizzardEffect` |  |

### StartCameraMoveEndFirst()

```csharp
private void StartCameraMoveEndFirst()
```

### StartMovieEffect()

```csharp
public void StartMovieEffect()
```

### Update()

```csharp
public override void Update()
```
