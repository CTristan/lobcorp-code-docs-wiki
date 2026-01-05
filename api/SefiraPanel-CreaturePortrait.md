# Class SefiraPanel.CreaturePortrait

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraPanel.CreaturePortrait
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraPanel.CreaturePortrait

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreaturePortrait()

```csharp
public CreaturePortrait()
```

## Fields

### creature

```csharp
public CreatureModel creature
```

#### Field Value

**Type:** Global.CreatureModel

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

### isInit

```csharp
public bool isInit
```

#### Field Value

**Type:** System.Boolean

### portrait

```csharp
public Image portrait
```

#### Field Value

**Type:** UnityEngine.UI.Image

### riskColor

```csharp
public List<MaskableGraphic> riskColor
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### riskLevel

```csharp
public Text riskLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetCreature(CreatureModel, int, Color)

```csharp
public void SetCreature(CreatureModel creature, int sefiraLevel, Color sefiraColor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `sefiraLevel` | `System.Int32` |  |
| `sefiraColor` | `UnityEngine.Color` |  |

### SetEmpty(Color)

```csharp
public void SetEmpty(Color sefiraColor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraColor` | `UnityEngine.Color` |  |

### UpdateCheck()

```csharp
public void UpdateCheck()
```
