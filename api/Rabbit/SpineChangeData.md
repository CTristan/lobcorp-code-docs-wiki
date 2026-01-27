---
uid: Rabbit.SpineChangeData
canonical_path: /api/Rabbit/SpineChangeData
---

# Class SpineChangeData

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpineChangeData
```
information for updating a positioning and color with Spine


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpineChangeData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpineChangeData()

```csharp
public SpineChangeData()
```

## Fields

### attachmentName

```csharp
[SpineAttachment(true, false, false, "", "", "", true)]
public string attachmentName
```

#### Field Value

**Type:** System.String

### slot

```csharp
[SpineSlot("", "", false, true)]
public string slot
```

#### Field Value

**Type:** System.String

### sprite

```csharp
[Header("Assigned")]
public Sprite sprite
```

#### Field Value

**Type:** UnityEngine.Sprite
