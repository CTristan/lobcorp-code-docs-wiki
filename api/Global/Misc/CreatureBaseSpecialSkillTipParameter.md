---
uid: Global.CreatureBase.SpecialSkillTipParameter
canonical_path: /api/Global/Misc/CreatureBaseSpecialSkillTipParameter
---

# Class CreatureBase.SpecialSkillTipParameter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase.SpecialSkillTipParameter
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase.SpecialSkillTipParameter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### desc

```csharp
private CreatureSpecialSkillDesc desc
```

#### Field Value

**Type:** Global.CreatureSpecialSkillDesc

### isActivated

```csharp
private bool isActivated
```

#### Field Value

**Type:** System.Boolean

### isRelease

```csharp
private bool isRelease
```

#### Field Value

**Type:** System.Boolean

### key

```csharp
private string key
```

#### Field Value

**Type:** System.String

### maxCount

```csharp
private int maxCount
```

#### Field Value

**Type:** System.Int32

### openLevel

```csharp
public int openLevel
```

#### Field Value

**Type:** System.Int32

### paramSave

```csharp
private List<object> paramSave
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Object}

### script

```csharp
private CreatureBase script
```

#### Field Value

**Type:** Global.CreatureBase

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
