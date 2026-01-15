---
uid: Global.ChesedBossBase
canonical_path: /api/Global/Misc/ChesedBossBase
---

# Class ChesedBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChesedBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → ChesedBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/Global/Misc/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Misc/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChesedBossBase()

```csharp
public ChesedBossBase()
```

## Fields

### _effectLifeTime

```csharp
private const float _effectLifeTime = 3
```

#### Field Value

**Type:** System.Single

### _effectTimer

```csharp
private Timer _effectTimer
```

#### Field Value

**Type:** Global.Timer

### _phase

```csharp
private int _phase
```

#### Field Value

**Type:** System.Int32

### _secondPhaseQliphothLevel

```csharp
private const int _secondPhaseQliphothLevel = 2
```

#### Field Value

**Type:** System.Int32

### _thirdPhaseQliphothLevel

```csharp
private const int _thirdPhaseQliphothLevel = 5
```

#### Field Value

**Type:** System.Int32

### animSrc

```csharp
private const string animSrc = "ChesedCoreAnim"
```

#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Chesed/1_Theme_-_Blues_Man"
```

#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Chesed/2_Battle_-_Urgent_Encounter"
```

#### Field Value

**Type:** System.String

### chesedBase

```csharp
private const string chesedBase = "ChesedCoreScript"
```

#### Field Value

**Type:** System.String

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 8
```

#### Field Value

**Type:** System.Int32

### currentDamageMultiplied

```csharp
private List<RwbpType> currentDamageMultiplied
```

#### Field Value

**Type:** System.Collections.Generic.List{RwbpType}

### descDelay

```csharp
private const float descDelay = 15
```

#### Field Value

**Type:** System.Single

### model

```csharp
private SefiraBossCreatureModel model
```

#### Field Value

**Type:** Global.SefiraBossCreatureModel

### node

```csharp
private const string node = "dept-chesed-4"
```

#### Field Value

**Type:** System.String

### rain

```csharp
private CameraFilterPack_Atmosphere_Rain_Pro rain
```

#### Field Value

**Type:** Global.CameraFilterPack_Atmosphere_Rain_Pro

### rwbpTypes

```csharp
private static RwbpType[] rwbpTypes
```

#### Field Value

**Type:** Global.RwbpType[]

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

### Script

```csharp
private ChesedCoreScript Script { get; }
```

#### Property Value

**Type:** Global.ChesedCoreScript

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GenBuf()

```csharp
private void GenBuf()
```

### GetDamageChangeTime()

```csharp
private float GetDamageChangeTime()
```

#### Returns

**Type:** System.Single

### IsCleared()

```csharp
public override bool IsCleared()
```

#### Returns

**Type:** System.Boolean

### IsDamageMultiplied(RwbpType)

```csharp
public bool IsDamageMultiplied(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

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

### SetDamageMultiplied()

```csharp
private void SetDamageMultiplied()
```

### SetDamageMultiplied(int)

```csharp
public void SetDamageMultiplied(int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### StartEffect()

```csharp
public void StartEffect()
```

### UpdateEffect(float)

```csharp
public void UpdateEffect(float rate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |
