---
uid: Global.SefiraName
canonical_path: /api/Global/Misc/SefiraName
---

# Class SefiraName

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraName
```
Holds a list of the names of Sephirot.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraName

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraName()

```csharp
public SefiraName()
```

## Fields

### Binah

```csharp
public const string Binah = "Binah"
```
#INC


#### Field Value

**Type:** System.String

### Chesed

```csharp
public const string Chesed = "Chesed"
```
#INC


#### Field Value

**Type:** System.String

### Chokhmah

```csharp
public const string Chokhmah = "Chokhmah"
```
#INC


#### Field Value

**Type:** System.String

### cv_Chesed

```csharp
public const string cv_Chesed = "Chesed"
```
#INC


#### Field Value

**Type:** System.String

### cv_Geburah

```csharp
public const string cv_Geburah = "Geburah"
```
#INC


#### Field Value

**Type:** System.String

### cv_Hod

```csharp
public const string cv_Hod = "Hod"
```
#INC


#### Field Value

**Type:** System.String

### cv_Malkut

```csharp
public const string cv_Malkut = "Malkuth"
```
#INC


#### Field Value

**Type:** System.String

### cv_Netzach

```csharp
public const string cv_Netzach = "Netzach"
```
#INC


#### Field Value

**Type:** System.String

### cv_Tiphereth

```csharp
public const string cv_Tiphereth = "Tiphereths"
```
#INC


#### Field Value

**Type:** System.String

### cv_Yesod

```csharp
public const string cv_Yesod = "Yesod"
```
#INC


#### Field Value

**Type:** System.String

### Daat

```csharp
public const string Daat = "Daat"
```
#INC


#### Field Value

**Type:** System.String

### Dummy

```csharp
public const string Dummy = "Dummy"
```
#INC


#### Field Value

**Type:** System.String

### Geburah

```csharp
public const string Geburah = "Geburah"
```
#INC


#### Field Value

**Type:** System.String

### Hod

```csharp
public const string Hod = "Hod"
```
#INC


#### Field Value

**Type:** System.String

### Kether

```csharp
public const string Kether = "Kether"
```
#INC


#### Field Value

**Type:** System.String

### Malkut

```csharp
public const string Malkut = "Malkut"
```
#INC


#### Field Value

**Type:** System.String

### Netzach

```csharp
public const string Netzach = "Netzach"
```
#INC


#### Field Value

**Type:** System.String

### Tiphereth

```csharp
public const string Tiphereth = "Tiphereth"
```
#INC


#### Field Value

**Type:** System.String

### Tiphereth1

```csharp
public const string Tiphereth1 = "Tiphereth1"
```
#INC


#### Field Value

**Type:** System.String

### Tiphereth2

```csharp
public const string Tiphereth2 = "Tiphereth2"
```
#INC


#### Field Value

**Type:** System.String

### Yesod

```csharp
public const string Yesod = "Yesod"
```
#INC


#### Field Value

**Type:** System.String

## Methods

### GetLocalizingSefiraName(SefiraEnum)

```csharp
public static string GetLocalizingSefiraName(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.String

### GetSefiraByEnum(SefiraEnum)

```csharp
public static string GetSefiraByEnum(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.String

### GetSefiraCharacter(SefiraEnum)

```csharp
public static string GetSefiraCharacter(SefiraEnum sefira)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.String

### GetSefiraCharName(SefiraEnum)

```csharp
public static string GetSefiraCharName(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.String

### GetSefiraEnum(string)

```csharp
public static SefiraEnum GetSefiraEnum(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.SefiraEnum
