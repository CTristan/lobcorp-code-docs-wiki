# Class CreatureBase.SpecialSkillTipParameter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase.SpecialSkillTipParameter
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase.SpecialSkillTipParameter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SpecialSkillTipParameter(CreatureBase, CreatureSpecialSkillDesc)

```csharp
public SpecialSkillTipParameter(CreatureBase script, CreatureSpecialSkillDesc desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CreatureBase` |  |
| `desc` | `Global.CreatureSpecialSkillDesc` |  |

### SpecialSkillTipParameter(CreatureBase, string, int)

```csharp
public SpecialSkillTipParameter(CreatureBase script, string key, int maxCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CreatureBase` |  |
| `key` | `System.String` |  |
| `maxCount` | `System.Int32` |  |

### SpecialSkillTipParameter(CreatureBase, string, int, bool)

```csharp
public SpecialSkillTipParameter(CreatureBase script, string key, int maxCount, bool isRelease)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CreatureBase` |  |
| `key` | `System.String` |  |
| `maxCount` | `System.Int32` |  |
| `isRelease` | `System.Boolean` |  |

## Fields

### openLevel

```csharp
public int openLevel
```

#### Field Value

**Type:** System.Int32

## Methods

### AddCount()

```csharp
public void AddCount()
```

### Clear()

```csharp
public void Clear()
```

### IsActivated()

```csharp
public bool IsActivated()
```

#### Returns

**Type:** System.Boolean

### IsRevealed()

```csharp
public bool IsRevealed()
```

#### Returns

**Type:** System.Boolean

### OnActivate()

```csharp
public void OnActivate()
```

### OnObserveLevelUpdated(int)

```csharp
public void OnObserveLevelUpdated(int currentObserveLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentObserveLevel` | `System.Int32` |  |

### ParamSave(params object[])

```csharp
public void ParamSave(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

### SetCount(int)

```csharp
public void SetCount(int cnt)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cnt` | `System.Int32` |  |
