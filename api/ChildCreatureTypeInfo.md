# Class ChildCreatureTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureTypeInfo : CreatureTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureTypeInfo](/api/CreatureTypeInfo) → ChildCreatureTypeInfo

## Inherited Members
[stringData](/api/CreatureTypeInfo#stringdata), [intData](/api/CreatureTypeInfo#intdata), [childTypeInfo](/api/CreatureTypeInfo#childtypeinfo), [noDataString](/api/CreatureTypeInfo#nodatastring), [id](/api/CreatureTypeInfo#id), [maxHp](/api/CreatureTypeInfo#maxhp), [creatureWorkType](/api/CreatureTypeInfo#creatureworktype), [creatureKitType](/api/CreatureTypeInfo#creaturekittype), [kitIconSrc](/api/CreatureTypeInfo#kiticonsrc), [workAnim](/api/CreatureTypeInfo#workanim), [workAnimFace](/api/CreatureTypeInfo#workanimface), [feelingStateCubeBounds](/api/CreatureTypeInfo#feelingstatecubebounds), [creatureSpecialDamageTable](/api/CreatureTypeInfo#creaturespecialdamagetable), [workDamage](/api/CreatureTypeInfo#workdamage), [defenseTable](/api/CreatureTypeInfo#defensetable), [workCooltime](/api/CreatureTypeInfo#workcooltime), [cubeSpeed](/api/CreatureTypeInfo#cubespeed), [workProbTable](/api/CreatureTypeInfo#workprobtable), [observeData](/api/CreatureTypeInfo#observedata), [equipMakeInfos](/api/CreatureTypeInfo#equipmakeinfos), [observeBonus](/api/CreatureTypeInfo#observebonus), [maxWorkCount](/api/CreatureTypeInfo#maxworkcount), [maxProbReductionCounter](/api/CreatureTypeInfo#maxprobreductioncounter), [probReduction](/api/CreatureTypeInfo#probreduction), [animSrc](/api/CreatureTypeInfo#animsrc), [roomReturnSrc](/api/CreatureTypeInfo#roomreturnsrc), [script](/api/CreatureTypeInfo#script), [qliphothMax](/api/CreatureTypeInfo#qliphothmax), [typoTable](/api/CreatureTypeInfo#typotable), [narrationTable](/api/CreatureTypeInfo#narrationtable), [soundTable](/api/CreatureTypeInfo#soundtable), [observe](/api/CreatureTypeInfo#observe), [openText](/api/CreatureTypeInfo#opentext), [observeList](/api/CreatureTypeInfo#observelist), [nodeInfo](/api/CreatureTypeInfo#nodeinfo), [edgeInfo](/api/CreatureTypeInfo#edgeinfo), [dataTable](/api/CreatureTypeInfo#datatable), [observeTable](/api/CreatureTypeInfo#observetable), [specialSkillTable](/api/CreatureTypeInfo#specialskilltable), [collectionUsedAgentName](/api/CreatureTypeInfo#collectionusedagentname), [isEscapeAble](/api/CreatureTypeInfo#isescapeable), [MaxObserveLevel](/api/CreatureTypeInfo#maxobservelevel), [speed](/api/CreatureTypeInfo#speed), [_isChildAndHasData](/api/CreatureTypeInfo#ischildandhasdata), [_tempPortrait](/api/CreatureTypeInfo#tempportrait), [tempPortrait](/api/CreatureTypeInfo#tempportrait), [desc](/api/CreatureTypeInfo#desc), [observeRecord](/api/CreatureTypeInfo#observerecord), [skillTriggerCheck](/api/CreatureTypeInfo#skilltriggercheck), [maxObserveModule](/api/CreatureTypeInfo#maxobservemodule), [creatureStaticData](/api/CreatureTypeInfo#creaturestaticdata), [GetRiskLevelEnumToString(RiskLevel)](/api/CreatureTypeInfo#getrisklevelenumtostring-risklevel), [GetRiskLevelStringToEnum(string)](/api/CreatureTypeInfo#getrisklevelstringtoenum-string), [ActivatedSpecialSkill()](/api/CreatureTypeInfo#activatedspecialskill), [GetAgentName(int, out AgentName)](/api/CreatureTypeInfo#getagentname-int-out-agentname), [AddAgentName(int, AgentName)](/api/CreatureTypeInfo#addagentname-int-agentname), [CurrentObserveLevel](/api/CreatureTypeInfo#currentobservelevel), [name](/api/CreatureTypeInfo#name), [collectionName](/api/CreatureTypeInfo#collectionname), [codeId](/api/CreatureTypeInfo#codeid), [riskLevelForce](/api/CreatureTypeInfo#risklevelforce), [portraitSrc](/api/CreatureTypeInfo#portraitsrc), [portraitSrcForcely](/api/CreatureTypeInfo#portraitsrcforcely), [specialSkillName](/api/CreatureTypeInfo#specialskillname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ChildCreatureTypeInfo()

```csharp
public ChildCreatureTypeInfo()
```

## Fields

### _attackType

```csharp
public string _attackType
```

#### Field Value

**Type:** System.String

### _riskLevel

```csharp
public string _riskLevel
```

#### Field Value

**Type:** System.String

### attackTypeOpen

```csharp
public int attackTypeOpen
```

#### Field Value

**Type:** System.Int32

### data

```csharp
public ChildCreatureData data
```

#### Field Value

**Type:** Global.ChildCreatureData

### isHasBaseMeta

```csharp
public bool isHasBaseMeta
```

#### Field Value

**Type:** System.Boolean

### riskLevelOpen

```csharp
public int riskLevelOpen
```

#### Field Value

**Type:** System.Int32

## Properties

### attackType

```csharp
public string attackType { get; }
```

#### Property Value

**Type:** System.String

### riskLevel

```csharp
public override string riskLevel { get; }
```

#### Property Value

**Type:** System.String

## Methods

### GetAttackType()

```csharp
public RwbpType GetAttackType()
```

#### Returns

**Type:** Global.RwbpType

### GetRiskLevel()

```csharp
public override RiskLevel GetRiskLevel()
```

#### Returns

**Type:** Global.RiskLevel
