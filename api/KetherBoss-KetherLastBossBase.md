# Class KetherLastBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherLastBossBase : KetherBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → [KetherBossBase](/api/KetherBoss-KetherBossBase) → KetherLastBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss-KetherBossBase#modelhpfactor), [type](/api/KetherBoss-KetherBossBase#type), [builder](/api/KetherBoss-KetherBossBase#builder), [bossBaseList](/api/KetherBoss-KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss-KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss-KetherBossBase#stringformat-string-params-object), [OnOverloadActivated(int)](/api/KetherBoss-KetherBossBase#onoverloadactivated-int), [QliphothOverloadLevel](/api/KetherBoss-KetherBossBase#qliphothoverloadlevel), [_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnKetherStart()](/api/SefiraBossBase#onketherstart), [OnStageEnd()](/api/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KetherLastBossBase()

```csharp
public KetherLastBossBase()
```

## Fields

### backgroundMover

```csharp
public KetherBackgroundMover backgroundMover
```

#### Field Value

**Type:** KetherBoss.KetherBackgroundMover

### LaserCast

```csharp
public static string LaserCast
```

#### Field Value

**Type:** System.String

### LaserLoad

```csharp
public static string LaserLoad
```

#### Field Value

**Type:** System.String

### LaserPing

```csharp
public static string LaserPing
```

#### Field Value

**Type:** System.String

### ShakeDown

```csharp
public static string ShakeDown
```

#### Field Value

**Type:** System.String

### ShakeEnd

```csharp
public static string ShakeEnd
```

#### Field Value

**Type:** System.String

### ShakeMove

```csharp
public static string ShakeMove
```

#### Field Value

**Type:** System.String

### ShakeStart

```csharp
public static string ShakeStart
```

#### Field Value

**Type:** System.String

### soundFolder

```csharp
public const string soundFolder = "Sounds/BGM/Boss/Kether/"
```

#### Field Value

**Type:** System.String

## Properties

### CurrentLevel

```csharp
public int CurrentLevel { get; }
```

#### Property Value

**Type:** System.Int32

### EffectPivot

```csharp
public Transform EffectPivot { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

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

### EnergyLevelChange(int)

```csharp
public void EnergyLevelChange(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

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

### GetEffect(KetherLastEffectType)

```csharp
public KetherLastEffectBase GetEffect(KetherLastEffectType type)
```

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

### MakeKetherSound(string)

```csharp
public void MakeKetherSound(string sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `System.String` |  |

### OnCleared()

```csharp
public override void OnCleared()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### TerminateEffect(KetherLastEffectType)

```csharp
public void TerminateEffect(KetherLastEffectType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `KetherBoss.KetherLastEffectType` |  |

### ToCredit()

```csharp
public void ToCredit()
```

### TurnOnArriveEarthquake()

```csharp
public void TurnOnArriveEarthquake()
```

### Update()

```csharp
public override void Update()
```
