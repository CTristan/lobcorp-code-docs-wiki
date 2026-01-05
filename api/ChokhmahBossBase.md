# Class ChokhmahBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChokhmahBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → ChokhmahBossBase

## Inherited Members
[_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnStageEnd()](/api/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ChokhmahBossBase()

```csharp
public ChokhmahBossBase()
```

## Fields

### ketherValue

```csharp
public static float[] ketherValue
```

#### Field Value

**Type:** System.Single[]

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

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

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

### StartVhsEffect()

```csharp
public void StartVhsEffect()
```

### Update()

```csharp
public override void Update()
```
