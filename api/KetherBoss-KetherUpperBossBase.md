# Class KetherUpperBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherUpperBossBase : KetherBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → [KetherBossBase](/api/KetherBoss-KetherBossBase) → KetherUpperBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss-KetherBossBase#modelhpfactor), [type](/api/KetherBoss-KetherBossBase#type), [builder](/api/KetherBoss-KetherBossBase#builder), [bossBaseList](/api/KetherBoss-KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss-KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss-KetherBossBase#stringformat-string-params-object), [FixedUpdate()](/api/KetherBoss-KetherBossBase#fixedupdate), [QliphothOverloadLevel](/api/KetherBoss-KetherBossBase#qliphothoverloadlevel), [_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnKetherStart()](/api/SefiraBossBase#onketherstart), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KetherUpperBossBase()

```csharp
public KetherUpperBossBase()
```

## Fields

### bufList

```csharp
public List<HodBossBuf> bufList
```

#### Field Value

**Type:** System.Collections.Generic.List{HodBossBuf}

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
