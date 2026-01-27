---
uid: Manual.LabelData
canonical_path: /api/Manual/LabelData
---

# Class LabelData

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LabelData
```
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → LabelData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LabelData()

```csharp
public LabelData()
```

## Fields

### globalFontSize

```csharp
public int globalFontSize
```
#INC


#### Field Value

**Type:** System.Int32

### globalHeight

```csharp
public float globalHeight
```
#INC


#### Field Value

**Type:** System.Single

### list

```csharp
public List<LabelData.LabelUnit> list
```

#### Field Value

**Type:** System.Collections.Generic.List{Manual.LabelData.LabelUnit}

### prefix

```csharp
public LabelData.PrefixType prefix
```

#### Field Value

**Type:** Manual.LabelData.PrefixType

### rect

```csharp
public Rect rect
```
#INC


#### Field Value

**Type:** UnityEngine.Rect

### space

```csharp
public float space
```
#INC


#### Field Value

**Type:** System.Single

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
public static LabelData Parse(string idPrefix, XmlNode node)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idPrefix` | `System.String` |  |
| `node` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Manual.LabelData
