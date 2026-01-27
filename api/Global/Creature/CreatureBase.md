---
uid: Global.CreatureBase
canonical_path: /api/Global/Creature/CreatureBase
---

# Class CreatureBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase
```
Parent class for all abnormalities, and I think a few other things too.

Handles some timers, behavior on work success/failure, work damage, behavior on entry, release, and work finish, escape behavior, effects, end-of-day behavior, observation level changes, room and work sprites, behavior on opening UI, loading and saving creature data, making sounds, qliphoth counters, making child abnos, and a MILLION OTHER THINGS TOO.

All of these implementations are virtual and are intended to be overridden by the abnormalities that use them.

#inc


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase

## Derived
[Alriune](/api/Global/Misc/Alriune), [AnonymousManPortrait](/api/Global/Misc/AnonymousManPortrait), [ArmorCreature](/api/Global/IOBserver/ArmorCreature), [AuthorNote](/api/Global/Misc/AuthorNote), [Baku](/api/Global/Misc/Baku), [Bald](/api/Global/Misc/Bald), [BeautyBeast](/api/Global/Misc/BeautyBeast), [BigBadWolf](/api/Global/IOBserver/BigBadWolf), [BigTreeSap](/api/Global/Misc/BigTreeSap), [BinahCoreScript](/api/Global/Script/BinahCoreScript), [BirdCreatureBase](/api/Global/Misc/BirdCreatureBase), [BlackCorps](/api/Global/Misc/BlackCorps), [BlackSwan](/api/Global/IOBserver/BlackSwan), [BlackSwanSister](/api/Global/Misc/BlackSwanSister), [BloodBath](/api/Global/Misc/BloodBath), [BloodyTree](/api/Global/Misc/BloodyTree), [BlueStar](/api/Global/IOBserver/BlueStar), [BugOrdealCreature](/api/Global/Creature/BugOrdealCreature), [Bunny](/api/Global/Misc/Bunny), [Butterfly](/api/Global/Misc/Butterfly), [CensoredCreatureBase](/api/Global/Misc/CensoredCreatureBase), [ChesedCoreScript](/api/Global/Script/ChesedCoreScript), [ChokhmahCoreScript](/api/Global/Script/ChokhmahCoreScript), [CircusOrdealCreature](/api/Global/Creature/CircusOrdealCreature), [Cosmos](/api/Global/Misc/Cosmos), [DangoCreature](/api/Global/IOBserver/DangoCreature), [DesireHeart](/api/Global/Misc/DesireHeart), [DontTouchMe](/api/Global/Misc/DontTouchMe), [DummyCreature](/api/Global/Creature/DummyCreature), [Fairy](/api/Global/Misc/Fairy), [FengYun](/api/Global/IOBserver/FengYun), [FireBird](/api/Global/IOBserver/FireBird), [FixerCreature](/api/Global/Creature/FixerCreature), [Freischutz](/api/Global/Misc/Freischutz), [GalaxyBoy](/api/Global/IOBserver/GalaxyBoy), [GeburahCoreScript](/api/Global/Script/GeburahCoreScript), [HappyTeddy](/api/Global/Misc/HappyTeddy), [HealthBracelet](/api/Global/Misc/HealthBracelet), [HellTrain](/api/Global/Misc/HellTrain), [Helper](/api/Global/Misc/Helper), [HodCoreScript](/api/Global/Script/HodCoreScript), [IronMaiden](/api/Global/Misc/IronMaiden), [JackLessTree](/api/Global/Misc/JackLessTree), [JusticeReceiver](/api/Global/Misc/JusticeReceiver), [KnightOfDespair](/api/Global/Misc/KnightOfDespair), [LadyLookingAtWall](/api/Global/Misc/LadyLookingAtWall), [LightsHammer](/api/Global/Misc/LightsHammer), [LittleWitch](/api/Global/Misc/LittleWitch), [LittleWitchMonster](/api/Global/Misc/LittleWitchMonster), [LookAtMe](/api/Global/Misc/LookAtMe), [Lumberjack](/api/Global/Misc/Lumberjack), [MachineOrdealCreature](/api/Global/Creature/MachineOrdealCreature), [MagicalGirl](/api/Global/IOBserver/MagicalGirl), [MagicalGirl_2](/api/Global/Misc/MagicalGirl2), [MalkutCoreScript](/api/Global/Script/MalkutCoreScript), [MatchGirl](/api/Global/Misc/MatchGirl), [MeatIdol](/api/Global/Misc/MeatIdol), [Mhz_1_76](/api/Global/Misc/Mhz176), [NamelessFetus](/api/Global/Misc/NamelessFetus), [NetzachCoreScript](/api/Global/Script/NetzachCoreScript), [Nothing](/api/Global/Misc/Nothing), [OldLady](/api/Global/IOBserver/OldLady), [OneBadManyGood](/api/Global/Misc/OneBadManyGood), [OtherWorldPortrait](/api/Global/IOBserver/OtherWorldPortrait), [OutterGodOrdealCreature](/api/Global/Creature/OutterGodOrdealCreature), [Piano](/api/Global/Misc/Piano), [PianoCreature](/api/Global/Creature/PianoCreature), [PinkCorps](/api/Global/IOBserver/PinkCorps), [Porccu](/api/Global/Misc/Porccu), [Ppodae](/api/Global/Misc/Ppodae), [PromiseAndFaith](/api/Global/Misc/PromiseAndFaith), [ProphecyOfSkin](/api/Global/IOBserver/ProphecyOfSkin), [QueenBee](/api/Global/Misc/QueenBee), [QueenBeeWorker](/api/Global/Worker/QueenBeeWorker), [Reaper](/api/Global/Misc/Reaper), [RedHood](/api/Global/IOBserver/RedHood), [RedShoes](/api/Global/Misc/RedShoes), [ResearcherNote](/api/Global/Misc/ResearcherNote), [ResetMirror](/api/Global/Misc/ResetMirror), [ReverseClock](/api/Global/Misc/ReverseClock), [Rudolph](/api/Global/Misc/Rudolph), [Sakura](/api/Global/Misc/Sakura), [Scarecrow](/api/Global/Misc/Scarecrow), [ScavengerOrdealCreature](/api/Global/Creature/ScavengerOrdealCreature), [ScytheClock](/api/Global/Misc/ScytheClock), [Shark](/api/Global/Misc/Shark), [Shelter](/api/Global/Misc/Shelter), [ShyThing](/api/Global/Misc/ShyThing), [SilentGirl](/api/Global/Misc/SilentGirl), [SilentOrchestra](/api/Global/Misc/SilentOrchestra), [SingingMachine](/api/Global/Machine/SingingMachine), [SlimeCreature](/api/Global/Creature/SlimeCreature), [SmilePierrot](/api/Global/Misc/SmilePierrot), [SnowQueen](/api/Global/Misc/SnowQueen), [SnowWhite](/api/Global/Misc/SnowWhite), [SpiderMom](/api/Global/Misc/SpiderMom), [StraitJacket](/api/Global/Misc/StraitJacket), [Theresia](/api/Global/Misc/Theresia), [TipherethCoreScript](/api/Global/Script/TipherethCoreScript), [ViscusSnake](/api/Global/Misc/ViscusSnake), [VoidBook](/api/Global/Misc/VoidBook), [Wellcheers](/api/Global/Misc/Wellcheers), [Wraith](/api/Global/Misc/Wraith), [YesodCoreScript](/api/Global/Script/YesodCoreScript), [Yggdrasil](/api/Global/IOBserver/Yggdrasil), [Yggdrasil_Sapling](/api/Global/Misc/YggdrasilSapling), [YinAndYangBase](/api/Global/Misc/YinAndYangBase), [YouMustHappy](/api/Global/IOBserver/YouMustHappy), [YoungPrince](/api/Global/IOBserver/YoungPrince), [YoungPrinceFriend](/api/Global/Misc/YoungPrinceFriend), [DeathAngel](/api/Legacy/DeathAngel), [PlagueDoctor](/api/Legacy/PlagueDoctor), [DeathAngel](/api/WhiteNightSpace/DeathAngel), [DeathAngelApostle](/api/WhiteNightSpace/DeathAngelApostle), [PlagueDoctor](/api/WhiteNightSpace/PlagueDoctor)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureBase()

```csharp
public CreatureBase()
```

## Fields

### _allocatedAgent

```csharp
private AgentModel _allocatedAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _check

```csharp
private SkillTriggerCheck _check
```
#INC


#### Field Value

**Type:** Global.SkillTriggerCheck

### damage

```csharp
public int damage
```
#INC


#### Field Value

**Type:** System.Int32

### hasUniqueEscapeLogic

```csharp
public bool hasUniqueEscapeLogic
```
#INC


#### Field Value

**Type:** System.Boolean

### isolateSpriteSrc

```csharp
public const string isolateSpriteSrc = "Sprites/CreatureSprite/Isolate/"
```
#INC


#### Field Value

**Type:** System.String

### isWorkAllocated

```csharp
public bool isWorkAllocated
```
#INC


#### Field Value

**Type:** System.Boolean

### kitEvent

```csharp
public CreatureBase.KitEquipEventListener kitEvent
```

#### Field Value

**Type:** Global.CreatureBase.KitEquipEventListener

### model

```csharp
public CreatureModel model
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### OnReleaseSpecialTip

```csharp
public List<string> OnReleaseSpecialTip
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### skill

```csharp
public CreatureSpecialSkill skill
```
#INC


#### Field Value

**Type:** Global.CreatureSpecialSkill

### specialSkillTipParamList

```csharp
public List<CreatureBase.SpecialSkillTipParameter> specialSkillTipParamList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureBase.SpecialSkillTipParameter}

## Properties

### AllocatedAgent

```csharp
public AgentModel AllocatedAgent { get; }
```

#### Property Value

**Type:** Global.AgentModel

### currentPassage

```csharp
public virtual PassageObjectModel currentPassage { get; }
```

#### Property Value

**Type:** Global.PassageObjectModel

### GetSaveSrc

```csharp
public string GetSaveSrc { get; }
```

#### Property Value

**Type:** System.String

### movable

```csharp
public virtual MovableObjectNode movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

### skillTriggerCheck

```csharp
public SkillTriggerCheck skillTriggerCheck { get; }
```

#### Property Value

**Type:** Global.SkillTriggerCheck

### Unit

```csharp
public CreatureUnit Unit { get; }
```

#### Property Value

**Type:** Global.CreatureUnit

## Methods

### ActivateQliphothCounter()

```csharp
public virtual void ActivateQliphothCounter()
```
#INC


### AddedQliphothCounter()

```csharp
public virtual void AddedQliphothCounter()
```
#INC


### AgentAnimCalled(int, WorkerModel)

```csharp
public virtual void AgentAnimCalled(int i, WorkerModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `actor` | `Global.WorkerModel` |  |

### AttackProcess(UnitModel)

```csharp
public virtual bool AttackProcess(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### AutoFeelingDown()

```csharp
public virtual bool AutoFeelingDown()
```
#INC


#### Returns

**Type:** System.Boolean

### CanEnterRoom()

```csharp
public virtual bool CanEnterRoom()
```
#INC


#### Returns

**Type:** System.Boolean

### CanObservedByAgent(AgentModel)

```csharp
public virtual bool CanObservedByAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### CanTakeDamage(UnitModel, DamageInfo)

```csharp
public virtual bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### DelayAttackMotion(float)

```csharp
public virtual void DelayAttackMotion(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### Escape()

```csharp
public virtual void Escape()
```
#INC


### ExistSaveData()

```csharp
public bool ExistSaveData()
```
#INC


#### Returns

**Type:** System.Boolean

### ForcelyFail(UseSkill)

```csharp
public virtual bool ForcelyFail(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### ForcelySuccess(UseSkill)

```csharp
public virtual bool ForcelySuccess(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### GenPursueCommandAlter(WorkerModel)

```csharp
public virtual bool GenPursueCommandAlter(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### GetDamageFactor(UnitModel, DamageInfo)

```csharp
public virtual float GetDamageFactor(UnitModel target, DamageInfo damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### GetDamageMultiplierInWork(UseSkill)

```csharp
public virtual float GetDamageMultiplierInWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Single

### GetDebugText()

```csharp
public virtual string GetDebugText()
```
#INC


#### Returns

**Type:** System.String

### GetKitCreatureProcessTime()

```csharp
public virtual float GetKitCreatureProcessTime()
```
#INC


#### Returns

**Type:** System.Single

### GetMaxWorkCountView()

```csharp
public virtual int GetMaxWorkCountView()
```
#INC


#### Returns

**Type:** System.Int32

### GetMentalDamage(out float)

```csharp
public virtual bool GetMentalDamage(out float dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetName()

```csharp
public virtual string GetName()
```
#INC


#### Returns

**Type:** System.String

### GetPhysicalDamage(out float)

```csharp
public virtual bool GetPhysicalDamage(out float dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetQliphothCounterMax()

```csharp
public virtual int GetQliphothCounterMax()
```
#INC


#### Returns

**Type:** System.Int32

### GetRadius()

```csharp
public virtual float GetRadius()
```
#INC


#### Returns

**Type:** System.Single

### GetRealTargets()

```csharp
public virtual UnitModel[] GetRealTargets()
```
#INC


#### Returns

**Type:** Global.UnitModel[]

### GetRiskLevel()

```csharp
public virtual string GetRiskLevel()
```
#INC


#### Returns

**Type:** System.String

### GetSaveData()

```csharp
public virtual Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpecialSkill()

```csharp
public virtual SkillTypeInfo GetSpecialSkill()
```
#INC


#### Returns

**Type:** Global.SkillTypeInfo

### HasEscapeUI()

```csharp
public virtual bool HasEscapeUI()
```
#INC


#### Returns

**Type:** System.Boolean

### HasRoomCounter()

```csharp
public virtual bool HasRoomCounter()
```
#INC


#### Returns

**Type:** System.Boolean

### HasScriptSaveData()

```csharp
public virtual bool HasScriptSaveData()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueAttackDealy()

```csharp
public virtual bool HasUniqueAttackDealy()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueCollectionCost(string, out string)

```csharp
public virtual bool HasUniqueCollectionCost(string areaName, out string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `areaName` | `System.String` |  |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### HasUniqueCommandAction(int)

```csharp
public virtual bool HasUniqueCommandAction(int workType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### hasUniqueDeadScene()

```csharp
public virtual bool hasUniqueDeadScene()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueFaction()

```csharp
public virtual bool HasUniqueFaction()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueMaxObservationFinish()

```csharp
public virtual bool HasUniqueMaxObservationFinish()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueName()

```csharp
public virtual bool HasUniqueName()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueProcessWorkNarration()

```csharp
public virtual bool HasUniqueProcessWorkNarration()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueWorkSelect(int)

```csharp
public virtual int HasUniqueWorkSelect(int workId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workId` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### IsActivatedWorkDesc()

```csharp
public virtual bool IsActivatedWorkDesc()
```
#INC


#### Returns

**Type:** System.Boolean

### isAttackInWorkProcess()

```csharp
public virtual bool isAttackInWorkProcess()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public virtual bool IsAutoSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsIndirectSuppressable()

```csharp
public virtual bool IsIndirectSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSensoredInPassage()

```csharp
public virtual bool IsSensoredInPassage()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSuppressable()

```csharp
public virtual bool IsSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSuppressableByRoom()

```csharp
public virtual bool IsSuppressableByRoom()
```
#INC


#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public virtual bool IsWorkable()
```
#INC


#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public virtual void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadScriptData()

```csharp
public virtual void LoadScriptData()
```
#INC


### MakeChildCreature(UnitModel)

```csharp
public virtual ChildCreatureModel MakeChildCreature(UnitModel origin)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.ChildCreatureModel

### MakeEffect(IsolateRoom, int)

```csharp
public virtual void MakeEffect(IsolateRoom room, int currentSkillResult)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `room` | `Global.IsolateRoom` |  |
| `currentSkillResult` | `System.Int32` |  |

### MakeEffectAlter(IsolateRoom, int)

```csharp
public void MakeEffectAlter(IsolateRoom room, int result)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `room` | `Global.IsolateRoom` |  |
| `result` | `System.Int32` |  |

### MakeEffectAttachedToHead(string)

```csharp
public virtual GameObject MakeEffectAttachedToHead(string effectSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effectSrc` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectGlobalPos(string, Vector3)

```csharp
public virtual GameObject MakeEffectGlobalPos(string src, Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectGlobalPosNonTrans(string, Vector3)

```csharp
public virtual GameObject MakeEffectGlobalPosNonTrans(string src, Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeSound(string)

```csharp
public virtual SoundEffectPlayer MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, AudioRolloffMode)

```csharp
public virtual SoundEffectPlayer MakeSound(string src, AudioRolloffMode mode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `mode` | `UnityEngine.AudioRolloffMode` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, float)

```csharp
public virtual SoundEffectPlayer MakeSound(string src, float pitch)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pitch` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string)

```csharp
public virtual SoundEffectPlayer MakeSoundLoop(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundQueue(params string[])

```csharp
public virtual SoundEffectPlayer MakeSoundQueue(params string[] fileName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String[]` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakingEffect(string, float)

```csharp
public virtual void MakingEffect(string effect, float effectLength)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |

### MakingEffect(string, float, string, Transform, int)

```csharp
public virtual void MakingEffect(string effect, float effectLength, string sound, Transform parent, int recoil)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |
| `sound` | `System.String` |  |
| `parent` | `UnityEngine.Transform` |  |
| `recoil` | `System.Int32` |  |

### MakingEffect(string, float, string, Vector3, int)

```csharp
public virtual void MakingEffect(string effect, float effectLength, string sound, Vector3 pos, int recoil)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |
| `sound` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `recoil` | `System.Int32` |  |

### ObserveLevelChangeForSpecialSkillTip()

```csharp
public void ObserveLevelChangeForSpecialSkillTip()
```
#INC


### OnAfterSuppressed()

```csharp
public virtual bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAgentAllocateWork(AgentModel)

```csharp
public virtual void OnAgentAllocateWork(AgentModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnAgentAnimatorReseted()

```csharp
public virtual void OnAgentAnimatorReseted()
```
#INC


### OnAgentWorkEndAnimationPlayed(UseSkill)

```csharp
public virtual void OnAgentWorkEndAnimationPlayed(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnAllocatedWork(AgentModel)

```csharp
public virtual void OnAllocatedWork(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### OnAttackInWorkProcess(UseSkill)

```csharp
public virtual void OnAttackInWorkProcess(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnBonusWorkProb()

```csharp
public virtual int OnBonusWorkProb()
```
#INC


#### Returns

**Type:** System.Int32

### OnChildSuppressed(ChildCreatureModel)

```csharp
public virtual void OnChildSuppressed(ChildCreatureModel child)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.ChildCreatureModel` |  |

### OnElevatorStuck()

```csharp
public virtual void OnElevatorStuck()
```
#INC


### OnEnterRoom(UseSkill)

```csharp
public virtual void OnEnterRoom(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFeverTimeOver()

```csharp
public virtual void OnFeverTimeOver()
```
#INC


### OnFinishWork(UseSkill)

```csharp
public virtual void OnFinishWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public virtual void OnFixedUpdate(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnFixedUpdateInSkill(UseSkill)

```csharp
public virtual void OnFixedUpdateInSkill(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnForceSpecialSkillTipReveal(string, params object[])

```csharp
public virtual void OnForceSpecialSkillTipReveal(string key, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnGamemanagerInit()

```csharp
public virtual void OnGamemanagerInit()
```
#INC


### OnInit()

```csharp
public virtual void OnInit()
```
#INC


### OnInitialBuild()

```csharp
public virtual void OnInitialBuild()
```
#INC


### OnKillWorker(WorkerModel)

```csharp
public virtual bool OnKillWorker(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### OnLoadCreatureName(ref string)

```csharp
public virtual bool OnLoadCreatureName(ref string nameOut)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nameOut` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### OnObserveLevelChanged()

```csharp
public virtual void OnObserveLevelChanged()
```
#INC


### OnOpenCollectionWindow()

```csharp
public virtual bool OnOpenCollectionWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOpenCommandWindow(Button[])

```csharp
public virtual void OnOpenCommandWindow(Button[] buttons)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenObserveWindow()

```csharp
public virtual bool OnOpenObserveWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOpenWorkWindow()

```csharp
public virtual bool OnOpenWorkWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOverlayIsolateObserve()

```csharp
public virtual bool OnOverlayIsolateObserve()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOverlayIsolateWork()

```csharp
public virtual bool OnOverlayIsolateWork()
```
#INC


#### Returns

**Type:** System.Boolean

### OnReleaseWork(UseSkill)

```csharp
public virtual void OnReleaseWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReleaseWorkAllocated()

```csharp
public virtual void OnReleaseWorkAllocated()
```
#INC


### OnReturn()

```csharp
public virtual void OnReturn()
```
#INC


### OnSelectMaxObservation(int)

```csharp
public virtual void OnSelectMaxObservation(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSkillFailWorkTick(UseSkill)

```csharp
public virtual void OnSkillFailWorkTick(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillGoalComplete(UseSkill)

```csharp
public virtual void OnSkillGoalComplete(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillSuccessWorkTick(UseSkill)

```csharp
public virtual void OnSkillSuccessWorkTick(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillTickUpdate(UseSkill)

```csharp
public virtual void OnSkillTickUpdate(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```
#INC


### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public virtual void OnStageStart()
```
#INC


### OnSuperArmorBreak()

```csharp
public virtual void OnSuperArmorBreak()
```
#INC


### OnSuppressed()

```csharp
public virtual void OnSuppressed()
```
#INC


### OnTakeDamage(UnitModel, DamageInfo, float)

```csharp
public virtual void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
| `value` | `System.Single` |  |

### OnTakePhysicalDamage(UnitModel, float)

```csharp
public virtual void OnTakePhysicalDamage(UnitModel attacker, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### OnTimerEnd()

```csharp
public virtual void OnTimerEnd()
```
#INC


### OnViewDestroy()

```csharp
public virtual void OnViewDestroy()
```
#INC


### OnViewInit(CreatureUnit)

```csharp
public virtual void OnViewInit(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnViewInitPrev(CreatureUnit)

```csharp
public void OnViewInitPrev(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkAllocated(SkillTypeInfo, AgentModel)

```csharp
public virtual void OnWorkAllocated(SkillTypeInfo skill, AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |
| `agent` | `Global.AgentModel` |  |

### OnWorkClosed(UseSkill, int)

```csharp
public virtual void OnWorkClosed(UseSkill skill, int successCount)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |
| `successCount` | `System.Int32` |  |

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public virtual void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### OnWorkerPanic(WorkerModel)

```csharp
public virtual bool OnWorkerPanic(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### OnWorkReleaseSpeicalSkillTipReveal(string)

```csharp
public virtual void OnWorkReleaseSpeicalSkillTipReveal(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### OnWorkReleaseTipUpdate(params object[])

```csharp
public virtual void OnWorkReleaseTipUpdate(params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

### OnWorkWindowSkillClicked(long)

```csharp
public virtual void OnWorkWindowSkillClicked(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### ParamInit()

```csharp
public virtual void ParamInit()
```
#INC


### PermitCancelCurrentWork()

```csharp
public virtual bool PermitCancelCurrentWork()
```
#INC


#### Returns

**Type:** System.Boolean

### Prob(int)

```csharp
public virtual bool Prob(int probability)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `probability` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### ReducedQliphothCounter()

```csharp
public virtual void ReducedQliphothCounter()
```
#INC


### RemoveSaveData()

```csharp
public void RemoveSaveData()
```
#INC


### ReplaceCommand(CreatureModel)

```csharp
public void ReplaceCommand(CreatureModel replaced)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `replaced` | `Global.CreatureModel` |  |

### ResetQliphothCounter()

```csharp
public virtual void ResetQliphothCounter()
```
#INC


### RoomCounterInit()

```csharp
public virtual void RoomCounterInit()
```
#INC


### RoomEscapeSpriteOff()

```csharp
public virtual void RoomEscapeSpriteOff()
```
#INC


### RoomEscapeSpriteOn()

```csharp
public virtual void RoomEscapeSpriteOn()
```
#INC


### RoomSkillSpriteOff()

```csharp
public virtual void RoomSkillSpriteOff()
```
#INC


### RoomSkillSpriteOn()

```csharp
public virtual void RoomSkillSpriteOn()
```
#INC


### RoomSpriteInit()

```csharp
public virtual void RoomSpriteInit()
```
#INC


### RoomStateSpriteOff()

```csharp
public virtual void RoomStateSpriteOff()
```
#INC


### RoomStateSpriteOn()

```csharp
public virtual void RoomStateSpriteOn()
```
#INC


### SaveScriptData()

```csharp
public virtual void SaveScriptData()
```
#INC


### SetCastingSlider(Slider)

```csharp
public virtual bool SetCastingSlider(Slider castingSlider)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetHpSlider(Slider)

```csharp
public virtual bool SetHpSlider(Slider slider)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetModel(CreatureModel)

```csharp
public virtual void SetModel(CreatureModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SpecialEnergyTick()

```csharp
public virtual float SpecialEnergyTick()
```
#INC


#### Returns

**Type:** System.Single

### TranformWorkProb(float)

```csharp
public virtual float TranformWorkProb(float originWorkProb)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `originWorkProb` | `System.Single` |  |

#### Returns

**Type:** System.Single

### TryRabbitTeleport(MapNode)

```csharp
public virtual bool TryRabbitTeleport(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** System.Boolean

### UniqueEscape()

```csharp
public virtual void UniqueEscape()
```
#INC


### UniqueMaxObservationFinish(Desc)

```csharp
public virtual bool UniqueMaxObservationFinish(CreatureMaxObserve.Desc desc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `Global.CreatureMaxObserve.Desc` |  |

#### Returns

**Type:** System.Boolean

### UniqueMoveControl()

```csharp
public virtual bool UniqueMoveControl()
```
#INC


#### Returns

**Type:** System.Boolean

### UniqueProcessWorkNarration(UseSkill)

```csharp
public virtual void UniqueProcessWorkNarration(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### UniqueStunEffect()

```csharp
public virtual bool UniqueStunEffect()
```
#INC


#### Returns

**Type:** System.Boolean

### UseDefaultDamageIgnoreMessage(DamageTextEffect)

```csharp
public virtual bool UseDefaultDamageIgnoreMessage(DamageTextEffect damageScript)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageScript` | `Global.DamageTextEffect` |  |

#### Returns

**Type:** System.Boolean
