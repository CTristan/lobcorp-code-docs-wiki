# Class Skin

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Skin
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Skin

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Skin(string)

```csharp
public Skin(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### Attachments

```csharp
public Dictionary<Skin.AttachmentKeyTuple, Attachment> Attachments { get; }
```

#### Property Value

**Type:** System.Collections.Generic.Dictionary{Spine.Skin.AttachmentKeyTuple,Spine.Attachment}

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

## Methods

### AddAttachment(int, string, Attachment)

```csharp
public void AddAttachment(int slotIndex, string name, Attachment attachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `name` | `System.String` |  |
| `attachment` | `Spine.Attachment` |  |

### FindAttachmentsForSlot(int, List<Attachment>)

```csharp
public void FindAttachmentsForSlot(int slotIndex, List<Attachment> attachments)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `attachments` | `System.Collections.Generic.List{Spine.Attachment}` |  |

### FindNamesForSlot(int, List<string>)

```csharp
public void FindNamesForSlot(int slotIndex, List<string> names)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `names` | `System.Collections.Generic.List{System.String}` |  |

### GetAttachment(int, string)

```csharp
public Attachment GetAttachment(int slotIndex, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.Attachment

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
