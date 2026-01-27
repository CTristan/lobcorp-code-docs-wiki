---
uid: CreatureGenerate.CreatureGenerateDoor
canonical_path: /api/CreatureGenerate/CreatureGenerateDoor
---

# Class CreatureGenerateDoor

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateDoor : CreatureGenerateData
```

Code for choosing the creature behind each door during abnormality extraction.

Randomly chooses the grade based on the CreatureGenInfo resource, then randomly chooses an abnormality from the list of viable abnormalities of that grade.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate/CreatureGenerateData) → CreatureGenerateDoor

## Inherited Members
[split](/api/CreatureGenerate/CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate/CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate/CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate/CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate/CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate/CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureGenerateDoor()

```csharp
public CreatureGenerateDoor()
```
#INC


## Fields

### Creature

```csharp
public long Creature
```
#INC


#### Field Value

**Type:** System.Int64

### initialState

```csharp
public static bool[] initialState
```
#INC


#### Field Value

**Type:** System.Boolean[]

### MAX

```csharp
public const int MAX = 5
```
#INC


#### Field Value

**Type:** System.Int32

### prob

```csharp
public float[] prob
```
#INC


#### Field Value

**Type:** System.Single[]

### probState

```csharp
public bool[] probState
```
#INC


#### Field Value

**Type:** System.Boolean[]

### zeroAry

```csharp
public static readonly float[] zeroAry
```
#INC


#### Field Value

**Type:** System.Single[]

## Properties

### TotalProb

```csharp
public float TotalProb { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### CheckProb()

```csharp
public void CheckProb()
```
#INC


### GetList(int)

```csharp
public ActivateStateList GetList(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

#### Returns

**Type:** CreatureGenerate.ActivateStateList

### OnlyAction(params object[])

```csharp
public override void OnlyAction(params object[] ids)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### Parse(string)

```csharp
public static CreatureGenerateDoor Parse(string parsed)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parsed` | `System.String` |  |

#### Returns

**Type:** CreatureGenerate.CreatureGenerateDoor

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

