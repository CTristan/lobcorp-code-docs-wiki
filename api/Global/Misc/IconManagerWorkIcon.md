---
uid: Global.IconManager.WorkIcon
canonical_path: /api/Global/Misc/IconManagerWorkIcon
---

# Class IconManager.WorkIcon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IconManager.WorkIcon
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IconManager.WorkIcon

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkIcon()

```csharp
public WorkIcon()
```

## Fields

### currnetIndex

```csharp
public int currnetIndex
```

#### Field Value

**Type:** System.Int32

### defaultIndex

```csharp
public int defaultIndex
```

#### Field Value

**Type:** System.Int32

### icons

```csharp
[HideInInspector]
public List<IconManager.Icon> icons
```

#### Field Value

**Type:** System.Collections.Generic.List{IconManager.Icon}

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### sprites

```csharp
public List<Sprite> sprites
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

## Methods

### GetCurrent()

```csharp
public IconManager.Icon GetCurrent()
```

#### Returns

**Type:** Global.IconManager.Icon

### GetDefault()

```csharp
public IconManager.Icon GetDefault()
```

#### Returns

**Type:** Global.IconManager.Icon

### GetIcon(ManageWorkIconState)

```csharp
public IconManager.Icon GetIcon(ManageWorkIconState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.ManageWorkIconState` |  |

#### Returns

**Type:** Global.IconManager.Icon

### Init()

```csharp
public void Init()
```
