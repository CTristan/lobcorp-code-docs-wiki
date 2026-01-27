---
uid: WorkerSprite.WorkerAttachmentSprite
canonical_path: /api/WorkerSprite/WorkerAttachmentSprite
---

# Class WorkerAttachmentSprite

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerAttachmentSprite : WorkerEquipmentSprite
```

For loading I guess... all the resources for EGO gifts and their positioning?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerEquipmentSprite](/api/WorkerSprite/WorkerEquipmentSprite) → WorkerAttachmentSprite

## Inherited Members
[subRegion](/api/WorkerSprite/WorkerEquipmentSprite#subregion), [loadedData](/api/WorkerSprite/WorkerEquipmentSprite#loadeddata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerAttachmentSprite()

```csharp
public WorkerAttachmentSprite()
```

## Fields

### database

```csharp
public Dictionary<int, WorkerAttachmentSprite.AttachDatabase> database
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,WorkerSprite.WorkerAttachmentSprite.AttachDatabase}

### lib

```csharp
public Dictionary<int, List<SpriteResourceLoadData>> lib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{WorkerSprite.SpriteResourceLoadData}}

## Methods

### GetData(int)

```csharp
public List<SpriteResourceLoadData> GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{WorkerSprite.SpriteResourceLoadData}

### GetDb(int)

```csharp
public WorkerAttachmentSprite.AttachDatabase GetDb(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSprite.WorkerAttachmentSprite.AttachDatabase

### Init()

```csharp
public void Init()
```
#INC
#code-generated

