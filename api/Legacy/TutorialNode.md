---
uid: Legacy.TutorialNode
canonical_path: /api/Legacy/TutorialNode
---

# Class TutorialNode

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialNode
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TutorialNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TutorialNode(int, string)

```csharp
public TutorialNode(int index, string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `src` | `System.String` |  |

## Fields

### defSrc

```csharp
private const string defSrc = "Sprites/Tutorial/Interaction/"
```

#### Field Value

**Type:** System.String

### imgSrc

```csharp
public string imgSrc
```

#### Field Value

**Type:** System.String

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

## Methods

### GetSprite()

```csharp
public Sprite GetSprite()
```

#### Returns

**Type:** UnityEngine.Sprite
