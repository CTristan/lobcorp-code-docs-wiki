---
uid: Global.SaveUtil
canonical_path: /api/Global/Misc/SaveUtil
---

# Class SaveUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SaveUtil
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SaveUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SaveUtil()

```csharp
public SaveUtil()
```

## Methods

### DeleteSerializableFile(string)

```csharp
public static void DeleteSerializableFile(string fileName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |

### ReadSerializableFile(string)

```csharp
public static Dictionary<string, object> ReadSerializableFile(string fileName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### WriteSerializableFile(string, Dictionary<string, object>)

```csharp
public static void WriteSerializableFile(string fileName, Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
