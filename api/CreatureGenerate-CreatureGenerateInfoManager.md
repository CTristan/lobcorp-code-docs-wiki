# Class CreatureGenerateInfoManager

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureGenerateInfoManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureGenerateInfoManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureGenerateInfoManager()

```csharp
public CreatureGenerateInfoManager()
```

## Fields

### activateStateDic

```csharp
public Dictionary<RiskLevel, ActivateStateList> activateStateDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{RiskLevel,CreatureGenerate.ActivateStateList}

### CreatureList

```csharp
public Dictionary<RiskLevel, List<long>> CreatureList
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{RiskLevel,System.Collections.Generic.List{System.Int64}}

### dayGenInfoDic

```csharp
public Dictionary<int, CreatureGenerateModel> dayGenInfoDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,CreatureGenerate.CreatureGenerateModel}

### GenerateCommonActionList

```csharp
public List<string> GenerateCommonActionList
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### GenerateCommonActionString

```csharp
public static readonly string[] GenerateCommonActionString
```

#### Field Value

**Type:** System.String[]

### SelectData

```csharp
public Dictionary<int, CreatureSelectData> SelectData
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,CreatureGenerate.CreatureSelectData}

## Properties

### GenDay

```csharp
public int GenDay { get; }
```

#### Property Value

**Type:** System.Int32

### GenKit

```csharp
public bool GenKit { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Instance

```csharp
public static CreatureGenerateInfoManager Instance { get; }
```

#### Property Value

**Type:** CreatureGenerate.CreatureGenerateInfoManager

### IsInitiated

```csharp
public bool IsInitiated { get; }
```

#### Property Value

**Type:** System.Boolean

### IsloadedDayData

```csharp
public bool IsloadedDayData { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### CalculateDay()

```csharp
public void CalculateDay()
```

### CheckKitCreatureRemains()

```csharp
public bool CheckKitCreatureRemains()
```

#### Returns

**Type:** System.Boolean

### DebugCheck(int)

```csharp
public void DebugCheck(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

### GetCreature()

```csharp
public List<long> GetCreature()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### GetCreatureNew()

```csharp
public List<long> GetCreatureNew()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### GetCreatureState(RiskLevel, out ActivateStateList)

```csharp
public bool GetCreatureState(RiskLevel risk, out ActivateStateList list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `risk` | `Global.RiskLevel` |  |
| `list` | `CreatureGenerate.ActivateStateList` |  |

#### Returns

**Type:** System.Boolean

### HasUniqueAction(string[], out int)

```csharp
public bool HasUniqueAction(string[] split, out int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `split` | `System.String[]` |  |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public void Init()
```

### InitCreatureList()

```csharp
public void InitCreatureList()
```

### Log(string, bool)

```csharp
public static void Log(string text, bool isError = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `isError` | `System.Boolean` |  |

### OnDayChanged()

```csharp
public void OnDayChanged()
```

### OnUsed(long)

```csharp
public void OnUsed(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### Print()

```csharp
public void Print()
```

### RemoveAction(long)

```csharp
public void RemoveAction(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
