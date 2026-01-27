---
uid: Global.UIUtil
canonical_path: /api/Global/Misc/UIUtil
---

# Class UIUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UIUtil
```
Provides some common methods for UI elements, like displaying defense factors, text, icons, and changing alpha. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UIUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UIUtil()

```csharp
public UIUtil()
```

## Fields

### full

```csharp
public const float full = 1
```
#INC


#### Field Value

**Type:** System.Single

### half

```csharp
public const float half = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### quater

```csharp
public const float quater = 0.25
```
#INC


#### Field Value

**Type:** System.Single

### quaterHalf

```csharp
public const float quaterHalf = 0.75
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### DefenseSetFactor(DefenseInfo, Text[], bool)

```csharp
public static void DefenseSetFactor(DefenseInfo defenseInfo, Text[] text, bool bracket = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseInfo` | `Global.DefenseInfo` |  |
| `text` | `UnityEngine.UI.Text[]` |  |
| `bracket` | `System.Boolean` |  |

### DefenseSetFull(DefenseInfo, Text[], string)

```csharp
public static void DefenseSetFull(DefenseInfo defenseInfo, Text[] text, string divider = "")
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseInfo` | `Global.DefenseInfo` |  |
| `text` | `UnityEngine.UI.Text[]` |  |
| `divider` | `System.String` |  |

### DefenseSetOnlyText(DefenseInfo, Text[])

```csharp
public static void DefenseSetOnlyText(DefenseInfo defenseInfo, Text[] text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseInfo` | `Global.DefenseInfo` |  |
| `text` | `UnityEngine.UI.Text[]` |  |

### GetDefenseText(Type)

```csharp
public static string GetDefenseText(DefenseInfo.Type type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.DefenseInfo.Type` |  |

#### Returns

**Type:** System.String

### SetDefenseTypeIcon(DefenseInfo, Image[])

```csharp
public static void SetDefenseTypeIcon(DefenseInfo defenseInfo, Image[] renderer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseInfo` | `Global.DefenseInfo` |  |
| `renderer` | `UnityEngine.UI.Image[]` |  |

### SetUIAlpha(Image, float)

```csharp
public static void SetUIAlpha(Image image, float value)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `image` | `UnityEngine.UI.Image` |  |
| `value` | `System.Single` |  |

### SetUIAlpha(Text, float)

```csharp
public static void SetUIAlpha(Text text, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `UnityEngine.UI.Text` |  |
| `value` | `System.Single` |  |
