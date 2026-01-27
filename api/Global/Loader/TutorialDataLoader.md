---
uid: Global.TutorialDataLoader
canonical_path: /api/Global/Loader/TutorialDataLoader
---

# Class TutorialDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialDataLoader
```
Loads tutorial data from XML for the current language, or english by default.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TutorialDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TutorialDataLoader()

```csharp
public TutorialDataLoader()
```

## Fields

### _instance

```csharp
private static TutorialDataLoader _instance
```
#INC


#### Field Value

**Type:** Global.TutorialDataLoader

### currentLn

```csharp
private string currentLn
```
#INC


#### Field Value

**Type:** System.String

### documentSrc

```csharp
private string documentSrc
```
#INC


#### Field Value

**Type:** System.String

### tutorialData

```csharp
private TutorialData tutorialData
```
#INC


#### Field Value

**Type:** Global.TutorialData

## Properties

### instance

```csharp
public static TutorialDataLoader instance { get; }
```

#### Property Value

**Type:** Global.TutorialDataLoader

### TutorialData

```csharp
public TutorialData TutorialData { get; }
```

#### Property Value

**Type:** Global.TutorialData

## Methods

### Load()

```csharp
public void Load()
```
#INC


### LoadDoc(string)

```csharp
private XmlDocument LoadDoc(string currentLn)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentLn` | `System.String` |  |

#### Returns

**Type:** System.Xml.XmlDocument
