---
uid: Global.ChildCreatureTypeInfo
canonical_path: /api/Global/Creature/ChildCreatureTypeInfo
---

# Class ChildCreatureTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureTypeInfo : CreatureTypeInfo
```

Holds basic type information for a [ChildCreatureModel](/api/Global/Creature/ChildCreatureModel), like risk level and attack type.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureTypeInfo](/api/Global/Info/CreatureTypeInfo) → ChildCreatureTypeInfo

## Inherited Members
[stringData](/api/Global/Info/CreatureTypeInfo#stringdata), [intData](/api/Global/Info/CreatureTypeInfo#intdata), [childTypeInfo](/api/Global/Info/CreatureTypeInfo#childtypeinfo), [noDataString](/api/Global/Info/CreatureTypeInfo#nodatastring), [id](/api/Global/Info/CreatureTypeInfo#id), [maxHp](/api/Global/Info/CreatureTypeInfo#maxhp), [creatureWorkType](/api/Global/Info/CreatureTypeInfo#creatureworktype), [creatureKitType](/api/Global/Info/CreatureTypeInfo#creaturekittype), [kitIconSrc](/api/Global/Info/CreatureTypeInfo#kiticonsrc), [workAnim](/api/Global/Info/CreatureTypeInfo#workanim), [workAnimFace](/api/Global/Info/CreatureTypeInfo#workanimface), [feelingStateCubeBounds](/api/Global/Info/CreatureTypeInfo#feelingstatecubebounds), [creatureSpecialDamageTable](/api/Global/Info/CreatureTypeInfo#creaturespecialdamagetable), [workDamage](/api/Global/Info/CreatureTypeInfo#workdamage), [defenseTable](/api/Global/Info/CreatureTypeInfo#defensetable), [workCooltime](/api/Global/Info/CreatureTypeInfo#workcooltime), [cubeSpeed](/api/Global/Info/CreatureTypeInfo#cubespeed), [workProbTable](/api/Global/Info/CreatureTypeInfo#workprobtable), [observeData](/api/Global/Info/CreatureTypeInfo#observedata), [equipMakeInfos](/api/Global/Info/CreatureTypeInfo#equipmakeinfos), [observeBonus](/api/Global/Info/CreatureTypeInfo#observebonus), [maxWorkCount](/api/Global/Info/CreatureTypeInfo#maxworkcount), [maxProbReductionCounter](/api/Global/Info/CreatureTypeInfo#maxprobreductioncounter), [probReduction](/api/Global/Info/CreatureTypeInfo#probreduction), [animSrc](/api/Global/Info/CreatureTypeInfo#animsrc), [roomReturnSrc](/api/Global/Info/CreatureTypeInfo#roomreturnsrc), [script](/api/Global/Info/CreatureTypeInfo#script), [qliphothMax](/api/Global/Info/CreatureTypeInfo#qliphothmax), [typoTable](/api/Global/Info/CreatureTypeInfo#typotable), [narrationTable](/api/Global/Info/CreatureTypeInfo#narrationtable), [soundTable](/api/Global/Info/CreatureTypeInfo#soundtable), [observe](/api/Global/Info/CreatureTypeInfo#observe), [openText](/api/Global/Info/CreatureTypeInfo#opentext), [observeList](/api/Global/Info/CreatureTypeInfo#observelist), [nodeInfo](/api/Global/Info/CreatureTypeInfo#nodeinfo), [edgeInfo](/api/Global/Info/CreatureTypeInfo#edgeinfo), [dataTable](/api/Global/Info/CreatureTypeInfo#datatable), [observeTable](/api/Global/Info/CreatureTypeInfo#observetable), [specialSkillTable](/api/Global/Info/CreatureTypeInfo#specialskilltable), [collectionUsedAgentName](/api/Global/Info/CreatureTypeInfo#collectionusedagentname), [isEscapeAble](/api/Global/Info/CreatureTypeInfo#isescapeable), [MaxObserveLevel](/api/Global/Info/CreatureTypeInfo#maxobservelevel), [speed](/api/Global/Info/CreatureTypeInfo#speed), [_isChildAndHasData](/api/Global/Info/CreatureTypeInfo#ischildandhasdata), [_tempPortrait](/api/Global/Info/CreatureTypeInfo#tempportrait), [activateSpecialSkill](/api/Global/Info/CreatureTypeInfo#activatespecialskill), [tempPortrait](/api/Global/Info/CreatureTypeInfo#tempportrait), [desc](/api/Global/Info/CreatureTypeInfo#desc), [observeRecord](/api/Global/Info/CreatureTypeInfo#observerecord), [skillTriggerCheck](/api/Global/Info/CreatureTypeInfo#skilltriggercheck), [maxObserveModule](/api/Global/Info/CreatureTypeInfo#maxobservemodule), [creatureStaticData](/api/Global/Info/CreatureTypeInfo#creaturestaticdata), [GetRiskLevelEnumToString(RiskLevel)](/api/Global/Info/CreatureTypeInfo#getrisklevelenumtostring-risklevel), [GetRiskLevelStringToEnum(string)](/api/Global/Info/CreatureTypeInfo#getrisklevelstringtoenum-string), [ActivatedSpecialSkill()](/api/Global/Info/CreatureTypeInfo#activatedspecialskill), [GetAgentName(int, out AgentName)](/api/Global/Info/CreatureTypeInfo#getagentname-int-out-agentname), [AddAgentName(int, AgentName)](/api/Global/Info/CreatureTypeInfo#addagentname-int-agentname), [CurrentObserveLevel](/api/Global/Info/CreatureTypeInfo#currentobservelevel), [name](/api/Global/Info/CreatureTypeInfo#name), [collectionName](/api/Global/Info/CreatureTypeInfo#collectionname), [codeId](/api/Global/Info/CreatureTypeInfo#codeid), [riskLevelForce](/api/Global/Info/CreatureTypeInfo#risklevelforce), [portraitSrc](/api/Global/Info/CreatureTypeInfo#portraitsrc), [portraitSrcForcely](/api/Global/Info/CreatureTypeInfo#portraitsrcforcely), [specialSkillName](/api/Global/Info/CreatureTypeInfo#specialskillname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


#### Field Value

**Type:** System.String

### _riskLevel

```csharp
public string _riskLevel
```
#INC


#### Field Value

**Type:** System.String

### attackTypeOpen

```csharp
public int attackTypeOpen
```
#INC


#### Field Value

**Type:** System.Int32

### data

```csharp
public ChildCreatureData data
```
#INC


#### Field Value

**Type:** Global.ChildCreatureData

### isHasBaseMeta

```csharp
public bool isHasBaseMeta
```
#INC


#### Field Value

**Type:** System.Boolean

### riskLevelOpen

```csharp
public int riskLevelOpen
```
#INC


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
#INC


#### Returns

**Type:** Global.RwbpType

### GetRiskLevel()

```csharp
public override RiskLevel GetRiskLevel()
```
#INC
#code-generated


#### Returns

**Type:** Global.RiskLevel
