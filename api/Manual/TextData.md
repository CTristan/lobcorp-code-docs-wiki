---
uid: Manual.TextData
canonical_path: /api/Manual/TextData
---

# Class TextData

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TextData
```
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TextData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TextData()

```csharp
public TextData()
```

## Fields

### fontSize

```csharp
public int fontSize
```
#INC


#### Field Value

**Type:** System.Int32

### rect

```csharp
public Rect rect
```
#INC


#### Field Value

**Type:** UnityEngine.Rect

### textId

```csharp
public string textId
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public TextType type
```
#INC


#### Field Value

**Type:** Manual.TextType

## Properties

### h

```csharp
public float h { get; set; }
```

#### Property Value

**Type:** System.Single

### w

```csharp
public float w { get; set; }
```

#### Property Value

**Type:** System.Single

### x

```csharp
public float x { get; set; }
```

#### Property Value

**Type:** System.Single

### y

```csharp
public float y { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### Parse(string, XmlNode)

```csharp
public static TextData Parse(string idPrefix, XmlNode node)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idPrefix` | `System.String` |  |
| `node` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Manual.TextData
