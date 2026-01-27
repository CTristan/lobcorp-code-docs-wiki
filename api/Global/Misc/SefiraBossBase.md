---
uid: Global.SefiraBossBase
canonical_path: /api/Global/Misc/SefiraBossBase
---

# Class SefiraBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraBossBase
```
Base class for all core suppressions.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraBossBase

## Derived
[BinahBossBase](/api/Global/Misc/BinahBossBase), [ChesedBossBase](/api/Global/Misc/ChesedBossBase), [ChokhmahBossBase](/api/Global/Misc/ChokhmahBossBase), [GeburahBossBase](/api/Global/Misc/GeburahBossBase), [HodBossBase](/api/Global/Misc/HodBossBase), [MalkutBossBase](/api/Global/Misc/MalkutBossBase), [NetzachBossBase](/api/Global/Misc/NetzachBossBase), [TipherethBossBase](/api/Global/Misc/TipherethBossBase), [YesodBossBase](/api/Global/Misc/YesodBossBase), [KetherBossBase](/api/KetherBoss/KetherBossBase)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraBossBase()

```csharp
public SefiraBossBase()
```

## Fields

### _cameraDescTimer

```csharp
protected Timer _cameraDescTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _closeEffectMethod

```csharp
public SefiraBossBase.CloseEffect _closeEffectMethod
```

#### Field Value

**Type:** Global.SefiraBossBase.CloseEffect

### _closeEffectTime

```csharp
private const float _closeEffectTime = 5
```
#INC


#### Field Value

**Type:** System.Single

### _closeTimer

```csharp
public UnscaledTimer _closeTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _defaultDescFreq

```csharp
private const float _defaultDescFreq = 3
```
#INC


#### Field Value

**Type:** System.Single

### _descAppearProb

```csharp
public const float _descAppearProb = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### bgmSoundPrefix

```csharp
public const string bgmSoundPrefix = "Sounds/BGM/Boss/"
```
#INC


#### Field Value

**Type:** System.String

### closeEffectType

```csharp
public SefiraBossCloseEffectType closeEffectType
```
#INC


#### Field Value

**Type:** Global.SefiraBossCloseEffectType

### currentCloseEffectParam

```csharp
private List<object> currentCloseEffectParam
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Object}

### DefaultDamageInfo

```csharp
public static DamageInfo DefaultDamageInfo
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### DefaultDefenseInfo

```csharp
public static DefenseInfo DefaultDefenseInfo
```
#INC


#### Field Value

**Type:** Global.DefenseInfo

### descList

```csharp
public List<SefiraBossDescUI> descList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraBossDescUI}

### generalAnim

```csharp
public const string generalAnim = "SefiraBossGeneral"
```
#INC


#### Field Value

**Type:** System.String

### generalScript

```csharp
public const string generalScript = "SefiraBossBase"
```
#INC


#### Field Value

**Type:** System.String

### modelList

```csharp
public List<SefiraBossCreatureModel> modelList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraBossCreatureModel}

### sefiraEnum

```csharp
public SefiraEnum sefiraEnum
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

## Properties

### QliphothOverloadLevel

```csharp
public virtual int QliphothOverloadLevel { get; }
```

#### Property Value

**Type:** System.Int32

### Sefira

```csharp
public Sefira Sefira { get; }
```

#### Property Value

**Type:** Global.Sefira

## Methods

### ClearDescTexts()

```csharp
public virtual void ClearDescTexts()
```
#INC


### DefaultClearEffect(params object[])

```csharp
public virtual void DefaultClearEffect(params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### GetDamageInfo()

```csharp
public virtual DamageInfo GetDamageInfo()
```
#INC


#### Returns

**Type:** Global.DamageInfo

### GetDefenseInfo()

```csharp
public virtual DefenseInfo GetDefenseInfo()
```
#INC


#### Returns

**Type:** Global.DefenseInfo

### GetDescFreq()

```csharp
public virtual float GetDescFreq()
```
#INC


#### Returns

**Type:** System.Single

### GetDescType(float)

```csharp
public virtual SefiraBossDescType GetDescType(float defaultProb = 0.5)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defaultProb` | `System.Single` |  |

#### Returns

**Type:** Global.SefiraBossDescType

### IsCleared()

```csharp
public virtual bool IsCleared()
```
#INC


#### Returns

**Type:** System.Boolean

### IsReadyToClose()

```csharp
public virtual bool IsReadyToClose()
```
#INC


#### Returns

**Type:** System.Boolean

### IsStartEmergencyBgm()

```csharp
public virtual bool IsStartEmergencyBgm()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeSound(string)

```csharp
public virtual SoundEffectPlayer MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundAttachCamera(string)

```csharp
public virtual SoundEffectPlayer MakeSoundAttachCamera(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnChangePhase()

```csharp
public virtual void OnChangePhase()
```
#INC


### OnCleared()

```csharp
public virtual void OnCleared()
```
#INC


### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnKetherStart()

```csharp
public virtual void OnKetherStart()
```
#INC


### OnOverloadActivated(int)

```csharp
public virtual void OnOverloadActivated(int currentLevel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnRemoveDesc(SefiraBossDescUI)

```csharp
public void OnRemoveDesc(SefiraBossDescUI ui)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ui` | `Global.SefiraBossDescUI` |  |

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```
#INC


### OnStageStart()

```csharp
public virtual void OnStageStart()
```
#INC
#code-generated


### Update()

```csharp
public virtual void Update()
```
#INC

