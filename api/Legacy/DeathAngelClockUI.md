---
uid: Legacy.DeathAngelClockUI
canonical_path: /api/Legacy/DeathAngelClockUI
---

# Class DeathAngelClockUI

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelClockUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeathAngelClockUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngelClockUI()

```csharp
public DeathAngelClockUI()
```

## Fields

### _adventTime

```csharp
[SerializeField]
private float _adventTime
```

#### Field Value

**Type:** System.Single

### _bellFrequencyTime

```csharp
[SerializeField]
private float _bellFrequencyTime
```

#### Field Value

**Type:** System.Single

### _effectTime

```csharp
[SerializeField]
private float _effectTime
```

#### Field Value

**Type:** System.Single

### _nameColorTime

```csharp
[SerializeField]
private float _nameColorTime
```

#### Field Value

**Type:** System.Single

### _prewarmTime

```csharp
[SerializeField]
private float _prewarmTime
```

#### Field Value

**Type:** System.Single

### adventElap

```csharp
private float adventElap
```

#### Field Value

**Type:** System.Single

### angel

```csharp
private DeathAngel angel
```

#### Field Value

**Type:** Legacy.DeathAngel

### ApostleDesc

```csharp
public Text ApostleDesc
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ApostleName

```csharp
public Text[] ApostleName
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### attachedObject

```csharp
public GameObject attachedObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### audioSrc

```csharp
public AudioSource audioSrc
```

#### Field Value

**Type:** UnityEngine.AudioSource

### bellCount

```csharp
private int bellCount
```

#### Field Value

**Type:** System.Int32

### bellSoundClip

```csharp
public AudioClip bellSoundClip
```

#### Field Value

**Type:** UnityEngine.AudioClip

### clockArrow

```csharp
public GameObject clockArrow
```

#### Field Value

**Type:** UnityEngine.GameObject

### currentApostleCount

```csharp
private int currentApostleCount
```

#### Field Value

**Type:** System.Int32

### currentNameItem

```csharp
private Text currentNameItem
```

#### Field Value

**Type:** UnityEngine.UI.Text

### descEffect

```csharp
private bool descEffect
```

#### Field Value

**Type:** System.Boolean

### descElap

```csharp
private float descElap
```

#### Field Value

**Type:** System.Single

### descTime

```csharp
[SerializeField]
private float descTime
```

#### Field Value

**Type:** System.Single

### effectEnabled

```csharp
private bool effectEnabled
```

#### Field Value

**Type:** System.Boolean

### elap

```csharp
private float elap
```

#### Field Value

**Type:** System.Single

### endCall

```csharp
public DeathAngelClockUI.EndCalled endCall
```

#### Field Value

**Type:** Legacy.DeathAngelClockUI.EndCalled

### globalCanvas

```csharp
public Canvas globalCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### isAdvent

```csharp
[HideInInspector]
public bool isAdvent
```

#### Field Value

**Type:** System.Boolean

### nameEffect

```csharp
private bool nameEffect
```

#### Field Value

**Type:** System.Boolean

### nameElap

```csharp
[HideInInspector]
public float nameElap
```

#### Field Value

**Type:** System.Single

### nameList

```csharp
private List<AgentName> nameList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### nameTime

```csharp
[SerializeField]
private float nameTime
```

#### Field Value

**Type:** System.Single

### plagueDoc

```csharp
private PlagueDoctor plagueDoc
```

#### Field Value

**Type:** Legacy.PlagueDoctor

### prewarmed

```csharp
private bool prewarmed
```

#### Field Value

**Type:** System.Boolean

### readyForAdvent

```csharp
private bool readyForAdvent
```

#### Field Value

**Type:** System.Boolean

### revealedName

```csharp
private AgentName revealedName
```

#### Field Value

**Type:** Global.AgentName

### setColor

```csharp
private bool setColor
```

#### Field Value

**Type:** System.Boolean

### tempBlockReleaseTimer

```csharp
private UnscaledTimer tempBlockReleaseTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

### tempClockBlockingMaximumEnabled

```csharp
private bool tempClockBlockingMaximumEnabled
```

#### Field Value

**Type:** System.Boolean

### tickSoundClip

```csharp
public AudioClip tickSoundClip
```

#### Field Value

**Type:** UnityEngine.AudioClip

### tickSrc

```csharp
public AudioSource tickSrc
```

#### Field Value

**Type:** UnityEngine.AudioSource

### uiRoot

```csharp
public GameObject uiRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### currentNameOutLine

```csharp
private Outline currentNameOutLine { get; }
```

#### Property Value

**Type:** UnityEngine.UI.Outline

### EffectTime

```csharp
public float EffectTime { get; }
```

#### Property Value

**Type:** System.Single

### localScale

```csharp
private Vector3 localScale { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### tempClockBlockTime

```csharp
private float tempClockBlockTime { get; }
```

#### Property Value

**Type:** System.Single

### uiScale

```csharp
public Vector3 uiScale { get; set; }
```

#### Property Value

**Type:** UnityEngine.Vector3

## Methods

### AddName(AgentName)

```csharp
public void AddName(AgentName name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |

### AddName(params AgentName[])

```csharp
public void AddName(params AgentName[] input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `Global.AgentName[]` |  |

### AddNameAposte(PlagueDoctor, int, List<DeathAngelApostle>)

```csharp
private void AddNameAposte(PlagueDoctor doctor, int current, List<DeathAngelApostle> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `doctor` | `Legacy.PlagueDoctor` |  |
| `current` | `System.Int32` |  |
| `list` | `System.Collections.Generic.List{Legacy.DeathAngelApostle}` |  |

### AdventEffect()

```csharp
public void AdventEffect()
```

### AdventEffect(AgentName, string)

```csharp
public void AdventEffect(AgentName name, string paramData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |
| `paramData` | `System.String` |  |

### AdventEvent()

```csharp
private void AdventEvent()
```

### ApostleAdventEvent()

```csharp
public void ApostleAdventEvent()
```

### ApostleEffect(AgentName, ParameterData)

```csharp
public void ApostleEffect(AgentName name, CreatureStaticData.ParameterData paramData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |
| `paramData` | `Global.CreatureStaticData.ParameterData` |  |

### ApostleInit()

```csharp
public void ApostleInit()
```

### CameraMoveEnd()

```csharp
public void CameraMoveEnd()
```

### EndApostleEvent()

```csharp
private void EndApostleEvent()
```

### EndDescEffect()

```csharp
private void EndDescEffect()
```

### EndNameEffect()

```csharp
private void EndNameEffect()
```

### ForcelyRelease()

```csharp
public void ForcelyRelease()
```

### Init()

```csharp
private void Init()
```

### Init(DeathAngel)

```csharp
public void Init(DeathAngel angel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angel` | `Legacy.DeathAngel` |  |

### Init(PlagueDoctor)

```csharp
public void Init(PlagueDoctor doctor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `doctor` | `Legacy.PlagueDoctor` |  |

### NameColor(float)

```csharp
private void NameColor(float elap)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elap` | `System.Single` |  |

### OnLuciferEnd()

```csharp
public void OnLuciferEnd()
```

### PlayBellSound()

```csharp
public void PlayBellSound()
```

### PlayTickSound()

```csharp
public void PlayTickSound()
```

### PrewarmDesc(float)

```csharp
private void PrewarmDesc(float elap)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elap` | `System.Single` |  |

### RevealName()

```csharp
public void RevealName()
```

### SetDescAlpha(float)

```csharp
private void SetDescAlpha(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetDir()

```csharp
public void SetDir()
```

### SetEndCallEvent(EndCalled)

```csharp
public void SetEndCallEvent(DeathAngelClockUI.EndCalled called)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `called` | `Legacy.DeathAngelClockUI.EndCalled` |  |

### SetNameColor(float)

```csharp
private void SetNameColor(float percent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `percent` | `System.Single` |  |

### StartDescEffect(string)

```csharp
public void StartDescEffect(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### StartEffectAfterLucifer()

```csharp
public void StartEffectAfterLucifer()
```

### StartNameEffect()

```csharp
private void StartNameEffect()
```

### Update()

```csharp
public void Update()
```
