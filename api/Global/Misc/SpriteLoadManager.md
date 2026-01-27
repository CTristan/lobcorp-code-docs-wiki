---
uid: Global.SpriteLoadManager
canonical_path: /api/Global/Misc/SpriteLoadManager
---

# Class SpriteLoadManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteLoadManager
```
Loads and stores locations for sprites.

#INC  #verify 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteLoadManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpriteLoadManager()

```csharp
public SpriteLoadManager()
```

## Fields

### _instance

```csharp
private static SpriteLoadManager _instance
```
#INC


#### Field Value

**Type:** Global.SpriteLoadManager

### _isLoaded

```csharp
private bool _isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### commonLib

```csharp
public Dictionary<string, string> commonLib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### commonSetDic

```csharp
public Dictionary<string, SpriteSetLoadedScript.SRC> commonSetDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SpriteSetLoadedScript.SRC}

### sefiraLib

```csharp
public Dictionary<string, string> sefiraLib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### sefiraSetDic

```csharp
public Dictionary<string, SpriteSetLoadedScript.SRC> sefiraSetDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SpriteSetLoadedScript.SRC}

## Properties

### instance

```csharp
public static SpriteLoadManager instance { get; }
```

#### Property Value

**Type:** Global.SpriteLoadManager

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetCommonSetSRC(string)

```csharp
public SpriteSetLoadedScript.SRC GetCommonSetSRC(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.SpriteSetLoadedScript.SRC

### GetCommonSrc(string)

```csharp
public string GetCommonSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetSefiraSetSRC(string)

```csharp
public SpriteSetLoadedScript.SRC GetSefiraSetSRC(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.SpriteSetLoadedScript.SRC

### GetSefiraSrc(string)

```csharp
public string GetSefiraSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### Init(Dictionary<string, string>, Dictionary<string, string>, Dictionary<string, SRC>, Dictionary<string, SRC>)

```csharp
public void Init(Dictionary<string, string> common, Dictionary<string, string> sefira, Dictionary<string, SpriteSetLoadedScript.SRC> commonSetDic, Dictionary<string, SpriteSetLoadedScript.SRC> sefiraSetDic)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `common` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `sefira` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
| `commonSetDic` | `System.Collections.Generic.Dictionary{System.String,SpriteSetLoadedScript.SRC}` |  |
| `sefiraSetDic` | `System.Collections.Generic.Dictionary{System.String,SpriteSetLoadedScript.SRC}` |  |
