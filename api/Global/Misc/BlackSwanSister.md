---
uid: Global.BlackSwanSister
canonical_path: /api/Global/Misc/BlackSwanSister
---

# Class BlackSwanSister

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackSwanSister : CreatureBase
```

[Dream of a Black Swan](/api/Global/IOBserver/BlackSwan)'s breaching form, the sister.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → BlackSwanSister

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BlackSwanSister()

```csharp
public BlackSwanSister()
```

## Fields

### _animScript

```csharp
private BlackSwanSisterAnim _animScript
```
#INC


#### Field Value

**Type:** Global.BlackSwanSisterAnim

### _unit

```csharp
private ChildCreatureUnit _unit
```
#INC


#### Field Value

**Type:** Global.ChildCreatureUnit

### annoyEffectFixedX

```csharp
private const float annoyEffectFixedX = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### annoyEffectFixedY

```csharp
private const float annoyEffectFixedY = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### attackCoolTime

```csharp
private const float attackCoolTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### attackCoolTimer

```csharp
private Timer attackCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attackDelayTime

```csharp
private const float attackDelayTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### attackDelayTimer

```csharp
private Timer attackDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attackDmgMax

```csharp
private const int attackDmgMax = 8
```
#INC


#### Field Value

**Type:** System.Int32

### attackDmgMin

```csharp
private const int attackDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Int32

### attackEffectFixedX

```csharp
private const float attackEffectFixedX = 0
```
#INC


#### Field Value

**Type:** System.Single

### attackEffectFixedY

```csharp
private const float attackEffectFixedY = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### attackRange

```csharp
private const float attackRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### brother

```csharp
private BlackSwan brother
```
#INC


#### Field Value

**Type:** Global.BlackSwan

### cryingSound

```csharp
private SoundEffectPlayer cryingSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### damageRange

```csharp
private const float damageRange = 4.6
```
#INC


#### Field Value

**Type:** System.Single

### effect_annoy

```csharp
private const string effect_annoy = "BlackSwanAnnoyEffect"
```
#INC


#### Field Value

**Type:** System.String

### effect_attack

```csharp
private const string effect_attack = "BlackSwanAttackEffect"
```
#INC


#### Field Value

**Type:** System.String

### effect_reflect

```csharp
private const string effect_reflect = "BlackSwanReflectEffect"
```
#INC


#### Field Value

**Type:** System.String

### effect_skill

```csharp
private const string effect_skill = "BlackSwanSkillEffect"
```
#INC


#### Field Value

**Type:** System.String

### effect_summon

```csharp
private const string effect_summon = "BlackSwanSummonEffect"
```
#INC


#### Field Value

**Type:** System.String

### effectSrc

```csharp
private const string effectSrc = "Effect/Creature/BlackSwan/"
```
#INC


#### Field Value

**Type:** System.String

### init

```csharp
private bool init
```
#INC


#### Field Value

**Type:** System.Boolean

### initTime

```csharp
private const float initTime = 4
```
#INC


#### Field Value

**Type:** System.Single

### initTimer

```csharp
private Timer initTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### neighborDoors

```csharp
private List<MapNode> neighborDoors
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### neighbors

```csharp
private List<BlackSwanSister.AnnoyedNeighbor> neighbors
```

#### Field Value

**Type:** System.Collections.Generic.List{BlackSwanSister.AnnoyedNeighbor}

### oldPassage

```csharp
private PassageObjectModel oldPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### reflectCoolTime

```csharp
private const float reflectCoolTime = 15
```
#INC


#### Field Value

**Type:** System.Single

### reflectCoolTimer

```csharp
private Timer reflectCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### reflectEffectFixedX

```csharp
private const float reflectEffectFixedX = 5
```
#INC


#### Field Value

**Type:** System.Single

### reflectEffectFixedY

```csharp
private const float reflectEffectFixedY = 2
```
#INC


#### Field Value

**Type:** System.Single

### reflectRemainTime

```csharp
private const float reflectRemainTime = 10
```
#INC


#### Field Value

**Type:** System.Single

### reflectRemainTimer

```csharp
private Timer reflectRemainTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### skillCoolTime

```csharp
private const float skillCoolTime = 25
```
#INC


#### Field Value

**Type:** System.Single

### skillCoolTimer

```csharp
private Timer skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### skillDmgMax

```csharp
private const int skillDmgMax = 45
```
#INC


#### Field Value

**Type:** System.Int32

### skillDmgMin

```csharp
private const int skillDmgMin = 30
```
#INC


#### Field Value

**Type:** System.Int32

### skillEffectFixedX

```csharp
private const float skillEffectFixedX = 0.8
```
#INC


#### Field Value

**Type:** System.Single

### skillEffectFixedY

```csharp
private const float skillEffectFixedY = 4.6
```
#INC


#### Field Value

**Type:** System.Single

### sound_atk_dmg

```csharp
public const string sound_atk_dmg = "atk_dmg"
```
#INC


#### Field Value

**Type:** System.String

### sound_dead

```csharp
public const string sound_dead = "dead"
```
#INC


#### Field Value

**Type:** System.String

### sound_pre_atk

```csharp
public const string sound_pre_atk = "pre_atk"
```
#INC


#### Field Value

**Type:** System.String

### sound_reflect

```csharp
public const string sound_reflect = "reflect"
```
#INC


#### Field Value

**Type:** System.String

### sound_skill

```csharp
public const string sound_skill = "skill"
```
#INC


#### Field Value

**Type:** System.String

### sound_trans

```csharp
public const string sound_trans = "trans"
```
#INC


#### Field Value

**Type:** System.String

### SubQliphothCounterCoolTime

```csharp
private const float SubQliphothCounterCoolTime = 30
```
#INC


#### Field Value

**Type:** System.Single

### summonEffectFixedX

```csharp
private const float summonEffectFixedX = 0
```
#INC


#### Field Value

**Type:** System.Single

### summonEffectFixedY

```csharp
private const float summonEffectFixedY = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### transformHpCondition

```csharp
private const float transformHpCondition = 0.4
```
#INC


#### Field Value

**Type:** System.Single

### transformInitTime

```csharp
private const float transformInitTime = 1.4
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### animScript

```csharp
public BlackSwanSisterAnim animScript { get; }
```

#### Property Value

**Type:** Global.BlackSwanSisterAnim

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### Model

```csharp
private ChildCreatureModel Model { get; }
```

#### Property Value

**Type:** Global.ChildCreatureModel

### skillDmg

```csharp
private static int skillDmg { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AttackEnd()

```csharp
public void AttackEnd()
```
#INC


### AttackStart()

```csharp
private void AttackStart()
```
#INC


### CanTakeDamage(UnitModel, DamageInfo)

```csharp
public override bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### GetSoundSrc(string)

```csharp
public string GetSoundSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GiveAttackDamage()

```csharp
public void GiveAttackDamage()
```
#INC


### HasEscapeUI()

```csharp
public override bool HasEscapeUI()
```
#INC


#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float)

```csharp
private bool IsInRange(UnitModel unit, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### MakeEffect(string, float, float, UnitModel)

```csharp
private GameObject MakeEffect(string src, float fixedX, float fixedY, UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `fixedX` | `System.Single` |  |
| `fixedY` | `System.Single` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeMovement()

```csharp
private void MakeMovement()
```
#INC


### MakeSound(string)

```csharp
public override SoundEffectPlayer MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string)

```csharp
public override SoundEffectPlayer MakeSoundLoop(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnTakeDamage(UnitModel, DamageInfo, float)

```csharp
public override void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
| `value` | `System.Single` |  |

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SetBrother(BlackSwan)

```csharp
private void SetBrother(BlackSwan brother)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `brother` | `Global.BlackSwan` |  |

### SetModel(CreatureModel)

```csharp
public override void SetModel(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SkillDamage()

```csharp
public void SkillDamage()
```
#INC


### SkillEnd()

```csharp
public void SkillEnd()
```
#INC


### SkillStart()

```csharp
private void SkillStart()
```
#INC

