# Class CreatureObserveBonusList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureObserveBonusList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureObserveBonusList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureObserveBonusList()

```csharp
public CreatureObserveBonusList()
```

## Fields

### bonusList

```csharp
public List<CreatureObserveBonusData> bonusList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureObserveBonusData}

## Methods

### GetProbBonus(int)

```csharp
public int GetProbBonus(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetSpeedBonus(int)

```csharp
public int GetSpeedBonus(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### Init(List<CreatureObserveBonusData>)

```csharp
public void Init(List<CreatureObserveBonusData> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{CreatureObserveBonusData}` |  |
