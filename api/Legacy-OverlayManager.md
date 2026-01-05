# Class OverlayManager

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OverlayManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

### commonLib

```csharp
public OverlayManager.OverlayCommonDesc commonLib
```

#### Field Value

**Type:** Legacy.OverlayManager.OverlayCommonDesc

### normalLib

```csharp
public OverlayManager.OverlayNormalDesc normalLib
```

#### Field Value

**Type:** Legacy.OverlayManager.OverlayNormalDesc

### randomLib

```csharp
public OverlayManager.OverlayRandomDesc randomLib
```

#### Field Value

**Type:** Legacy.OverlayManager.OverlayRandomDesc

### statKey

```csharp
public string[] statKey
```

#### Field Value

**Type:** System.String[]

## Properties

### instance

```csharp
public static OverlayManager instance { get; }
```

#### Property Value

**Type:** Legacy.OverlayManager

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### LoadData(List<string>, List<string>, List<string>, List<OverlayNormalDescElement>, List<OverlayRandomDescElement>, List<OverlayCommonDescElement>)

```csharp
public void LoadData(List<string> nKey, List<string> rKey, List<string> cKey, List<OverlayManager.OverlayNormalDescElement> nDesc, List<OverlayManager.OverlayRandomDescElement> rDesc, List<OverlayManager.OverlayCommonDescElement> cDesc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nKey` | `System.Collections.Generic.List{System.String}` |  |
| `rKey` | `System.Collections.Generic.List{System.String}` |  |
| `cKey` | `System.Collections.Generic.List{System.String}` |  |
| `nDesc` | `System.Collections.Generic.List{Legacy.OverlayManager.OverlayNormalDescElement}` |  |
| `rDesc` | `System.Collections.Generic.List{Legacy.OverlayManager.OverlayRandomDescElement}` |  |
| `cDesc` | `System.Collections.Generic.List{Legacy.OverlayManager.OverlayCommonDescElement}` |  |

### SetAgentDescription(AgentModel)

```csharp
public void SetAgentDescription(AgentModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |
