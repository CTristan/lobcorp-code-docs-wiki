# Class KetherZeroBossBase

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherZeroBossBase : KetherBossBase, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/SefiraBossBase) → [KetherBossBase](/api/KetherBoss-KetherBossBase) → KetherZeroBossBase

## Inherited Members
[ModelHPFactor](/api/KetherBoss-KetherBossBase#modelhpfactor), [type](/api/KetherBoss-KetherBossBase#type), [builder](/api/KetherBoss-KetherBossBase#builder), [bossBaseList](/api/KetherBoss-KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss-KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss-KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss-KetherBossBase#oncleared), [Update()](/api/KetherBoss-KetherBossBase#update), [FixedUpdate()](/api/KetherBoss-KetherBossBase#fixedupdate), [OnOverloadActivated(int)](/api/KetherBoss-KetherBossBase#onoverloadactivated-int), [QliphothOverloadLevel](/api/KetherBoss-KetherBossBase#qliphothoverloadlevel), [_descAppearProb](/api/SefiraBossBase#descappearprob), [generalScript](/api/SefiraBossBase#generalscript), [generalAnim](/api/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/SefiraBossBase#bgmsoundprefix), [modelList](/api/SefiraBossBase#modellist), [sefiraEnum](/api/SefiraBossBase#sefiraenum), [closeEffectType](/api/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/SefiraBossBase#closetimer), [_closeEffectMethod](/api/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/SefiraBossBase#cameradesctimer), [descList](/api/SefiraBossBase#desclist), [OnKetherStart()](/api/SefiraBossBase#onketherstart), [OnStageEnd()](/api/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/SefiraBossBase#defaultcleareffect-params-object), [GetDamageInfo()](/api/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/SefiraBossBase#isstartemergencybgm), [Sefira](/api/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KetherZeroBossBase()

```csharp
public KetherZeroBossBase()
```

## Methods

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

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnFixerClawSuppressed()

```csharp
public void OnFixerClawSuppressed()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```
