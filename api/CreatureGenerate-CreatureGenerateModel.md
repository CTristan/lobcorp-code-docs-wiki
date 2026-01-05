# Class CreatureGenerateModel

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateModel : CreatureGenerateData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate-CreatureGenerateData) → CreatureGenerateModel

## Inherited Members
[split](/api/CreatureGenerate-CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate-CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate-CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate-CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate-CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate-CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Collections.Generic.List{System.Int64}

### day

```csharp
public int day
```

#### Field Value

**Type:** System.Int32

### door1

```csharp
public CreatureGenerateDoor door1
```

#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### door2

```csharp
public CreatureGenerateDoor door2
```

#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### door3

```csharp
public CreatureGenerateDoor door3
```

#### Field Value

**Type:** CreatureGenerate.CreatureGenerateDoor

### stop

```csharp
public bool stop
```

#### Field Value

**Type:** System.Boolean

## Methods

### OnlyAction(params object[])

```csharp
public override void OnlyAction(params object[] ids)
```

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

### RemoveAction(params object[])

```csharp
public override void RemoveAction(params object[] ids)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### SetCreature()

```csharp
public void SetCreature()
```
