---
uid: Global.GameSettingModel
canonical_path: /api/Global/Model/GameSettingModel
---

# Class GameSettingModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameSettingModel
```
Holds game graphics settings options, like resolution, texture quality, and fullscreen mode.

Used by [OptionUI](/api/Global/UI/OptionUI) probably #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GameSettingModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GameSettingModel()

```csharp
public GameSettingModel()
```

## Fields

### _instance

```csharp
private static GameSettingModel _instance
```
#INC


#### Field Value

**Type:** Global.GameSettingModel

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
#INC


### GetCurrentFullScreenMode()

```csharp
public GameFullScreenMode GetCurrentFullScreenMode()
```
#INC


#### Returns

**Type:** Global.GameFullScreenMode

### GetCurrentTextureQuality()

```csharp
public int GetCurrentTextureQuality()
```
#INC


#### Returns

**Type:** System.Int32

### GetResolutionList()

```csharp
public void GetResolutionList()
```
#INC


### InitResolution()

```csharp
public void InitResolution()
```
#INC
#code-generated


### SetCurrentTextureQuality(int)

```csharp
public void SetCurrentTextureQuality(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetResolution(int, int, GameFullScreenMode)

```csharp
public void SetResolution(int width, int height, GameFullScreenMode mode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `width` | `System.Int32` |  |
| `height` | `System.Int32` |  |
| `mode` | `Global.GameFullScreenMode` |  |
