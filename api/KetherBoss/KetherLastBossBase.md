---
uid: KetherBoss.KetherLastBossBase
canonical_path: /api/KetherBoss/KetherLastBossBase
---

# Class KetherLastBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherLastBossBase : KetherBossBase
```
Day 50 suppression and all that


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherLastBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnOverloadActivated(int)](/api/KetherBoss/KetherBossBase#onoverloadactivated-int), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Misc/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Misc/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KetherLastBossBase()

```csharp
public KetherLastBossBase()
```

## Fields

### _arriveEarthquake

```csharp
private const float _arriveEarthquake = 3
```
#INC


#### Field Value

**Type:** System.Single

### _arriveEarthquakeTimer

```csharp
private UnscaledTimer _arriveEarthquakeTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _contUpdateTimer

```csharp
private UnscaledTimer _contUpdateTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _effects

```csharp
private KetherLastEffectBase[] _effects
```
#INC


#### Field Value

**Type:** KetherBoss.KetherLastEffectBase[]

### _energyLevel

```csharp
private static int _energyLevel
```
#INC


#### Field Value

**Type:** System.Int32

### _energyLevelInv

```csharp
private static float _energyLevelInv
```
#INC


#### Field Value

**Type:** System.Single

### _energyMax

```csharp
private float _energyMax
```
#INC


#### Field Value

**Type:** System.Single

### _groundLevelBgTurnOn

```csharp
private KetherLastBossBase.KetherLastEvent _groundLevelBgTurnOn
```

#### Field Value

**Type:** KetherBoss.KetherLastBossBase.KetherLastEvent

### _lastInit

```csharp
private bool _lastInit
```
#INC


#### Field Value

**Type:** System.Boolean

### _lightOnEvent

```csharp
private KetherLastBossBase.KetherLastEvent _lightOnEvent
```

#### Field Value

**Type:** KetherBoss.KetherLastBossBase.KetherLastEvent

### _startDelayTime

```csharp
private const float _startDelayTime = 2
```
#INC


#### Field Value

**Type:** System.Single

### _startDelayTimer

```csharp
private UnscaledTimer _startDelayTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _startEqSpeed

```csharp
private float _startEqSpeed
```
#INC


#### Field Value

**Type:** System.Single

### backgroundMover

```csharp
public KetherBackgroundMover backgroundMover
```
#INC


#### Field Value

**Type:** KetherBoss.KetherBackgroundMover

### bgm0

```csharp
private const string bgm0 = "Sounds/BGM/Boss/Event/50/1_the night sky"
```
#INC


#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Sounds/BGM/Boss/Event/50/2_Dark Fantasy Studio-Sun and moon"
```
#INC


#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Sounds/BGM/Boss/Event/50/3_Dark Fantasy Studio-You are a giant"
```
#INC


#### Field Value

**Type:** System.String

### bgMoverSrc

```csharp
private const string bgMoverSrc = "Effect/SefiraBoss/Kether/KetherBackgroundMover"
```
#INC


#### Field Value

**Type:** System.String

### convEnergyDic

```csharp
private Dictionary<float, int> convEnergyDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Single,System.Int32}

### convEnergyPercent

```csharp
private static float[] convEnergyPercent
```
#INC


#### Field Value

**Type:** System.Single[]

### convEnergyQueue

```csharp
private Queue<float> convEnergyQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{System.Single}

### LaserCast

```csharp
public static string LaserCast
```
#INC


#### Field Value

**Type:** System.String

### LaserLoad

```csharp
public static string LaserLoad
```
#INC


#### Field Value

**Type:** System.String

### LaserPing

```csharp
public static string LaserPing
```
#INC


#### Field Value

**Type:** System.String

### parentName

```csharp
private const string parentName = "KetherEnergyConcentrate"
```
#INC


#### Field Value

**Type:** System.String

### ShakeDown

```csharp
public static string ShakeDown
```
#INC


#### Field Value

**Type:** System.String

### ShakeEnd

```csharp
public static string ShakeEnd
```
#INC


#### Field Value

**Type:** System.String

### ShakeMove

```csharp
public static string ShakeMove
```
#INC


#### Field Value

**Type:** System.String

### ShakeStart

```csharp
public static string ShakeStart
```
#INC


#### Field Value

**Type:** System.String

### soundFolder

```csharp
public const string soundFolder = "Sounds/BGM/Boss/Kether/"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### _currentQueueTop

```csharp
private float _currentQueueTop { get; }
```

#### Property Value

**Type:** System.Single

### CurrentLevel

```csharp
public int CurrentLevel { get; private set; }
```
#INC


#### Property Value

**Type:** System.Int32

### EffectPivot

```csharp
public Transform EffectPivot { get; private set; }
```
#INC


#### Property Value

**Type:** UnityEngine.Transform

### EnergyUnit

```csharp
private float EnergyUnit { get; }
```

#### Property Value

**Type:** System.Single

### LightOnEvent

```csharp
public KetherLastBossBase.KetherLastEvent LightOnEvent { get; }
```

#### Property Value

**Type:** KetherBoss.KetherLastBossBase.KetherLastEvent

## Methods

### AddEffect(KetherLastEffectType, bool)

```csharp
public KetherLastEffectBase AddEffect(KetherLastEffectType type, bool overwrite = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `KetherBoss.KetherLastEffectType` |  |
| `overwrite` | `System.Boolean` |  |

#### Returns

**Type:** KetherBoss.KetherLastEffectBase

### DestroyBackgroundMover()

```csharp
public void DestroyBackgroundMover()
```
#INC


### EnergyLevelChange(int)

```csharp
public void EnergyLevelChange(int currentLevel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### EnergyUpdate()

```csharp
private void EnergyUpdate()
```
#INC


### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### FixEnergy()

```csharp
private void FixEnergy()
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

### GetEffect(KetherLastEffectType)

```csharp
public KetherLastEffectBase GetEffect(KetherLastEffectType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `KetherBoss.KetherLastEffectType` |  |

#### Returns

**Type:** KetherBoss.KetherLastEffectBase

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

### IsStartEmergencyBgm()

```csharp
public override bool IsStartEmergencyBgm()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### MakeKetherSound(string)

```csharp
public void MakeKetherSound(string sound)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `System.String` |  |

### OnCleared()

```csharp
public override void OnCleared()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### TerminateEffect(KetherLastEffectType)

```csharp
public void TerminateEffect(KetherLastEffectType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `KetherBoss.KetherLastEffectType` |  |

### ToCredit()

```csharp
public void ToCredit()
```
#INC


### TurnOnArriveEarthquake()

```csharp
public void TurnOnArriveEarthquake()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC

