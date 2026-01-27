---
uid: Global.UICommonTextConverter
canonical_path: /api/Global/Misc/UICommonTextConverter
---

# Class UICommonTextConverter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UICommonTextConverter
```

Provides methods for converting common text; only used to get the chance text for work based on the percent (i.e. 'very low', 'low', 'common', 'high', 'very high').

#verify 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UICommonTextConverter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UICommonTextConverter()

```csharp
public UICommonTextConverter()
```

## Methods

### GetPercentText(float)

```csharp
public static string GetPercentText(float rate)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

#### Returns

**Type:** System.String

### GetPercentText(int)

```csharp
public static string GetPercentText(int level)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.String
