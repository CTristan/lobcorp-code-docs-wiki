---
uid: WorkerSpine.SpriteChangeData
canonical_path: /api/WorkerSpine/SpriteChangeData
---

# Class SpriteChangeData

**Namespace:** [WorkerSpine](/api/WorkerSpine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteChangeData
```
stores data to modify a sprite, maybe?
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteChangeData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpriteChangeData()

```csharp
public SpriteChangeData()
```

## Fields

### attachmentName

```csharp
[SpineAttachment(true, false, false, "", "", "", true)]
public string attachmentName
```

#### Field Value

**Type:** System.String

### calculateRate

```csharp
public bool calculateRate
```
#INC


#### Field Value

**Type:** System.Boolean

### color

```csharp
public Color color
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### isSetColor

```csharp
[Header("Color")]
public bool isSetColor
```

#### Field Value

**Type:** System.Boolean

### isSetOffset

```csharp
[Header("Offset")]
public bool isSetOffset
```

#### Field Value

**Type:** System.Boolean

### position

```csharp
public Vector2 position
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### rotation

```csharp
public float rotation
```
#INC


#### Field Value

**Type:** System.Single

### scale

```csharp
public Vector2 scale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### slot

```csharp
[SpineSlot("", "", false, true)]
public string slot
```

#### Field Value

**Type:** System.String

### spriteData

```csharp
[Header("Assigned")]
public Sprite spriteData
```

#### Field Value

**Type:** UnityEngine.Sprite
