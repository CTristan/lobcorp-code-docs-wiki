---
uid: Global.AssetLoader
canonical_path: /api/Global/Loader/AssetLoader
---

# Class AssetLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AssetLoader
```
Loads an XML from `ExternalData/xml` #verify .


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AssetLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AssetLoader()

```csharp
public AssetLoader()
```

## Methods

### LoadExternalXML(string)

```csharp
public static XmlDocument LoadExternalXML(string src)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** System.Xml.XmlDocument

### LoadExternalXmlSafe(string, string, bool, string)

```csharp
public static XmlDocument LoadExternalXmlSafe(string fileName, string language, bool languageFolderExist, string prefix = "Language/")
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |
| `language` | `System.String` |  |
| `languageFolderExist` | `System.Boolean` |  |
| `prefix` | `System.String` |  |

#### Returns

**Type:** System.Xml.XmlDocument
