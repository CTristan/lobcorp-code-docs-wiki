---
uid: Global.GeburahBossBase
canonical_path: /api/Global/Misc/GeburahBossBase
---

# Class GeburahBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahBossBase : SefiraBossBase
```

extends [SefiraBossBase](/api/Global/Misc/SefiraBossBase)

Gebura's core suppression. Ends when [The Red Mist](/api/Global/Script/GeburahCoreScript) is defeated. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Misc/SefiraBossBase) → GeburahBossBase

## Inherited Members
[_closeEffectTime](/api/Global/Misc/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Misc/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Misc/SefiraBossBase#descappearprob), [generalScript](/api/Global/Misc/SefiraBossBase#generalscript), [generalAnim](/api/Global/Misc/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Misc/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Misc/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Misc/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Misc/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Misc/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Misc/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Misc/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Misc/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Misc/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Misc/SefiraBossBase#cameradesctimer), [descList](/api/Global/Misc/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Misc/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Misc/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Misc/SefiraBossBase#defaultcleareffect-params-object), [OnOverloadActivated(int)](/api/Global/Misc/SefiraBossBase#onoverloadactivated-int), [OnDestroy()](/api/Global/Misc/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Misc/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Misc/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Misc/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Misc/SefiraBossBase#getdescfreq), [ClearDescTexts()](/api/Global/Misc/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Misc/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Misc/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Misc/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Misc/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Misc/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahBossBase()

```csharp
public GeburahBossBase()
```
#INC


## Fields

### _hexaEffect

```csharp
private UnscaledTimer _hexaEffect
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _hexagonTime

```csharp
private const float _hexagonTime = 4
```
#INC


#### Field Value

**Type:** System.Single

### _isInit

```csharp
private bool _isInit
```
#INC


#### Field Value

**Type:** System.Boolean

### _phase

```csharp
private int _phase
```
#INC


#### Field Value

**Type:** System.Int32

### animSrc

```csharp
private const string animSrc = "GeburahCoreAnim"
```
#INC


#### Field Value

**Type:** System.String

### bgm1

```csharp
private const string bgm1 = "Geburah/1_Tilarids - Distorted Night"
```
#INC


#### Field Value

**Type:** System.String

### bgm2

```csharp
private const string bgm2 = "Geburah/2_Tilarids - Insignia Decay"
```
#INC


#### Field Value

**Type:** System.String

### blackColor

```csharp
private const string blackColor = "#350000FF"
```
#INC


#### Field Value

**Type:** System.String

### geburahBase

```csharp
private const string geburahBase = "GeburahCoreScript"
```
#INC


#### Field Value

**Type:** System.String

### hexa_black

```csharp
private Color hexa_black
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### hexa_red

```csharp
private Color hexa_red
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### hexagon

```csharp
private CameraFilterPack_AAA_SuperHexagon hexagon
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_AAA_SuperHexagon

### model

```csharp
public SefiraBossCreatureModel model
```
#INC


#### Field Value

**Type:** Global.SefiraBossCreatureModel

### redColor

```csharp
private const string redColor = "#FF0000FF"
```
#INC


#### Field Value

**Type:** System.String

### startNode

```csharp
private const string startNode = "dept-geburah-4"
```
#INC


#### Field Value

**Type:** System.String

### superComputer

```csharp
private CameraFilterPack_AAA_SuperComputer superComputer
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_AAA_SuperComputer

### vignetting

```csharp
private CameraFilterPack_TV_Vignetting vignetting
```
#INC


#### Field Value

**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties

### Script

```csharp
private GeburahCoreScript Script { get; }
```

#### Property Value

**Type:** Global.GeburahCoreScript

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
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

### InitModel()

```csharp
public void InitModel()
```
#INC


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


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### StartCameraMoveEndFirst()

```csharp
private void StartCameraMoveEndFirst()
```
#INC


### StartHexagonEffect()

```csharp
public void StartHexagonEffect()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC

