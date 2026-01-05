# Class KetherBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → KetherBossBase

## Inherited Members
[_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnKetherStart()](/api/SefiraBossBase#onketherstart), [OnStageEnd()](/api/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/SefiraBossBase#ondestroy), [IsCleared()](/api/SefiraBossBase#iscleared), [IsReadyToClose()](/api/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/SefiraBossBase#isstartemergencybgm), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KetherBossBase()

```csharp
public KetherBossBase()
```

## Fields

### _currentQliphothLevel

```csharp
protected int _currentQliphothLevel
```

#### Field Value

**Type:** System.Int32

### bossBaseList

```csharp
public List<SefiraBossBase> bossBaseList
```

#### Field Value

**Type:** System.Collections.Generic.List{SefiraBossBase}

### builder

```csharp
protected StringBuilder builder
```

#### Field Value

**Type:** System.Text.StringBuilder

### ModelHPFactor

```csharp
public const float ModelHPFactor = 0.6
```

#### Field Value

**Type:** System.Single

### type

```csharp
public KetherBossType type
```

#### Field Value

**Type:** Global.KetherBossType

## Properties

### QliphothOverloadLevel

```csharp
public override int QliphothOverloadLevel { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

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

### OnStageStart()

```csharp
public override void OnStageStart()
```

### StringFormat(string, params object[])

```csharp
public string StringFormat(string format, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format` | `System.String` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### Update()

```csharp
public override void Update()
```
