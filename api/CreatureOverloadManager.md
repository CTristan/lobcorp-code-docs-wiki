# Class CreatureOverloadManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureOverloadManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureOverloadManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureOverloadManager()

```csharp
public CreatureOverloadManager()
```

## Properties

### instance

```csharp
public static CreatureOverloadManager instance { get; }
```

#### Property Value

**Type:** Global.CreatureOverloadManager

### qliphothOverloadMax

```csharp
public int qliphothOverloadMax { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ActivateOverload(int, OverloadType, float, bool, bool, bool, params long[])

```csharp
public List<CreatureModel> ActivateOverload(int overloadCount, OverloadType type, float overloadTime, bool ignoreWork = false, bool ignoreBossReward = false, bool ignoreDefaultOverload = false, params long[] ignoredCreatureMetaId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overloadCount` | `System.Int32` |  |
| `type` | `Global.OverloadType` |  |
| `overloadTime` | `System.Single` |  |
| `ignoreWork` | `System.Boolean` |  |
| `ignoreBossReward` | `System.Boolean` |  |
| `ignoreDefaultOverload` | `System.Boolean` |  |
| `ignoredCreatureMetaId` | `System.Int64[]` |  |

#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### AddOverloadGague()

```csharp
public void AddOverloadGague()
```

### GetQliphothOverloadLevel()

```csharp
public int GetQliphothOverloadLevel()
```

#### Returns

**Type:** System.Int32

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```
