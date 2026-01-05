# Class GameSettingModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameSettingModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GameSettingModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GameSettingModel()

```csharp
public GameSettingModel()
```

## Properties

### instance

```csharp
public static GameSettingModel instance { get; }
```

#### Property Value

**Type:** Global.GameSettingModel

## Methods

### FixInvalidResolution()

```csharp
public void FixInvalidResolution()
```

### GetCurrentFullScreenMode()

```csharp
public GameFullScreenMode GetCurrentFullScreenMode()
```

#### Returns

**Type:** Global.GameFullScreenMode

### GetCurrentTextureQuality()

```csharp
public int GetCurrentTextureQuality()
```

#### Returns

**Type:** System.Int32

### GetResolutionList()

```csharp
public void GetResolutionList()
```

### InitResolution()

```csharp
public void InitResolution()
```

### SetCurrentTextureQuality(int)

```csharp
public void SetCurrentTextureQuality(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetResolution(int, int, GameFullScreenMode)

```csharp
public void SetResolution(int width, int height, GameFullScreenMode mode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `width` | `System.Int32` |  |
| `height` | `System.Int32` |  |
| `mode` | `Global.GameFullScreenMode` |  |
