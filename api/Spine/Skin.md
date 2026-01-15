---
uid: Spine.Skin
canonical_path: /api/Spine/Skin
---

# Class Skin

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Skin
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Skin

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [FindAttachmentsForSlot(Skin, string, SkeletonData, List<Attachment>)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_FindAttachmentsForSlot_Spine_Skin_System_String_Spine_SkeletonData_System_Collections_Generic_List_Spine_Attachment__)
- [FindNamesForSlot(Skin, string, SkeletonData, List<string>)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_FindNamesForSlot_Spine_Skin_System_String_Spine_SkeletonData_System_Collections_Generic_List_System_String__)
- [GetRepackedSkin(Skin, string, Material, out Material, out Texture2D, int, int, TextureFormat, bool)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetRepackedSkin_Spine_Skin_System_String_UnityEngine_Material_UnityEngine_Material__UnityEngine_Texture2D__System_Int32_System_Int32_UnityEngine_TextureFormat_System_Boolean_)
- [GetRepackedSkin(Skin, string, Shader, out Material, out Texture2D, int, int, TextureFormat, bool, Material, bool)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetRepackedSkin_Spine_Skin_System_String_UnityEngine_Shader_UnityEngine_Material__UnityEngine_Texture2D__System_Int32_System_Int32_UnityEngine_TextureFormat_System_Boolean_UnityEngine_Material_System_Boolean_)
- [Append(Skin, Skin)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_Append_Spine_Skin_Spine_Skin_)
- [Clear(Skin)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_Clear_Spine_Skin_)
- [CopyTo(Skin, Skin, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_CopyTo_Spine_Skin_Spine_Skin_System_Boolean_System_Boolean_System_Boolean_)
- [GetAttachment(Skin, string, string, Skeleton)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_GetAttachment_Spine_Skin_System_String_System_String_Spine_Skeleton_)
- [GetClone(Skin)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_GetClone_Spine_Skin_)
- [RemoveAttachment(Skin, int, string)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_RemoveAttachment_Spine_Skin_System_Int32_System_String_)
- [RemoveAttachment(Skin, string, string, Skeleton)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_RemoveAttachment_Spine_Skin_System_String_System_String_Spine_Skeleton_)
- [SetAttachment(Skin, int, string, Attachment)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_SetAttachment_Spine_Skin_System_Int32_System_String_Spine_Attachment_)
- [SetAttachment(Skin, string, string, Attachment, Skeleton)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_SetAttachment_Spine_Skin_System_String_System_String_Spine_Attachment_Spine_Skeleton_)

## Constructors

### Skin(string)

```csharp
public Skin(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### attachments

```csharp
private Dictionary<Skin.AttachmentKeyTuple, Attachment> attachments
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{Spine.Skin.AttachmentKeyTuple,Spine.Attachment}

### name

```csharp
internal string name
```

#### Field Value

**Type:** System.String

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

### AttachAll(Skeleton, Skin)

```csharp
internal void AttachAll(Skeleton skeleton, Skin oldSkin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `oldSkin` | `Spine.Skin` |  |

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
