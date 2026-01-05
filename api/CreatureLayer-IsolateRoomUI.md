# Class CreatureLayer.IsolateRoomUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureLayer.IsolateRoomUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureLayer.IsolateRoomUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### IsolateRoomUI()

```csharp
public IsolateRoomUI()
```

## Fields

### DamageSprite

```csharp
public Sprite[] DamageSprite
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### DisabledColor

```csharp
public Color DisabledColor
```

#### Field Value

**Type:** UnityEngine.Color

### FeelingStateColor

```csharp
public Color[] FeelingStateColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### FeelingStateIcon

```csharp
public Sprite[] FeelingStateIcon
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### MinusEnergyColor

```csharp
public Color MinusEnergyColor
```

#### Field Value

**Type:** UnityEngine.Color

### MinusTextColor

```csharp
public Color MinusTextColor
```

#### Field Value

**Type:** UnityEngine.Color

### PlusEnergyColor

```csharp
public Color PlusEnergyColor
```

#### Field Value

**Type:** UnityEngine.Color

### PlusTextColor

```csharp
public Color PlusTextColor
```

#### Field Value

**Type:** UnityEngine.Color

### RiskLevel

```csharp
public Sprite[] RiskLevel
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### RoomDisabledColor

```csharp
public Color RoomDisabledColor
```

#### Field Value

**Type:** UnityEngine.Color

### RoomEnabledColor

```csharp
public Color RoomEnabledColor
```

#### Field Value

**Type:** UnityEngine.Color

### ZeroColor

```csharp
public Color ZeroColor
```

#### Field Value

**Type:** UnityEngine.Color

### ZeroEnergyColor

```csharp
public Color ZeroEnergyColor
```

#### Field Value

**Type:** UnityEngine.Color

## Methods

### GetDamageSprite(RwbpType)

```csharp
public Sprite GetDamageSprite(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetFeelingStateData(CreatureFeelingState, out Sprite, out Color)

```csharp
public void GetFeelingStateData(CreatureFeelingState state, out Sprite sprite, out Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `color` | `UnityEngine.Color` |  |

### GetGeneratedEnergyColor(int, out Color, out Color)

```csharp
public void GetGeneratedEnergyColor(int value, out Color fill, out Color text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |
| `fill` | `UnityEngine.Color` |  |
| `text` | `UnityEngine.Color` |  |
