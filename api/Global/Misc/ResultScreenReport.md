---
uid: Global.ResultScreen.Report
canonical_path: /api/Global/Misc/ResultScreenReport
---

# Class ResultScreen.Report

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResultScreen.Report
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResultScreen.Report

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Report()

```csharp
public Report()
```

## Fields

### buttons

```csharp
public ResultScreen.ReportButton[] buttons
```

#### Field Value

**Type:** Global.ResultScreen.ReportButton[]

### day

```csharp
public Text day
```

#### Field Value

**Type:** UnityEngine.UI.Text

### defaultButtons

```csharp
public GameObject[] defaultButtons
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### emergencyColor

```csharp
public Color[] emergencyColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### gatheredEnergy

```csharp
public Text gatheredEnergy
```

#### Field Value

**Type:** UnityEngine.UI.Text

### histories

```csharp
public ResultScreen.HistoryData[] histories
```

#### Field Value

**Type:** Global.ResultScreen.HistoryData[]

### missionBoard

```csharp
public ResultScreen.Report.ClearedMissionBoard missionBoard
```

#### Field Value

**Type:** Global.ResultScreen.Report.ClearedMissionBoard

### nextDayClicked

```csharp
public GameObject nextDayClicked
```

#### Field Value

**Type:** UnityEngine.GameObject

### notButton

```csharp
public ResultScreen.NotButton[] notButton
```

#### Field Value

**Type:** Global.ResultScreen.NotButton[]

### ordsAndEmers

```csharp
public GameObject[] ordsAndEmers
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### promoted

```csharp
public ResultScreen.Report.PromotedAgents promoted
```

#### Field Value

**Type:** Global.ResultScreen.Report.PromotedAgents

### Rank

```csharp
public Text Rank
```

#### Field Value

**Type:** UnityEngine.UI.Text

### results

```csharp
public List<Result> results
```

#### Field Value

**Type:** System.Collections.Generic.List{Result}

### returnClicked

```csharp
public GameObject returnClicked
```

#### Field Value

**Type:** UnityEngine.GameObject

### Reward

```csharp
public Text Reward
```

#### Field Value

**Type:** UnityEngine.UI.Text

### rootGameObject

```csharp
public GameObject rootGameObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### selectedOrdsAndEmers

```csharp
public List<History> selectedOrdsAndEmers
```

#### Field Value

**Type:** System.Collections.Generic.List{History}

### stageRewardInfo

```csharp
private StageRewardTypeInfo stageRewardInfo
```

#### Field Value

**Type:** Global.StageRewardTypeInfo

### SurvivalRateColor

```csharp
public Gradient SurvivalRateColor
```

#### Field Value

**Type:** UnityEngine.Gradient

### textBlue

```csharp
public Color textBlue
```

#### Field Value

**Type:** UnityEngine.Color

### textRed

```csharp
public Color textRed
```

#### Field Value

**Type:** UnityEngine.Color

### textYellow

```csharp
public Color textYellow
```

#### Field Value

**Type:** UnityEngine.Color

### time

```csharp
public Text[] time
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### tortalLob

```csharp
public Text tortalLob
```

#### Field Value

**Type:** UnityEngine.UI.Text

### workerAlive

```csharp
public Text[] workerAlive
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### workerDead

```csharp
public Text[] workerDead
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### workerPromoted

```csharp
public Text workerPromoted
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### GetButton(int)

```csharp
public ResultScreen.ReportButton GetButton(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ResultScreen.ReportButton

### OnManagementEnd()

```csharp
public void OnManagementEnd()
```

### Update()

```csharp
public void Update()
```
