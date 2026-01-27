---
uid: Global.BugDusk
canonical_path: /api/Global/Misc/BugDusk
---

# Class BugDusk

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugDusk : BugOrdealCreature
```

Amber Dusk creature. See [BugDuskOrdeal](/api/Global/Misc/BugDuskOrdeal).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [BugOrdealCreature](/api/Global/Creature/BugOrdealCreature) → BugDusk

## Inherited Members
[_midnight](/api/Global/Creature/BugOrdealCreature#midnight), [_ordealScript](/api/Global/Creature/BugOrdealCreature#ordealscript), [_level](/api/Global/Creature/BugOrdealCreature#level), [_phase](/api/Global/Creature/BugOrdealCreature#phase), [_risk](/api/Global/Creature/BugOrdealCreature#risk), [_name](/api/Global/Creature/BugOrdealCreature#name), [GetOrdealName()](/api/Global/Creature/BugOrdealCreature#getordealname), [SetOrdeal(BugOrdeal, OrdealLevel, RiskLevel, string)](/api/Global/Creature/BugOrdealCreature#setordeal-bugordeal-ordeallevel-risklevel-string), [OnDie()](/api/Global/Creature/BugOrdealCreature#ondie), [SetMidnight(BugMidnight)](/api/Global/Creature/BugOrdealCreature#setmidnight-bugmidnight), [Midnight](/api/Global/Creature/BugOrdealCreature#midnight), [Risk](/api/Global/Creature/BugOrdealCreature#risk), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugDusk()

```csharp
public BugDusk()
```

## Fields

### _animScript

```csharp
private BugDuskAnim _animScript
```
#INC


#### Field Value

**Type:** Global.BugDuskAnim

### _appearanceDelayMax

```csharp
private const float _appearanceDelayMax = 1
```
#INC


#### Field Value

**Type:** System.Single

### _appearanceDelayMin

```csharp
private const float _appearanceDelayMin = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _appearDmgMax

```csharp
private const int _appearDmgMax = 40
```
#INC


#### Field Value

**Type:** System.Int32

### _appearDmgMin

```csharp
private const int _appearDmgMin = 30
```
#INC


#### Field Value

**Type:** System.Int32

### _appearDmgRange

```csharp
private const float _appearDmgRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### _attackDelayMax

```csharp
private const float _attackDelayMax = 2
```
#INC


#### Field Value

**Type:** System.Single

### _attackDelayMin

```csharp
private const float _attackDelayMin = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _attackDmgMax

```csharp
private const int _attackDmgMax = 70
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgMin

```csharp
private const int _attackDmgMin = 50
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgRangeMax

```csharp
private const float _attackDmgRangeMax = 4
```
#INC


#### Field Value

**Type:** System.Single

### _attackNode

```csharp
private MapNode _attackNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _attackRange

```csharp
private const float _attackRange = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### _beforeteleportTimeMax

```csharp
private const float _beforeteleportTimeMax = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _beforeteleportTimeMin

```csharp
private const float _beforeteleportTimeMin = 0.1
```
#INC


#### Field Value

**Type:** System.Single

### _childs

```csharp
private List<BugDawn> _childs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{BugDawn}

### _defaultSpeedMul

```csharp
private const float _defaultSpeedMul = 1
```
#INC


#### Field Value

**Type:** System.Single

### _slowDownHpCondition

```csharp
private const float _slowDownHpCondition = 0.05
```
#INC


#### Field Value

**Type:** System.Single

### _slowDownRatio

```csharp
private const float _slowDownRatio = 0.1
```
#INC


#### Field Value

**Type:** System.Single

### _slowDownTimeMax

```csharp
private const float _slowDownTimeMax = 2
```
#INC


#### Field Value

**Type:** System.Single

### _slowDownTimeMin

```csharp
private const float _slowDownTimeMin = 1
```
#INC


#### Field Value

**Type:** System.Single

### _soundDistDobule

```csharp
private const float _soundDistDobule = 30
```
#INC


#### Field Value

**Type:** System.Single

### _spawnDelayMax

```csharp
private const float _spawnDelayMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### _spawnDelayMin

```csharp
private const float _spawnDelayMin = 3
```
#INC


#### Field Value

**Type:** System.Single

### _spawnNode

```csharp
private MapNode _spawnNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _targetNode

```csharp
private MapNode _targetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _teleportDelayMax

```csharp
private const float _teleportDelayMax = 1
```
#INC


#### Field Value

**Type:** System.Single

### _teleportDelayMin

```csharp
private const float _teleportDelayMin = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### appearanceTimer

```csharp
private Timer appearanceTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attackDelayTimer

```csharp
private Timer attackDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### beforeteleportTimer

```csharp
private Timer beforeteleportTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### canSpawn

```csharp
private bool canSpawn
```
#INC


#### Field Value

**Type:** System.Boolean

### slowDownTimer

```csharp
private Timer slowDownTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### spawnDelayTimer

```csharp
private Timer spawnDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportDelayTimer

```csharp
private Timer teleportDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Properties

### animScript

```csharp
public BugDuskAnim animScript { get; }
```

#### Property Value

**Type:** Global.BugDuskAnim

### appearanceDelay

```csharp
private static float appearanceDelay { get; }
```

#### Property Value

**Type:** System.Single

### appearDmg

```csharp
private static int appearDmg { get; }
```

#### Property Value

**Type:** System.Int32

### attackDelay

```csharp
private static float attackDelay { get; }
```

#### Property Value

**Type:** System.Single

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### beforeteleportTime

```csharp
private static float beforeteleportTime { get; }
```

#### Property Value

**Type:** System.Single

### slowDownTime

```csharp
private static float slowDownTime { get; }
```

#### Property Value

**Type:** System.Single

### spawnDelay

```csharp
private static float spawnDelay { get; }
```

#### Property Value

**Type:** System.Single

### teleportDelay

```csharp
private static float teleportDelay { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### CanRangeInCamera()

```csharp
public bool CanRangeInCamera()
```
#INC


#### Returns

**Type:** System.Boolean

### CreateDaughter(int)

```csharp
public void CreateDaughter(int count)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### GetDistance(MovableObjectNode)

```csharp
private float GetDistance(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Single

### GetPassage()

```csharp
private PassageObjectModel GetPassage()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### GetTarget(float, bool)

```csharp
private List<UnitModel> GetTarget(float range, bool needDist = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDist` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveAttackDamage()

```csharp
public void GiveAttackDamage()
```
#INC


### Init()

```csharp
public void Init()
```
#INC


### IsHostile(UnitModel)

```csharp
private bool IsHostile(UnitModel u)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `u` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### MakeMovement()

```csharp
private void MakeMovement()
```
#INC


### NodeSelection(PassageObjectModel)

```csharp
private void NodeSelection(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnArrive()

```csharp
public void OnArrive()
```
#INC


### OnDisappear()

```csharp
public void OnDisappear()
```
#INC


### OnEndAttack()

```csharp
public void OnEndAttack()
```
#INC


### OnEndDigOut()

```csharp
public void OnEndDigOut()
```
#INC


### OnEndSpawn()

```csharp
public void OnEndSpawn()
```
#INC


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

### ProcessAttack()

```csharp
private void ProcessAttack()
```
#INC


### ProcessMoving()

```csharp
private void ProcessMoving()
```
#INC


### ReadyToTeleport(PassageObjectModel)

```csharp
public override void ReadyToTeleport(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### RecoverSpeed()

```csharp
private void RecoverSpeed()
```
#INC


### SetAttackNode(MapNode)

```csharp
public void SetAttackNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SlowDown()

```csharp
private void SlowDown()
```
#INC


### StartAttack()

```csharp
private void StartAttack()
```
#INC


### StartSpawn()

```csharp
private void StartSpawn()
```
#INC


### StartTeleport()

```csharp
public void StartTeleport()
```
#INC


### StopMovement()

```csharp
private void StopMovement()
```
#INC

