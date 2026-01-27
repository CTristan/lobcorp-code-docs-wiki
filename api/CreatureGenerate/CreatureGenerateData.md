---
uid: CreatureGenerate.CreatureGenerateData
canonical_path: /api/CreatureGenerate/CreatureGenerateData
---

# Class CreatureGenerateData

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateData
```
Parent class with some helper functions for reading in day info (from CreatureGenInfo, in resources).

See [CreatureGenerateModel](/api/CreatureGenerate/CreatureGenerateModel)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureGenerateData

## Derived
[CreatureGenerateDoor](/api/CreatureGenerate/CreatureGenerateDoor), [CreatureGenerateModel](/api/CreatureGenerate/CreatureGenerateModel)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureGenerateData()

```csharp
public CreatureGenerateData()
```

## Fields

### commonAction

```csharp
public CreatureGenerateData.ActionData commonAction
```

#### Field Value

**Type:** CreatureGenerate.CreatureGenerateData.ActionData

### split

```csharp
public static char[] split
```
#INC


#### Field Value

**Type:** System.Char[]

### uniqueText

```csharp
public static string uniqueText
```
#INC


#### Field Value

**Type:** System.String

## Methods

### IsCommonAction(string, out GenerateCommonAction)

```csharp
public static bool IsCommonAction(string parsed, out GenerateCommonAction action)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` |  |
| `action` | `CreatureGenerate.GenerateCommonAction` |  |

#### Returns

**Type:** System.Boolean

### IsUniqueAction(string)

```csharp
public static bool IsUniqueAction(string parsed)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### OnlyAction(params object[])

```csharp
public virtual void OnlyAction(params object[] ids)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### ParseAction(ref string, out ActionData)

```csharp
public bool ParseAction(ref string origin, out CreatureGenerateData.ActionData output)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `output` | `CreatureGenerate.CreatureGenerateData.ActionData` |  |

#### Returns

**Type:** System.Boolean

### RemoveAction(params object[])

```csharp
public virtual void RemoveAction(params object[] ids)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |
