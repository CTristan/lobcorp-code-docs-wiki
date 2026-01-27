---
uid: Global.LocalizeTextDataLoader
canonical_path: /api/Global/Loader/LocalizeTextDataLoader
---

# Class LocalizeTextDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LocalizeTextDataLoader
```
Loads language change information, and hence most text in the game.

See also [LocalizeTextDataModel](/api/Global/Model/LocalizeTextDataModel)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → LocalizeTextDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LocalizeTextDataLoader(string)

```csharp
public LocalizeTextDataLoader(string lang)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lang` | `System.String` |  |

## Fields

### _lang

```csharp
public string _lang
```

#### Field Value

**Type:** System.String

## Methods

### CheckDirText(DirectoryInfo, Dictionary<string, string>)

```csharp
public void CheckDirText(DirectoryInfo dir, Dictionary<string, string> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `System.IO.DirectoryInfo` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |

### GetLocalizeList()

```csharp
private string[] GetLocalizeList()
```
#INC


#### Returns

**Type:** System.String[]

### LoadLocalizeTextData()

```csharp
public void LoadLocalizeTextData()
```
#INC


### LoadText(XmlDocument)

```csharp
public Dictionary<string, string> LoadText(XmlDocument document)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `document` | `System.Xml.XmlDocument` |  |

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}
