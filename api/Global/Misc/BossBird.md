---
uid: Global.BossBird
canonical_path: /api/Global/Misc/BossBird
---

# Class BossBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBird : BirdCreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [BirdCreatureBase](/api/Global/Misc/BirdCreatureBase) → BossBird

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBird()

```csharp
public BossBird()
```

## Fields

### _attackDmgMax

```csharp
private const int _attackDmgMax = 43
```

#### Field Value

**Type:** System.Int32

### _attackDmgMin

```csharp
private const int _attackDmgMin = 23
```

#### Field Value

**Type:** System.Int32

### _attractMax

```csharp
private const int _attractMax = 5
```

#### Field Value

**Type:** System.Int32

### _attractMin

```csharp
private const int _attractMin = 3
```

#### Field Value

**Type:** System.Int32

### _biteDmgMax

```csharp
private const int _biteDmgMax = 115
```

#### Field Value

**Type:** System.Int32

### _biteDmgMin

```csharp
private const int _biteDmgMin = 50
```

#### Field Value

**Type:** System.Int32

### _boss_armor_id

```csharp
private const int _boss_armor_id = 300038
```

#### Field Value

**Type:** System.Int32

### _boss_gift_id

```csharp
public const int _boss_gift_id = 400038
```

#### Field Value

**Type:** System.Int32

### _boss_weapon_id

```csharp
private const int _boss_weapon_id = 200038
```

#### Field Value

**Type:** System.Int32

### _currentPhase

```csharp
private BossBird.Phase _currentPhase
```

#### Field Value

**Type:** Global.BossBird.Phase

### _laserDmgMax

```csharp
private const int _laserDmgMax = 14
```

#### Field Value

**Type:** System.Int32

### _laserDmgMin

```csharp
private const int _laserDmgMin = 8
```

#### Field Value

**Type:** System.Int32

### _scaleDmgMax

```csharp
private const int _scaleDmgMax = 15
```

#### Field Value

**Type:** System.Int32

### _scaleDmgMin

```csharp
private const int _scaleDmgMin = 10
```

#### Field Value

**Type:** System.Int32

### _unit

```csharp
private ChildCreatureUnit _unit
```

#### Field Value

**Type:** Global.ChildCreatureUnit

### activateState

```csharp
private bool activateState
```

#### Field Value

**Type:** System.Boolean

### aliveEggs

```csharp
private List<BossEggBase> aliveEggs
```

#### Field Value

**Type:** System.Collections.Generic.List{BossEggBase}

### attackDelayMax

```csharp
private const float attackDelayMax = 6
```

#### Field Value

**Type:** System.Single

### attackDelayMin

```csharp
private const float attackDelayMin = 4
```

#### Field Value

**Type:** System.Single

### attackType

```csharp
private RwbpType attackType
```

#### Field Value

**Type:** Global.RwbpType

### attracted

```csharp
private List<WorkerModel> attracted
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### attractEffect

```csharp
public const string attractEffect = "Effect/Creature/BossBird/Particle/BossBirdAttractEffect"
```

#### Field Value

**Type:** System.String

### attractPatternProb

```csharp
private const int attractPatternProb = 30
```

#### Field Value

**Type:** System.Int32

### bigBird

```csharp
private BigBird bigBird
```

#### Field Value

**Type:** Global.BigBird

### bigEgg

```csharp
private BossEggBase bigEgg
```

#### Field Value

**Type:** Global.BossEggBase

### birdControl

```csharp
private List<IBirdControl> birdControl
```

#### Field Value

**Type:** System.Collections.Generic.List{IBirdControl}

### bitePatternProb

```csharp
private const int bitePatternProb = 10
```

#### Field Value

**Type:** System.Int32

### biteType

```csharp
private RwbpType biteType
```

#### Field Value

**Type:** Global.RwbpType

### currentAttackType

```csharp
private BossBird.AttackType currentAttackType
```

#### Field Value

**Type:** Global.BossBird.AttackType

### currentForcelyTeleportTarget

```csharp
private BossEggBase currentForcelyTeleportTarget
```

#### Field Value

**Type:** Global.BossEggBase

### currentTeleportDest

```csharp
private MapNode currentTeleportDest
```

#### Field Value

**Type:** Global.MapNode

### defaultAmbience

```csharp
private SoundEffectPlayer defaultAmbience
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### escapedCreatures

```csharp
private List<CreatureBase> escapedCreatures
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureBase}

### eventScript

```csharp
private BossBirdEvent eventScript
```

#### Field Value

**Type:** Global.BossBirdEvent

### forcelyTeleport

```csharp
private bool forcelyTeleport
```

#### Field Value

**Type:** System.Boolean

### forcelyTeleportDelayMin

```csharp
private const float forcelyTeleportDelayMin = 10
```

#### Field Value

**Type:** System.Single

### forcelyTeleportReady

```csharp
private bool forcelyTeleportReady
```

#### Field Value

**Type:** System.Boolean

### forcelyTeleportTimer

```csharp
private Timer forcelyTeleportTimer
```

#### Field Value

**Type:** Global.Timer

### forcelyTteleportDelayMax

```csharp
private const float forcelyTteleportDelayMax = 15
```

#### Field Value

**Type:** System.Single

### gateWay

```csharp
private BossGateWay gateWay
```

#### Field Value

**Type:** Global.BossGateWay

### gatewayNode

```csharp
private MapNode gatewayNode
```

#### Field Value

**Type:** Global.MapNode

### isEscaped

```csharp
private bool isEscaped
```

#### Field Value

**Type:** System.Boolean

### isNarration

```csharp
private bool isNarration
```

#### Field Value

**Type:** System.Boolean

### isTeleporting

```csharp
private bool isTeleporting
```

#### Field Value

**Type:** System.Boolean

### laserArriveSoundPlayed

```csharp
private bool laserArriveSoundPlayed
```

#### Field Value

**Type:** System.Boolean

### LaserCount

```csharp
public const int LaserCount = 26
```

#### Field Value

**Type:** System.Int32

### laserExplode

```csharp
public const string laserExplode = "Effect/Creature/BossBird/Particle/ExplodeEffect"
```

#### Field Value

**Type:** System.String

### laserPatternProb

```csharp
private const int laserPatternProb = 35
```

#### Field Value

**Type:** System.Int32

### laserType

```csharp
private RwbpType laserType
```

#### Field Value

**Type:** Global.RwbpType

### laserUnitExplodeRad

```csharp
private const float laserUnitExplodeRad = 2
```

#### Field Value

**Type:** System.Single

### longBird

```csharp
private LongBird longBird
```

#### Field Value

**Type:** Global.LongBird

### longEgg

```csharp
private BossEggBase longEgg
```

#### Field Value

**Type:** Global.BossEggBase

### meleeHit_1_EffectSrc

```csharp
public const string meleeHit_1_EffectSrc = "Effect/Creature/BossBird/Particle/BossBirdMeleeHit"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Claw_LeftEffectSrc

```csharp
public const string meleeHit_2_Claw_LeftEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectLeft"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Claw_RightEffectSrc

```csharp
public const string meleeHit_2_Claw_RightEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectRight"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Grep_LeftEffectSrc

```csharp
public const string meleeHit_2_Grep_LeftEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectLeft"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Grep_RightEffectSrc

```csharp
public const string meleeHit_2_Grep_RightEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectRight"
```

#### Field Value

**Type:** System.String

### normalAttackReady

```csharp
private bool normalAttackReady
```

#### Field Value

**Type:** System.Boolean

### normalAttackTimer

```csharp
private Timer normalAttackTimer
```

#### Field Value

**Type:** Global.Timer

### notArrived

```csharp
private List<IBirdControl> notArrived
```

#### Field Value

**Type:** System.Collections.Generic.List{IBirdControl}

### patternDelay

```csharp
private const float patternDelay = 15
```

#### Field Value

**Type:** System.Single

### patternReady

```csharp
private bool patternReady
```

#### Field Value

**Type:** System.Boolean

### scaleEffect

```csharp
public const string scaleEffect = "Effect/Creature/BossBird/Particle/ScaleEffect"
```

#### Field Value

**Type:** System.String

### scalePatternProb

```csharp
private const int scalePatternProb = 25
```

#### Field Value

**Type:** System.Int32

### scaleType

```csharp
private RwbpType scaleType
```

#### Field Value

**Type:** Global.RwbpType

### smallBird

```csharp
private SmallBird smallBird
```

#### Field Value

**Type:** Global.SmallBird

### smallEgg

```csharp
private BossEggBase smallEgg
```

#### Field Value

**Type:** Global.BossEggBase

### specialPatternTimer

```csharp
private Timer specialPatternTimer
```

#### Field Value

**Type:** Global.Timer

### teleportDelayMax

```csharp
private const float teleportDelayMax = 25
```

#### Field Value

**Type:** System.Single

### teleportDelayMin

```csharp
private const float teleportDelayMin = 15
```

#### Field Value

**Type:** System.Single

### teleportReady

```csharp
private bool teleportReady
```

#### Field Value

**Type:** System.Boolean

### teleportTimer

```csharp
private Timer teleportTimer
```

#### Field Value

**Type:** Global.Timer

### traitId

```csharp
private const long traitId = 100038
```

#### Field Value

**Type:** System.Int64

### ultDeadEffecSrc

```csharp
public const string ultDeadEffecSrc = "Effect/Creature/BossBird/Particle/BossBirdAgentDead"
```

#### Field Value

**Type:** System.String

### ultHandLeftSrc

```csharp
public const string ultHandLeftSrc = "Effect/Creature/BossBird/Particle/UltShock_Left"
```

#### Field Value

**Type:** System.String

### ultHandRightSrc

```csharp
public const string ultHandRightSrc = "Effect/Creature/BossBird/Particle/UltShcok_Right"
```

#### Field Value

**Type:** System.String

### ultShooted

```csharp
private bool ultShooted
```

#### Field Value

**Type:** System.Boolean

### ultShootEffectLeftSrc

```csharp
public const string ultShootEffectLeftSrc = "Effect/Creature/BossBird/Particle/GutShootEffectLeft"
```

#### Field Value

**Type:** System.String

### ultShootEffectRightSrc

```csharp
public const string ultShootEffectRightSrc = "Effect/Creature/BossBird/Particle/GutShootEffectRight"
```

#### Field Value

**Type:** System.String

### uniquePattern

```csharp
private Timer uniquePattern
```

#### Field Value

**Type:** Global.Timer

### uniquePatternCheckTime

```csharp
private const float uniquePatternCheckTime = 5
```

#### Field Value

**Type:** System.Single

### waitQueue

```csharp
private Queue<IBirdControl> waitQueue
```

#### Field Value

**Type:** System.Collections.Generic.Queue{IBirdControl}

## Properties

### animScript

```csharp
private BossBirdAnim animScript { get; }
```

#### Property Value

**Type:** Global.BossBirdAnim

### attackDelay

```csharp
private float attackDelay { get; }
```

#### Property Value

**Type:** System.Single

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### attractCnt

```csharp
private static int attractCnt { get; }
```

#### Property Value

**Type:** System.Int32

### BigEggModel

```csharp
public EventCreatureModel BigEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### biteDmg

```csharp
private static int biteDmg { get; }
```

#### Property Value

**Type:** System.Int32

### currentPhase

```csharp
public BossBird.Phase currentPhase { get; set; }
```

#### Property Value

**Type:** Global.BossBird.Phase

### forcelyTeleportDelay

```csharp
private float forcelyTeleportDelay { get; }
```

#### Property Value

**Type:** System.Single

### GateWayModel

```csharp
public EventCreatureModel GateWayModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### laserDmg

```csharp
private static int laserDmg { get; }
```

#### Property Value

**Type:** System.Int32

### LongEggModel

```csharp
public EventCreatureModel LongEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### Model

```csharp
private ChildCreatureModel Model { get; }
```

#### Property Value

**Type:** Global.ChildCreatureModel

### scaleDmg

```csharp
private static int scaleDmg { get; }
```

#### Property Value

**Type:** System.Int32

### SmallEggModel

```csharp
public EventCreatureModel SmallEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### teleportDelay

```csharp
private float teleportDelay { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AddAgentsTrait()

```csharp
private void AddAgentsTrait()
```

### AfterAppearNarration()

```csharp
private void AfterAppearNarration()
```

### AfterEggBreakNarration()

```csharp
private void AfterEggBreakNarration()
```

### AttractCastingSuccess()

```csharp
private void AttractCastingSuccess()
```

### AttractPattern()

```csharp
public void AttractPattern()
```

### BiteCastingSuccess()

```csharp
private void BiteCastingSuccess()
```

### BitePattern()

```csharp
public void BitePattern()
```

### CancelNormalAttack()

```csharp
public void CancelNormalAttack()
```

### CancelPatternAttack()

```csharp
public void CancelPatternAttack()
```

### CheckCreatureUnitState()

```csharp
private void CheckCreatureUnitState()
```

### CheckTwilight()

```csharp
private bool CheckTwilight()
```

#### Returns

**Type:** System.Boolean

### DeleteSound(SoundEffectPlayer)

```csharp
public void DeleteSound(SoundEffectPlayer sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `Global.SoundEffectPlayer` |  |

### EndNormalAttack()

```csharp
public void EndNormalAttack()
```

### EndPatternAttack()

```csharp
public void EndPatternAttack()
```

### EndTeleport()

```csharp
public void EndTeleport()
```

### EndUltShoot()

```csharp
public void EndUltShoot()
```

### EscapeInit()

```csharp
private void EscapeInit()
```

### FadeOutSound()

```csharp
public void FadeOutSound()
```

### GetAttackTarget()

```csharp
public List<UnitModel> GetAttackTarget()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetAttackType()

```csharp
private BossBird.AttackType GetAttackType()
```

#### Returns

**Type:** Global.BossBird.AttackType

### GetCurrentAttackType()

```csharp
public BossBird.AttackType GetCurrentAttackType()
```

#### Returns

**Type:** Global.BossBird.AttackType

### GetDirectionTarget()

```csharp
public List<UnitModel> GetDirectionTarget()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetDirectionTarget(List<UnitModel>, float, float)

```csharp
public List<UnitModel> GetDirectionTarget(List<UnitModel> targets, float max_dist, float min_dist)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `max_dist` | `System.Single` |  |
| `min_dist` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetName()

```csharp
public override string GetName()
```

#### Returns

**Type:** System.String

### GetNarrationKeyByEnum(NarrationState)

```csharp
public static string GetNarrationKeyByEnum(BossBird.NarrationState nar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nar` | `Global.BossBird.NarrationState` |  |

#### Returns

**Type:** System.String

### GetNarrationState(string)

```csharp
public static BossBird.NarrationState GetNarrationState(string state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.String` |  |

#### Returns

**Type:** Global.BossBird.NarrationState

### GetParam(string)

```csharp
public CreatureStaticData.ParameterData GetParam(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetParamData(string)

```csharp
public string GetParamData(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetRangeTarget(Vector3, float)

```csharp
public List<UnitModel> GetRangeTarget(Vector3 pos, float half_Range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `half_Range` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveMeleeDamage()

```csharp
public void GiveMeleeDamage()
```

### InvokeForceTeleport()

```csharp
private void InvokeForceTeleport()
```

### InvokeNormalAttack()

```csharp
private void InvokeNormalAttack()
```

### InvokePatternAttack()

```csharp
private void InvokePatternAttack()
```

### InvokeTeleport()

```csharp
private void InvokeTeleport()
```

### MakeBirdConcentrationGate()

```csharp
public void MakeBirdConcentrationGate()
```

### MakeBirdObjects()

```csharp
private void MakeBirdObjects()
```

### MakeMovementRandom()

```csharp
public void MakeMovementRandom()
```

### MakeMovementToEgg(BossEggBase)

```csharp
public void MakeMovementToEgg(BossEggBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossEggBase` |  |

### MakeSound(string)

```csharp
public override SoundEffectPlayer MakeSound(string src)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnAllBirdArrived()

```csharp
private void OnAllBirdArrived()
```

### OnBirdArrived(IBirdControl)

```csharp
public void OnBirdArrived(IBirdControl bird)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bird` | `Global.IBirdControl` |  |

### OnBirdArrivedEndNarration()

```csharp
private void OnBirdArrivedEndNarration()
```

### OnBirdArrivedStartNarration()

```csharp
private void OnBirdArrivedStartNarration()
```

### OnBirdEscape(LongBird, SmallBird, BigBird)

```csharp
public void OnBirdEscape(LongBird longBird, SmallBird small, BigBird big)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `small` | `Global.SmallBird` |  |
| `big` | `Global.BigBird` |  |

### OnCannotUsePlaySpeedSetting(int)

```csharp
public void OnCannotUsePlaySpeedSetting(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnCastingEnd()

```csharp
public void OnCastingEnd()
```

### OnEggBreakDown(BossEggBase)

```csharp
public void OnEggBreakDown(BossEggBase eggScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnEggHalfDamage(BossEggBase)

```csharp
public void OnEggHalfDamage(BossEggBase eggScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGateWaySuppressed()

```csharp
public void OnGateWaySuppressed()
```

### OnLaserParticleArrived(LaserAttackTargetData)

```csharp
public void OnLaserParticleArrived(BossBird.LaserAttackTargetData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBird.LaserAttackTargetData` |  |

### OnSetPhase(Phase, bool)

```csharp
private void OnSetPhase(BossBird.Phase p, bool isDifferentWithPrevious)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Global.BossBird.Phase` |  |
| `isDifferentWithPrevious` | `System.Boolean` |  |

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnSuppressed()

```csharp
public override void OnSuppressed()
```

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkerWakeUp(WorkerModel)

```csharp
public void OnWorkerWakeUp(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OpenBossBirdCollection()

```csharp
public void OpenBossBirdCollection()
```

### ParamInit()

```csharp
public override void ParamInit()
```

### PrevTeleport(MapNode)

```csharp
public void PrevTeleport(MapNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### ScaleCastingSuccess()

```csharp
private void ScaleCastingSuccess()
```

### ScalePattern()

```csharp
public void ScalePattern()
```

### SetBirds(LongBird, SmallBird, BigBird)

```csharp
public void SetBirds(LongBird longBird, SmallBird smallBird, BigBird bigBird)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `smallBird` | `Global.SmallBird` |  |
| `bigBird` | `Global.BigBird` |  |

### SetCastingSlider(Slider)

```csharp
public override bool SetCastingSlider(Slider castingSlider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetCreatureActivateState(bool)

```csharp
public void SetCreatureActivateState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetModel(CreatureModel)

```csharp
public override void SetModel(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SetPassageAlpha(bool)

```csharp
private void SetPassageAlpha(bool isDark)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isDark` | `System.Boolean` |  |

### StartBirdMoveToNode(MapNode)

```csharp
private void StartBirdMoveToNode(MapNode dest)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dest` | `Global.MapNode` |  |

### StartMeleeAttack()

```csharp
public void StartMeleeAttack()
```

### StartRangeAttack()

```csharp
public void StartRangeAttack()
```

### StartUltShoot(MapNode)

```csharp
private void StartUltShoot(MapNode destNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `destNode` | `Global.MapNode` |  |

### StopMovement()

```csharp
public void StopMovement()
```

### TakeUltDamage()

```csharp
public void TakeUltDamage()
```

### Teleport()

```csharp
public void Teleport()
```

### TryMakeEquip(int)

```csharp
private void TryMakeEquip(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### TryMakeEquipments()

```csharp
private void TryMakeEquipments()
```

### WakeUpWorker(WorkerModel)

```csharp
public void WakeUpWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
