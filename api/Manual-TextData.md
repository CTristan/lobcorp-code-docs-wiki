# Class TextData

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TextData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TextData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Int32

### rect

```csharp
public Rect rect
```

#### Field Value

**Type:** UnityEngine.Rect

### textId

```csharp
public string textId
```

#### Field Value

**Type:** System.String

### type

```csharp
public TextType type
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idPrefix` | `System.String` |  |
| `node` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Manual.TextData
