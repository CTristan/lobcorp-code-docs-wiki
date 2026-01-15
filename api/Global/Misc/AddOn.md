---
uid: Global.Add_On
canonical_path: /api/Global/Misc/AddOn
---

# Class Add_On

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Add_On
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Add_On

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Add_On()

```csharp
public Add_On()
```

## Fields

### AssemList

```csharp
public List<Assembly> AssemList
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Reflection.Assembly}

### DirList

```csharp
public List<DirectoryInfo> DirList
```

#### Field Value

**Type:** System.Collections.Generic.List{System.IO.DirectoryInfo}

### DllList

```csharp
private string DllList
```

#### Field Value

**Type:** System.String

### EffectList

```csharp
public Dictionary<string, SkeletonDataAsset> EffectList
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,Spine.Unity.SkeletonDataAsset}

### Error_Report

```csharp
public static string Error_Report
```

#### Field Value

**Type:** System.String

### instance

```csharp
public static Add_On instance
```

#### Field Value

**Type:** Global.Add_On

### NoBoostList

```csharp
public static string[] NoBoostList
```

#### Field Value

**Type:** System.String[]

### ObjectList

```csharp
public Dictionary<string, object> ObjectList
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Portraits

```csharp
private static Dictionary<string, Sprite> Portraits
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Sprite}

### version

```csharp
public static string version
```

#### Field Value

**Type:** System.String

## Methods

### CheckNamedDir(DirectoryInfo, string)

```csharp
public static DirectoryInfo CheckNamedDir(DirectoryInfo dir, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `System.IO.DirectoryInfo` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** System.IO.DirectoryInfo

### CopyingSave(DirectoryInfo, DirectoryInfo)

```csharp
public static void CopyingSave(DirectoryInfo newback, DirectoryInfo save)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newback` | `System.IO.DirectoryInfo` |  |
| `save` | `System.IO.DirectoryInfo` |  |

### duplicateTexture(Texture2D)

```csharp
public static Texture2D duplicateTexture(Texture2D source)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `source` | `UnityEngine.Texture2D` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### GetBackDir()

```csharp
public static DirectoryInfo GetBackDir()
```

#### Returns

**Type:** System.IO.DirectoryInfo

### GetPortrait(string)

```csharp
public static Sprite GetPortrait(string portraitSrc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `portraitSrc` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetPortrait_OnlyTexture(string)

```csharp
public static Texture2D GetPortrait_OnlyTexture(string portraitSrc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `portraitSrc` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### init()

```csharp
public void init()
```

### Loading(string, string, object[])

```csharp
public static bool Loading(string Class, string Method, object[] values)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Class` | `System.String` |  |
| `Method` | `System.String` |  |
| `values` | `System.Object[]` |  |

#### Returns

**Type:** System.Boolean

### Loading_Return(string, string, object[])

```csharp
public static object[] Loading_Return(string Class, string Method, object[] values)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Class` | `System.String` |  |
| `Method` | `System.String` |  |
| `values` | `System.Object[]` |  |

#### Returns

**Type:** System.Object[]

### SaveBackUp()

```csharp
public static void SaveBackUp()
```

### UpdatingBackUps(DirectoryInfo, DirectoryInfo)

```csharp
public static void UpdatingBackUps(DirectoryInfo back, DirectoryInfo save)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `back` | `System.IO.DirectoryInfo` |  |
| `save` | `System.IO.DirectoryInfo` |  |
