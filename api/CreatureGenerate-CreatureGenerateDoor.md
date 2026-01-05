# Class CreatureGenerateDoor

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateDoor : CreatureGenerateData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureGenerateData](/api/CreatureGenerate-CreatureGenerateData) → CreatureGenerateDoor

## Inherited Members
[split](/api/CreatureGenerate-CreatureGenerateData#split), [uniqueText](/api/CreatureGenerate-CreatureGenerateData#uniquetext), [commonAction](/api/CreatureGenerate-CreatureGenerateData#commonaction), [IsCommonAction(string, out GenerateCommonAction)](/api/CreatureGenerate-CreatureGenerateData#iscommonaction-string-out-generatecommonaction), [IsUniqueAction(string)](/api/CreatureGenerate-CreatureGenerateData#isuniqueaction-string), [ParseAction(ref string, out ActionData)](/api/CreatureGenerate-CreatureGenerateData#parseaction-ref-string-out-actiondata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureGenerateDoor()

```csharp
public CreatureGenerateDoor()
```

## Fields

### Creature

```csharp
public long Creature
```

#### Field Value

**Type:** System.Int64

### initialState

```csharp
public static bool[] initialState
```

#### Field Value

**Type:** System.Boolean[]

### MAX

```csharp
public const int MAX = 5
```

#### Field Value

**Type:** System.Int32

### prob

```csharp
public float[] prob
```

#### Field Value

**Type:** System.Single[]

### probState

```csharp
public bool[] probState
```

#### Field Value

**Type:** System.Boolean[]

### zeroAry

```csharp
public static readonly float[] zeroAry
```

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

### GetList(int)

```csharp
public ActivateStateList GetList(int i)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.Object[]` |  |

### Parse(string)

```csharp
public static CreatureGenerateDoor Parse(string parsed)
```

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
