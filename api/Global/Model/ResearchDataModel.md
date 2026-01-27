---
uid: Global.ResearchDataModel
canonical_path: /api/Global/Model/ResearchDataModel
---

# Class ResearchDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchDataModel
```
Loads and holds information about researches, including completed researches.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchDataModel()

```csharp
public ResearchDataModel()
```

## Fields

### _instance

```csharp
private static ResearchDataModel _instance
```
#INC


#### Field Value

**Type:** Global.ResearchDataModel

### agentStatBonus

```csharp
private ResearchUnitStatUpgrade agentStatBonus
```
#INC


#### Field Value

**Type:** Global.ResearchUnitStatUpgrade

### bulletAbility

```csharp
private Dictionary<GlobalBulletType, bool> bulletAbility
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{GlobalBullet.GlobalBulletType,System.Boolean}

### promotionEasilyUpgrade

```csharp
private ResearchPromotionEasily promotionEasilyUpgrade
```
#INC


#### Field Value

**Type:** Global.ResearchPromotionEasily

### researchDatas

```csharp
private Dictionary<int, ResearchItemModel> researchDatas
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,ResearchItemModel}

### sephiraabilityLevel

```csharp
private Dictionary<string, int> sephiraabilityLevel
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### specialAbility

```csharp
private Dictionary<string, bool> specialAbility
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Boolean}

### weaponLevelResearchInfo

```csharp
private Dictionary<int, int> weaponLevelResearchInfo
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Int32}

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
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.ResearchUnitStatUpgrade

### GetLevel(int, int)

```csharp
public static int GetLevel(int id, int value)
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Single

### GetRemainResearchListBySefira(string)

```csharp
public List<ResearchItemModel> GetRemainResearchListBySefira(string sefira)
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSephiraAbility(Sefira)

```csharp
public int GetSephiraAbility(Sefira sephira)
```
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.List{ResearchItemModel}

### GetUpgradedResearchListBySefira(SefiraEnum)

```csharp
public List<ResearchItemModel> GetUpgradedResearchListBySefira(SefiraEnum sefira)
```
#INC


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
#INC
#code-generated


### IsUpgradedAbility(string)

```csharp
public bool IsUpgradedAbility(string name)
```
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### NextLevel(int)

```csharp
public static int NextLevel(int id)
```
#INC


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
#INC


### UpgradeAllResearch()

```csharp
public void UpgradeAllResearch()
```
#INC


### UpgradeResearch(int, bool)

```csharp
public bool UpgradeResearch(int id, bool forcely = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `forcely` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean
