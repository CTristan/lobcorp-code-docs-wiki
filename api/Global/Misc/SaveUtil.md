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
Provides several utilities for reading, writing, and deleting external files.

See also [GlobalGameManager](/api/Global/IOBserver/GlobalGameManager).




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
Deletes the file at the provided path if it exists, as well as the files at the paths `fileName`+".val.txt" and `fileName`+".\_temp".
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |

### ReadSerializableFile(string)

```csharp
public static Dictionary<string, object> ReadSerializableFile(string fileName)
```
Broadly, checks to see if there's a current version of the file and loads a Dictionary\<string,object> from it, or restores a backup if that fails.
###### More details:
Checks the path fileName+".val.txt" first; if it exists and the first byte is 64, it reads a Dictionary\<string,object> from fileName+".\_temp" and returns it.

Otherwise, it reads a Dictionary\<string, object> from the path fileName.

If this fails, it tries to read from fileName+".backup". If the backup exists, it moves the original fileName to another file with a random number appended, and replaces fileName with the backup.


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
Broadly, creates a backup of the current file, does some things with temporary files, and writes `dic` to `fileName`.
###### More details:
Serializes dic to fileName+".backup".

If there is a fileName+".val.txt" file with the value 64, tries to copy fileName+".\_temp" to overwrite fileName.

Then, makes a fileName+".\_temp" file and serializes dic to it, and makes a fileName+".val.txt" with a first byte of 64.

Then it copies the temp file to fileName and deletes both the .val.txt and .\_temp files.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
