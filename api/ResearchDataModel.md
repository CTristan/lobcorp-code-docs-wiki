# Class ResearchDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchDataModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ResearchDataModel()

```csharp
public ResearchDataModel()
```

## Properties

### instance

```csharp
public static ResearchDataModel instance { get; }
```

#### Property Value

**Type:** Global.ResearchDataModel

## Methods

### ConvertResearchType(ResearchType)

```csharp
public static string ConvertResearchType(ResearchType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.ResearchType` |  |

#### Returns

**Type:** System.String

### ConvertResearchType(string)

```csharp
public static ResearchType ConvertResearchType(string type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.String` |  |

#### Returns

**Type:** Global.ResearchType

### CurrentLevel(int)

```csharp
public static int CurrentLevel(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetAgentStatBonus()

```csharp
public ResearchUnitStatUpgrade GetAgentStatBonus()
```

#### Returns

**Type:** Global.ResearchUnitStatUpgrade

### GetLevel(int, int)

```csharp
public static int GetLevel(int id, int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `value` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetModel(int)

```csharp
public ResearchItemModel GetModel(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ResearchItemModel

### GetModelBySefira(string)

```csharp
public List<ResearchItemModel> GetModelBySefira(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemModel}

### GetPromotionEasilyValue()

```csharp
public float GetPromotionEasilyValue()
```

#### Returns

**Type:** System.Single

### GetRemainResearchListBySefira(string)

```csharp
public List<ResearchItemModel> GetRemainResearchListBySefira(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemModel}

### GetResearchCost(int)

```csharp
public int GetResearchCost(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetResearchItem(int)

```csharp
public ResearchItemModel GetResearchItem(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ResearchItemModel

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSephiraAbility(Sefira)

```csharp
public int GetSephiraAbility(Sefira sephira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sephira` | `Global.Sefira` |  |

#### Returns

**Type:** System.Int32

### GetUpgradedResearchList()

```csharp
public List<ResearchItemModel> GetUpgradedResearchList()
```

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemModel}

### GetUpgradedResearchListBySefira(SefiraEnum)

```csharp
public List<ResearchItemModel> GetUpgradedResearchListBySefira(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemModel}

### Init()

```csharp
public void Init()
```

### IsUpgradedAbility(string)

```csharp
public bool IsUpgradedAbility(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### IsUpgradedBullet(GlobalBulletType)

```csharp
public bool IsUpgradedBullet(GlobalBulletType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `GlobalBullet.GlobalBulletType` |  |

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### NextLevel(int)

```csharp
public static int NextLevel(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### UpdateResearch()

```csharp
public void UpdateResearch()
```

### UpgradeAllResearch()

```csharp
public void UpgradeAllResearch()
```

### UpgradeResearch(int, bool)

```csharp
public bool UpgradeResearch(int id, bool forcely = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `forcely` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean
