# Class SefiraBossBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraBossBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraBossBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** Global.Timer

### _closeEffectMethod

```csharp
public SefiraBossBase.CloseEffect _closeEffectMethod
```

#### Field Value

**Type:** Global.SefiraBossBase.CloseEffect

### _closeTimer

```csharp
public UnscaledTimer _closeTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### _descAppearProb

```csharp
public const float _descAppearProb = 0.3
```

#### Field Value

**Type:** System.Single

### bgmSoundPrefix

```csharp
public const string bgmSoundPrefix = "Sounds/BGM/Boss/"
```

#### Field Value

**Type:** System.String

### closeEffectType

```csharp
public SefiraBossCloseEffectType closeEffectType
```

#### Field Value

**Type:** Global.SefiraBossCloseEffectType

### DefaultDamageInfo

```csharp
public static DamageInfo DefaultDamageInfo
```

#### Field Value

**Type:** Global.DamageInfo

### DefaultDefenseInfo

```csharp
public static DefenseInfo DefaultDefenseInfo
```

#### Field Value

**Type:** Global.DefenseInfo

### descList

```csharp
public List<SefiraBossDescUI> descList
```

#### Field Value

**Type:** System.Collections.Generic.List{SefiraBossDescUI}

### generalAnim

```csharp
public const string generalAnim = "SefiraBossGeneral"
```

#### Field Value

**Type:** System.String

### generalScript

```csharp
public const string generalScript = "SefiraBossBase"
```

#### Field Value

**Type:** System.String

### modelList

```csharp
public List<SefiraBossCreatureModel> modelList
```

#### Field Value

**Type:** System.Collections.Generic.List{SefiraBossCreatureModel}

### sefiraEnum

```csharp
public SefiraEnum sefiraEnum
```

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

### DefaultClearEffect(params object[])

```csharp
public virtual void DefaultClearEffect(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```

### GetDamageInfo()

```csharp
public virtual DamageInfo GetDamageInfo()
```

#### Returns

**Type:** Global.DamageInfo

### GetDefenseInfo()

```csharp
public virtual DefenseInfo GetDefenseInfo()
```

#### Returns

**Type:** Global.DefenseInfo

### GetDescFreq()

```csharp
public virtual float GetDescFreq()
```

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

#### Returns

**Type:** System.Boolean

### IsReadyToClose()

```csharp
public virtual bool IsReadyToClose()
```

#### Returns

**Type:** System.Boolean

### IsStartEmergencyBgm()

```csharp
public virtual bool IsStartEmergencyBgm()
```

#### Returns

**Type:** System.Boolean

### MakeSound(string)

```csharp
public virtual SoundEffectPlayer MakeSound(string src)
```

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

### OnCleared()

```csharp
public virtual void OnCleared()
```

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnKetherStart()

```csharp
public virtual void OnKetherStart()
```

### OnOverloadActivated(int)

```csharp
public virtual void OnOverloadActivated(int currentLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnRemoveDesc(SefiraBossDescUI)

```csharp
public void OnRemoveDesc(SefiraBossDescUI ui)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ui` | `Global.SefiraBossDescUI` |  |

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```

### OnStageStart()

```csharp
public virtual void OnStageStart()
```

### Update()

```csharp
public virtual void Update()
```
