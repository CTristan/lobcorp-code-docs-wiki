---
uid: Global.ChokhmahBossBase
canonical_path: /api/Global/Misc/ChokhmahBossBase
---

# Class ChokhmahBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChokhmahBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → ChokhmahBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChokhmahBossBase()

```csharp
public ChokhmahBossBase()
```

## Fields

### _brokenTime

```csharp
private float _brokenTime
```

#### Field Value

**Type:** System.Single

### _brokenTimer

```csharp
private UnscaledTimer _brokenTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _currentSpaceCount

```csharp
private int _currentSpaceCount
```

#### Field Value

**Type:** System.Int32

### _phase

```csharp
private int _phase
```

#### Field Value

**Type:** System.Int32

### _qliphothAquired

```csharp
private bool _qliphothAquired
```

#### Field Value

**Type:** System.Boolean

### _qliphothClear

```csharp
private bool _qliphothClear
```

#### Field Value

**Type:** System.Boolean

### _startDelayTimer

```csharp
private Timer _startDelayTimer
```

#### Field Value

**Type:** Global.Timer

### _ui

```csharp
private ChokhmahPlaySpeedBlockUI _ui
```

#### Field Value

**Type:** GameStatusUI.ChokhmahPlaySpeedBlockUI

### _vhsLevel

```csharp
private int _vhsLevel
```

#### Field Value

**Type:** System.Int32

### _vhsTime

```csharp
private float _vhsTime
```

#### Field Value

**Type:** System.Single

### _vhsTimer

```csharp
private UnscaledTimer _vhsTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### animSrc

```csharp
private const string animSrc = "ChokhmahCoreAnim"
```

#### Field Value

**Type:** System.String

### animValue

```csharp
private static float[] animValue
```

#### Field Value

**Type:** System.Single[]

### bgm1

```csharp
private const string bgm1 = "Chokhmah/1_Tilarids - 090909090"
```

#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Chokhmah/2_Tilarids - circle-rombed oxygen"
```

#### Field Value

**Type:** System.String

### brokenEnd

```csharp
private static ChokhmahBossBase.BrokenScreen brokenEnd
```

#### Field Value

**Type:** Global.ChokhmahBossBase.BrokenScreen

### brokenStart

```csharp
private static ChokhmahBossBase.BrokenScreen brokenStart
```

#### Field Value

**Type:** Global.ChokhmahBossBase.BrokenScreen

### changeQliphothLevel

```csharp
private const int changeQliphothLevel = 6
```

#### Field Value

**Type:** System.Int32

### chokhmahBase

```csharp
private const string chokhmahBase = "ChokhmahCoreScript"
```

#### Field Value

**Type:** System.String

### clearQliphothLevel

```csharp
private const int clearQliphothLevel = 10
```

#### Field Value

**Type:** System.Int32

### firstChangeQliphothLevel

```csharp
private const int firstChangeQliphothLevel = 3
```

#### Field Value

**Type:** System.Int32

### grayScale

```csharp
private CameraFilterPack_Color_GrayScale grayScale
```

#### Field Value

**Type:** Global.CameraFilterPack_Color_GrayScale

### ketherValue

```csharp
public static float[] ketherValue
```

#### Field Value

**Type:** System.Single[]

### model

```csharp
private SefiraBossCreatureModel model
```

#### Field Value

**Type:** Global.SefiraBossCreatureModel

### screen

```csharp
private CameraFilterPack_Broken_Screen screen
```

#### Field Value

**Type:** Global.CameraFilterPack_Broken_Screen

### soundPrefix

```csharp
private const string soundPrefix = "SefiraBoss/Chokhmah/Chokma_Meltdown"
```

#### Field Value

**Type:** System.String

### stopSound

```csharp
private const string stopSound = "SefiraBoss/Chokhmah/Chokma_Space"
```

#### Field Value

**Type:** System.String

### targetCount

```csharp
private static MinMax targetCount
```

#### Field Value

**Type:** Global.MinMax

### timeMultiplyText

```csharp
private static int[] timeMultiplyText
```

#### Field Value

**Type:** System.Int32[]

### timeStopText

```csharp
private static int[] timeStopText
```

#### Field Value

**Type:** System.Int32[]

### timeValue

```csharp
private static float[] timeValue
```

#### Field Value

**Type:** System.Single[]

### totalEnergy

```csharp
private float totalEnergy
```

#### Field Value

**Type:** System.Single

### vhs

```csharp
private CameraFilterPack_TV_VHS vhs
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_VHS

### vhsEnd

```csharp
private static ChokhmahBossBase.TV_Vhs vhsEnd
```

#### Field Value

**Type:** Global.ChokhmahBossBase.TV_Vhs

### vhsStart

```csharp
private static ChokhmahBossBase.TV_Vhs vhsStart
```

#### Field Value

**Type:** Global.ChokhmahBossBase.TV_Vhs

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties

### ChokhmahQliphothLevel

```csharp
public int ChokhmahQliphothLevel { get; }
```

#### Property Value

**Type:** System.Int32

### Script

```csharp
public ChokhmahCoreScript Script { get; }
```

#### Property Value

**Type:** Global.ChokhmahCoreScript

## Methods

### CheckFunction(PlaySpeedSettingBlockFunction)

```csharp
public bool CheckFunction(PlaySpeedSettingBlockFunction function)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

#### Returns

**Type:** System.Boolean

### ExecutePanelty(List<ChokhmahPanelty>)

```csharp
public void ExecutePanelty(List<ChokhmahBossBase.ChokhmahPanelty> panelties)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panelties` | `System.Collections.Generic.List{ChokhmahBossBase.ChokhmahPanelty}` |  |

### ExtractTargetableAgent()

```csharp
private List<AgentModel> ExtractTargetableAgent()
```

#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GetBattleDesc(params int[])

```csharp
private string GetBattleDesc(params int[] id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32[]` |  |

#### Returns

**Type:** System.String

### GetDescFreq()

```csharp
public override float GetDescFreq()
```

#### Returns

**Type:** System.Single

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

### GetGrayscaleFade(int)

```csharp
private float GetGrayscaleFade(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### GetPaneltyType(AgentModel)

```csharp
private ChokhmahBossBase.ChokhmahPaneltyType GetPaneltyType(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** Global.ChokhmahBossBase.ChokhmahPaneltyType

### GetTargetAgentCount()

```csharp
public int GetTargetAgentCount()
```

#### Returns

**Type:** System.Int32

### IsCleared()

```csharp
public override bool IsCleared()
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

### OnKehterOverloadActivated(int)

```csharp
public void OnKehterOverloadActivated(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

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

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnTryTimeMultiply()

```csharp
public void OnTryTimeMultiply()
```

### OnTryTimePause()

```csharp
public void OnTryTimePause()
```

### StartBorkenEffect()

```csharp
public void StartBorkenEffect()
```

### StartCameraMoveEndFirst()

```csharp
private void StartCameraMoveEndFirst()
```

### StartVhsEffect()

```csharp
public void StartVhsEffect()
```

### Update()

```csharp
public override void Update()
```
