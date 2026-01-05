# Class NetzachBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class NetzachBossBase : SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → NetzachBossBase

## Inherited Members
[_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnStageEnd()](/api/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/SefiraBossBase#ondestroy), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/SefiraBossBase#getdesctype-float), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### NetzachBossBase()

```csharp
public NetzachBossBase()
```

## Methods

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

### OnStageStart()

```csharp
public override void OnStageStart()
```

### RecoverAll()

```csharp
public void RecoverAll()
```

### StartEffect()

```csharp
public void StartEffect()
```
