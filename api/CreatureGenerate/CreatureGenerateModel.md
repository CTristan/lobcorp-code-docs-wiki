---
uid: CreatureGenerate.CreatureGenerateModel
canonical_path: /api/CreatureGenerate/CreatureGenerateModel
---

# Class CreatureGenerateModel

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateModel : CreatureGenerateData
```

Holds three doors, which can be set as creatures. Also, has the implementation for the Remove and Only actions. 'Only' restricts to the listed abnormalities, and 'Remove' removes banned abnormalities for that day.

See [CreatureGenerateInfoManager](/api/CreatureGenerate/CreatureGenerateInfoManager)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate/CreatureGenerateData) → CreatureGenerateModel

## Inherited Members
[split](/api/CreatureGenerate/CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate/CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate/CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate/CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate/CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate/CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureGenerateModel()

```csharp
public CreatureGenerateModel()
```

## Fields

### creature

```csharp
public List<long> creature
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int64}

### day

```csharp
public int day
```
#INC


#### Field Value

**Type:** System.Int32

### door1

```csharp
public CreatureGenerateDoor door1
```
#INC


#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### door2

```csharp
public CreatureGenerateDoor door2
```
#INC


#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### door3

```csharp
public CreatureGenerateDoor door3
```
#INC


#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### stop

```csharp
public bool stop
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### OnlyAction(params object[])

```csharp
public override void OnlyAction(params object[] ids)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### ParseActionNode(string)

```csharp
public CreatureGenerateData.ActionData ParseActionNode(string nodeText)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeText` | `System.String` |  |

#### Returns

**Type:** CreatureGenerate.CreatureGenerateData.ActionData

### Print()

```csharp
public void Print()
```
#INC


### RemoveAction(params object[])

```csharp
public override void RemoveAction(params object[] ids)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### SetCreature()

```csharp
public void SetCreature()
```
#INC

