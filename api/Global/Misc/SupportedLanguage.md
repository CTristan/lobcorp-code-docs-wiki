---
uid: Global.SupportedLanguage
canonical_path: /api/Global/Misc/SupportedLanguage
---

# Class SupportedLanguage

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SupportedLanguage
```
Holds the supported languages and the names to display in the language drop-down.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SupportedLanguage

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### bg

```csharp
public const string bg = "bg"
```
#INC


#### Field Value

**Type:** System.String

### bg_Name

```csharp
public const string bg_Name = "български"
```
#INC


#### Field Value

**Type:** System.String

### cn

```csharp
public const string cn = "cn"
```
#INC


#### Field Value

**Type:** System.String

### cn_Name

```csharp
public const string cn_Name = "中文(简体)"
```
#INC


#### Field Value

**Type:** System.String

### cn_tr

```csharp
public const string cn_tr = "cn_tr"
```
#INC


#### Field Value

**Type:** System.String

### cn_tr_Name

```csharp
public const string cn_tr_Name = "中文(繁體)"
```
#INC


#### Field Value

**Type:** System.String

### en

```csharp
public const string en = "en"
```
#INC


#### Field Value

**Type:** System.String

### en_Name

```csharp
public const string en_Name = "English"
```
#INC


#### Field Value

**Type:** System.String

### es

```csharp
public const string es = "es"
```

#### Field Value

**Type:** System.String

### es_Name

```csharp
public const string es_Name = "Español Latinoamérica"
```

#### Field Value

**Type:** System.String

### jp

```csharp
public const string jp = "jp"
```
#INC


#### Field Value

**Type:** System.String

### jp_Name

```csharp
public const string jp_Name = "日本語"
```
#INC


#### Field Value

**Type:** System.String

### kr

```csharp
public const string kr = "kr"
```
#INC


#### Field Value

**Type:** System.String

### kr_Name

```csharp
public const string kr_Name = "한국어"
```
#INC


#### Field Value

**Type:** System.String

### ru

```csharp
public const string ru = "ru"
```
#INC


#### Field Value

**Type:** System.String

### ru_Name

```csharp
public const string ru_Name = "русский"
```
#INC


#### Field Value

**Type:** System.String

### vn

```csharp
public const string vn = "vn"
```
#INC


#### Field Value

**Type:** System.String

### vn_Name

```csharp
public const string vn_Name = "Tiếng Việt"
```
#INC


#### Field Value

**Type:** System.String

## Methods

### GetCurrentLanguageName(string)

```csharp
public static string GetCurrentLanguageName(string language)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `language` | `System.String` |  |

#### Returns

**Type:** System.String

### GetCurrentLanguageName(SystemLanguage)

```csharp
public static string GetCurrentLanguageName(SystemLanguage language)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `language` | `UnityEngine.SystemLanguage` |  |

#### Returns

**Type:** System.String

### GetSupprotedList()

```csharp
public static List<string> GetSupprotedList()
```
#INC
#code-generated


#### Returns

**Type:** System.Collections.Generic.List{System.String}
