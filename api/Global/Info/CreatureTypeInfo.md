---
uid: Global.CreatureTypeInfo
canonical_path: /api/Global/Info/CreatureTypeInfo
---

# Class CreatureTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureTypeInfo
```
Holds a ton of information about an abnormality.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureTypeInfo

## Derived
[ChildCreatureTypeInfo](/api/Global/Creature/ChildCreatureTypeInfo)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureTypeInfo()

```csharp
public CreatureTypeInfo()
```

## Fields

### _isChildAndHasData

```csharp
public bool _isChildAndHasData
```
#INC


#### Field Value

**Type:** System.Boolean

### _tempPortrait

```csharp
public string _tempPortrait
```
#INC


#### Field Value

**Type:** System.String

### activateSpecialSkill

```csharp
private bool activateSpecialSkill
```
#INC


#### Field Value

**Type:** System.Boolean

### animSrc

```csharp
public string animSrc
```
#INC


#### Field Value

**Type:** System.String

### childTypeInfo

```csharp
public ChildCreatureTypeInfo childTypeInfo
```
#INC


#### Field Value

**Type:** Global.ChildCreatureTypeInfo

### collectionUsedAgentName

```csharp
public Dictionary<int, AgentName> collectionUsedAgentName
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,AgentName}

### creatureKitType

```csharp
public CreatureKitType creatureKitType
```
#INC


#### Field Value

**Type:** Global.CreatureKitType

### creatureSpecialDamageTable

```csharp
public CreatureSpecialDamageTable creatureSpecialDamageTable
```
#INC


#### Field Value

**Type:** Global.CreatureSpecialDamageTable

### creatureStaticData

```csharp
public CreatureStaticData creatureStaticData
```
#INC


#### Field Value

**Type:** Global.CreatureStaticData

### creatureWorkType

```csharp
public CreatureWorkType creatureWorkType
```
#INC


#### Field Value

**Type:** Global.CreatureWorkType

### cubeSpeed

```csharp
public float cubeSpeed
```
#INC


#### Field Value

**Type:** System.Single

### dataTable

```csharp
public CreatureTypeInfo.CreatureDataTable dataTable
```

#### Field Value

**Type:** Global.CreatureTypeInfo.CreatureDataTable

### defenseTable

```csharp
public CreatureDefenseTable defenseTable
```
#INC


#### Field Value

**Type:** Global.CreatureDefenseTable

### desc

```csharp
public List<string> desc
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### edgeInfo

```csharp
public XmlNodeList edgeInfo
```
#INC


#### Field Value

**Type:** System.Xml.XmlNodeList

### equipMakeInfos

```csharp
public List<CreatureEquipmentMakeInfo> equipMakeInfos
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureEquipmentMakeInfo}

### feelingStateCubeBounds

```csharp
public FeelingStateCubeBounds feelingStateCubeBounds
```
#INC


#### Field Value

**Type:** Global.FeelingStateCubeBounds

### id

```csharp
public long id
```
#INC


#### Field Value

**Type:** System.Int64

### intData

```csharp
public static string[] intData
```
#INC


#### Field Value

**Type:** System.String[]

### isEscapeAble

```csharp
public bool isEscapeAble
```
#INC


#### Field Value

**Type:** System.Boolean

### kitIconSrc

```csharp
public string kitIconSrc
```
#INC


#### Field Value

**Type:** System.String

### maxHp

```csharp
public int maxHp
```
#INC


#### Field Value

**Type:** System.Int32

### MaxObserveLevel

```csharp
public int MaxObserveLevel
```
#INC


#### Field Value

**Type:** System.Int32

### maxObserveModule

```csharp
public CreatureMaxObserve maxObserveModule
```
#INC


#### Field Value

**Type:** Global.CreatureMaxObserve

### maxProbReductionCounter

```csharp
public int maxProbReductionCounter
```
#INC


#### Field Value

**Type:** System.Int32

### maxWorkCount

```csharp
public int maxWorkCount
```
#INC


#### Field Value

**Type:** System.Int32

### narrationTable

```csharp
public Dictionary<string, string> narrationTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### noDataString

```csharp
public const string noDataString = "Unknown"
```
#INC


#### Field Value

**Type:** System.String

### nodeInfo

```csharp
public XmlNodeList nodeInfo
```
#INC


#### Field Value

**Type:** System.Xml.XmlNodeList

### observe

```csharp
public string observe
```
#INC


#### Field Value

**Type:** System.String

### observeBonus

```csharp
public CreatureObserveBonusList observeBonus
```
#INC


#### Field Value

**Type:** Global.CreatureObserveBonusList

### observeData

```csharp
public List<ObserveInfoData> observeData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ObserveInfoData}

### observeList

```csharp
public string[] observeList
```
#INC


#### Field Value

**Type:** System.String[]

### observeRecord

```csharp
public List<string> observeRecord
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### observeTable

```csharp
public CreatureTypeInfo.ObserveTable observeTable
```

#### Field Value

**Type:** Global.CreatureTypeInfo.ObserveTable

### openText

```csharp
public string openText
```
#INC


#### Field Value

**Type:** System.String

### probReduction

```csharp
public float probReduction
```
#INC


#### Field Value

**Type:** System.Single

### qliphothMax

```csharp
public int qliphothMax
```
#INC


#### Field Value

**Type:** System.Int32

### roomReturnSrc

```csharp
public string roomReturnSrc
```
#INC


#### Field Value

**Type:** System.String

### script

```csharp
public string script
```
#INC


#### Field Value

**Type:** System.String

### skillTriggerCheck

```csharp
public SkillTriggerCheck skillTriggerCheck
```
#INC


#### Field Value

**Type:** Global.SkillTriggerCheck

### soundTable

```csharp
public Dictionary<string, string> soundTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### specialSkillTable

```csharp
public CreatureSpecialSkillTipTable specialSkillTable
```
#INC


#### Field Value

**Type:** Global.CreatureSpecialSkillTipTable

### speed

```csharp
public float speed
```
#INC


#### Field Value

**Type:** System.Single

### stringData

```csharp
public static string[] stringData
```
#INC


#### Field Value

**Type:** System.String[]

### tempPortrait

```csharp
public Sprite tempPortrait
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### typoTable

```csharp
public Dictionary<string, string> typoTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### workAnim

```csharp
public string workAnim
```
#INC


#### Field Value

**Type:** System.String

### workAnimFace

```csharp
public string workAnimFace
```
#INC


#### Field Value

**Type:** System.String

### workCooltime

```csharp
public int workCooltime
```
#INC


#### Field Value

**Type:** System.Int32

### workDamage

```csharp
public DamageInfo workDamage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### workProbTable

```csharp
public CreatureWorkProbTable workProbTable
```
#INC


#### Field Value

**Type:** Global.CreatureWorkProbTable

## Properties

### codeId

```csharp
public string codeId { get; }
```

#### Property Value

**Type:** System.String

### collectionName

```csharp
public string collectionName { get; }
```

#### Property Value

**Type:** System.String

### CurrentObserveLevel

```csharp
public int CurrentObserveLevel { get; }
```

#### Property Value

**Type:** System.Int32

### name

```csharp
public string name { get; }
```

#### Property Value

**Type:** System.String

### portraitSrc

```csharp
public string portraitSrc { get; }
```

#### Property Value

**Type:** System.String

### portraitSrcForcely

```csharp
public string portraitSrcForcely { get; }
```

#### Property Value

**Type:** System.String

### riskLevel

```csharp
public virtual string riskLevel { get; }
```

#### Property Value

**Type:** System.String

### riskLevelForce

```csharp
public string riskLevelForce { get; }
```

#### Property Value

**Type:** System.String

### specialSkillName

```csharp
public string specialSkillName { get; }
```

#### Property Value

**Type:** System.String

## Methods

### ActivatedSpecialSkill()

```csharp
public void ActivatedSpecialSkill()
```
#INC


### AddAgentName(int, AgentName)

```csharp
public void AddAgentName(int index, AgentName input)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `input` | `Global.AgentName` |  |

### GetAgentName(int, out AgentName)

```csharp
public bool GetAgentName(int index, out AgentName name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `name` | `Global.AgentName` |  |

#### Returns

**Type:** System.Boolean

### GetRiskLevel()

```csharp
public virtual RiskLevel GetRiskLevel()
```
#INC


#### Returns

**Type:** Global.RiskLevel

### GetRiskLevelEnumToString(RiskLevel)

```csharp
public static string GetRiskLevelEnumToString(RiskLevel level)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns

**Type:** System.String

### GetRiskLevelStringToEnum(string)

```csharp
public static RiskLevel GetRiskLevelStringToEnum(string level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.String` |  |

#### Returns

**Type:** Global.RiskLevel
