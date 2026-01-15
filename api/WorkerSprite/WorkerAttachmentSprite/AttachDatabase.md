---
uid: WorkerSprite.WorkerAttachmentSprite.AttachDatabase
canonical_path: /api/WorkerSprite/WorkerAttachmentSprite/AttachDatabase
---

# Class WorkerAttachmentSprite.AttachDatabase

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerAttachmentSprite.AttachDatabase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerAttachmentSprite.AttachDatabase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AttachDatabase()

```csharp
public AttachDatabase()
```

## Fields

### data

```csharp
private Dictionary<string, Sprite> data
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Sprite}

## Methods

### Add(SpriteResourceLoadData)

```csharp
public void Add(SpriteResourceLoadData s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `WorkerSprite.SpriteResourceLoadData` |  |

### GetSprite(string, out Sprite)

```csharp
public bool GetSprite(string name, out Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |

#### Returns

**Type:** System.Boolean
