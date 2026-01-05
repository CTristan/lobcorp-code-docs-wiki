# Class BossBirdAnim.NarrationData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdAnim.NarrationData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BossBirdAnim.NarrationData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### NarrationData(string, float, NarrationEndEvent, NarrationState)

```csharp
public NarrationData(string text, float time, BossBirdAnim.NarrationUI.NarrationEndEvent endEvent, BossBird.NarrationState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `time` | `System.Single` |  |
| `endEvent` | `Global.BossBirdAnim.NarrationUI.NarrationEndEvent` |  |
| `state` | `Global.BossBird.NarrationState` |  |

## Fields

### endEvent

```csharp
public BossBirdAnim.NarrationUI.NarrationEndEvent endEvent
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.NarrationEndEvent

### fadeEvent

```csharp
public BossBirdAnim.NarrationUI.FadeOutEvent fadeEvent
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI.FadeOutEvent

### narrationState

```csharp
public BossBird.NarrationState narrationState
```

#### Field Value

**Type:** Global.BossBird.NarrationState

### narrationText

```csharp
public string narrationText
```

#### Field Value

**Type:** System.String

### narrationTime

```csharp
public float narrationTime
```

#### Field Value

**Type:** System.Single
