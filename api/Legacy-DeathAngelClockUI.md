# Class DeathAngelClockUI

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelClockUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeathAngelClockUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeathAngelClockUI()

```csharp
public DeathAngelClockUI()
```

## Fields

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

### nameElap

```csharp
[HideInInspector]
public float nameElap
```

#### Field Value

**Type:** System.Single

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

### EffectTime

```csharp
public float EffectTime { get; }
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

### ForcelyRelease()

```csharp
public void ForcelyRelease()
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

### RevealName()

```csharp
public void RevealName()
```

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

### Update()

```csharp
public void Update()
```
