---
uid: Global.BigBird
canonical_path: /api/Global/Misc/BigBird
---

# Class BigBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBird : BirdCreatureBase, IBirdControl, IObserver
```

Big Bird. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [BirdCreatureBase](/api/Global/Misc/BirdCreatureBase) → BigBird

## Implements
[IBirdControl](/api/Global/Control/IBirdControl), [IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BigBird()

```csharp
public BigBird()
```

## Fields

### _agentDeadSceneHpConditionRatio

```csharp
private const float _agentDeadSceneHpConditionRatio = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _animScript

```csharp
private BigBirdAnim _animScript
```
#INC


#### Field Value

**Type:** Global.BigBirdAnim

### _attractCoolTimeMax

```csharp
private const float _attractCoolTimeMax = 12
```
#INC


#### Field Value

**Type:** System.Single

### _attractCoolTimeMin

```csharp
private const float _attractCoolTimeMin = 10
```
#INC


#### Field Value

**Type:** System.Single

### _attractInitTimeMax

```csharp
private const float _attractInitTimeMax = 7
```
#INC


#### Field Value

**Type:** System.Single

### _attractInitTimeMin

```csharp
private const float _attractInitTimeMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _attractOfficerProb

```csharp
private const int _attractOfficerProb = 40
```
#INC


#### Field Value

**Type:** System.Int32

### _attractTimeMax

```csharp
private const float _attractTimeMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### _attractTimeMin

```csharp
private const float _attractTimeMin = 3
```
#INC


#### Field Value

**Type:** System.Single

### _cameraSensingScale

```csharp
private const float _cameraSensingScale = 2
```
#INC


#### Field Value

**Type:** System.Single

### _deadSceneRangeMax

```csharp
private const float _deadSceneRangeMax = 2.75
```
#INC


#### Field Value

**Type:** System.Single

### _deadSceneRangeMin

```csharp
private const float _deadSceneRangeMin = 0
```
#INC


#### Field Value

**Type:** System.Single

### _defaultSpeed

```csharp
private const float _defaultSpeed = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _effect_boom

```csharp
private const string _effect_boom = "BigBirdAgentDeadEffect"
```
#INC


#### Field Value

**Type:** System.String

### _effect_src

```csharp
private const string _effect_src = "Effect/Creature/BigBird/"
```
#INC


#### Field Value

**Type:** System.String

### _escapeCoolTimeMax

```csharp
private const float _escapeCoolTimeMax = 40
```
#INC


#### Field Value

**Type:** System.Single

### _escapeCoolTimeMin

```csharp
private const float _escapeCoolTimeMin = 30
```
#INC


#### Field Value

**Type:** System.Single

### _motionDelayMax

```csharp
private const float _motionDelayMax = 1.2
```
#INC


#### Field Value

**Type:** System.Single

### _motionDelayMin

```csharp
private const float _motionDelayMin = 0.8
```
#INC


#### Field Value

**Type:** System.Single

### _officeDeadSceneProb

```csharp
private const int _officeDeadSceneProb = 30
```
#INC


#### Field Value

**Type:** System.Int32

### _otherBirdState

```csharp
private BossBird.OtherBirdState _otherBirdState
```
#INC


#### Field Value

**Type:** Global.BossBird.OtherBirdState

### _qliphothMax

```csharp
private const int _qliphothMax = 5
```
#INC


#### Field Value

**Type:** System.Int32

### _sound_attract

```csharp
private const string _sound_attract = "attract"
```
#INC


#### Field Value

**Type:** System.String

### _sound_dead1

```csharp
private const string _sound_dead1 = "dead1"
```
#INC


#### Field Value

**Type:** System.String

### _sound_dead2

```csharp
private const string _sound_dead2 = "dead2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_walk

```csharp
private const string _sound_walk = "walk"
```
#INC


#### Field Value

**Type:** System.String

### _specialSpeed

```csharp
private const float _specialSpeed = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### _subQliphothCondition

```csharp
private const int _subQliphothCondition = 5
```
#INC


#### Field Value

**Type:** System.Int32

### alive

```csharp
private List<OfficerModel> alive
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OfficerModel}

### attractCoolTimer

```csharp
private Timer attractCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attracted

```csharp
private List<WorkerModel> attracted
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### attractTimer

```csharp
private Timer attractTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### boss

```csharp
private BossBird boss
```
#INC


#### Field Value

**Type:** Global.BossBird

### boss_activated

```csharp
private bool boss_activated
```
#INC


#### Field Value

**Type:** System.Boolean

### cameraSensored

```csharp
private bool cameraSensored
```
#INC


#### Field Value

**Type:** System.Boolean

### dead

```csharp
private List<WorkerModel> dead
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### deadCnt

```csharp
private int deadCnt
```
#INC


#### Field Value

**Type:** System.Int32

### deadScene

```csharp
private Queue<WorkerModel> deadScene
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{WorkerModel}

### escapeCoolTimer

```csharp
private Timer escapeCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### motionDelayTimer

```csharp
private Timer motionDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### moveTarget

```csharp
private WorkerModel moveTarget
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### observingDanger

```csharp
private bool observingDanger
```
#INC


#### Field Value

**Type:** System.Boolean

### oldPassage

```csharp
private PassageObjectModel oldPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### prevSefira

```csharp
private Sefira prevSefira
```
#INC


#### Field Value

**Type:** Global.Sefira

### sensing

```csharp
private CreatureBase.SensingModule sensing
```

#### Field Value

**Type:** Global.CreatureBase.SensingModule

## Properties

### animScript

```csharp
public BigBirdAnim animScript { get; }
```

#### Property Value

**Type:** Global.BigBirdAnim

### attractCoolTime

```csharp
private static float attractCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### attractInitTime

```csharp
private static float attractInitTime { get; }
```

#### Property Value

**Type:** System.Single

### attractTime

```csharp
private static float attractTime { get; }
```

#### Property Value

**Type:** System.Single

### Boss

```csharp
public BossBird Boss { get; }
```

#### Property Value

**Type:** Global.BossBird

### Boss_Activated

```csharp
public bool Boss_Activated { get; }
```

#### Property Value

**Type:** System.Boolean

### escapeCoolTime

```csharp
private static float escapeCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### InstanceID

```csharp
public Guid InstanceID { get; private set; }
```
#INC


#### Property Value

**Type:** System.Guid

### motionDelay

```csharp
private static float motionDelay { get; }
```

#### Property Value

**Type:** System.Single

### OtherBirdState

```csharp
public BossBird.OtherBirdState OtherBirdState { get; }
```

#### Property Value

**Type:** Global.BossBird.OtherBirdState

### rect

```csharp
private RectTransform rect { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

### sensor

```csharp
private Camera sensor { get; }
```

#### Property Value

**Type:** UnityEngine.Camera

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC
#code-generated


### AgentDeadScene()

```csharp
private void AgentDeadScene()
```
#INC


### Attract(WorkerModel)

```csharp
private void Attract(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### CancelAttract()

```csharp
public void CancelAttract()
```
#INC


### CancelAttract(WorkerModel)

```csharp
public void CancelAttract(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### CancelCast()

```csharp
private void CancelCast()
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

### CheckAttractCondition(WorkerModel)

```csharp
private bool CheckAttractCondition(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### CheckDeadScene()

```csharp
private void CheckDeadScene()
```
#INC


### Escape()

```csharp
public override void Escape()
```
#INC


### GetDistance(WorkerModel)

```csharp
private float GetDistance(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Single

### GetMoveTarget()

```csharp
private WorkerModel GetMoveTarget()
```
#INC


#### Returns

**Type:** Global.WorkerModel

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

### GetWorkersInRange(float, float, bool)

```csharp
private List<WorkerModel> GetWorkersInRange(float rangeMax, float rangeMin = 0, bool hasDir = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetWorkersInSefira(Sefira, ref List<AgentModel>, ref List<OfficerModel>)

```csharp
private bool GetWorkersInSefira(Sefira sefira, ref List<AgentModel> agents, ref List<OfficerModel> officers)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |
| `agents` | `System.Collections.Generic.List{AgentModel}` |  |
| `officers` | `System.Collections.Generic.List{OfficerModel}` |  |

#### Returns

**Type:** System.Boolean

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsCasting()

```csharp
private bool IsCasting()
```
#INC


#### Returns

**Type:** System.Boolean

### IsHostile(WorkerModel)

```csharp
private bool IsHostile(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### IsInDeadScene()

```csharp
private bool IsInDeadScene()
```
#INC


#### Returns

**Type:** System.Boolean

### IsInRange(WorkerModel, float, float, bool)

```csharp
private bool IsInRange(WorkerModel target, float rangeMax, float rangeMin = 0, bool hasDir = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### IsSuppressable()

```csharp
public override bool IsSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeAgentDeadEffect(WorkerModel, string)

```csharp
private GameObject MakeAgentDeadEffect(WorkerModel worker, string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeMovement()

```csharp
private void MakeMovement()
```
#INC


### MakeMoveToGate(MapNode)

```csharp
public void MakeMoveToGate(MapNode dest)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dest` | `Global.MapNode` |  |

### MakeSefiraBrightly(Sefira)

```csharp
private void MakeSefiraBrightly(Sefira targetSefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetSefira` | `Global.Sefira` |  |

### MakeSefiraDarkly(Sefira)

```csharp
public void MakeSefiraDarkly(Sefira targetSefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetSefira` | `Global.Sefira` |  |

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

### MakeSound(string, float)

```csharp
public override SoundEffectPlayer MakeSound(string src, float vol)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MoveTargetable(WorkerModel)

```csharp
private bool MoveTargetable(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAgentAnimCalled(int)

```csharp
public void OnAgentAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnArrivedAndHide()

```csharp
public void OnArrivedAndHide()
```
#INC


### OnAttractSound()

```csharp
public void OnAttractSound()
```
#INC


### OnBossActivate()

```csharp
public void OnBossActivate()
```
#INC


### OnBossSuppressed()

```csharp
public void OnBossSuppressed()
```
#INC


### OnDeadSceneSound_1()

```csharp
public void OnDeadSceneSound_1()
```
#INC


### OnDeadSceneSound_2()

```csharp
public void OnDeadSceneSound_2()
```
#INC


### OnEndCast()

```csharp
public void OnEndCast()
```
#INC


### OnEndDeadScene()

```csharp
public void OnEndDeadScene()
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

### OnGateSuppressed()

```csharp
public void OnGateSuppressed()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnOpenCollectionWindow()

```csharp
public override bool OnOpenCollectionWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnReleaseWork(UseSkill)

```csharp
public override void OnReleaseWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReturn()

```csharp
public override void OnReturn()
```
#INC


### OnStageEnd()

```csharp
public override void OnStageEnd()
```
#INC


### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### OnStep()

```csharp
public void OnStep()
```
#INC


### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### SetBoss(BossBird)

```csharp
public void SetBoss(BossBird boss)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boss` | `Global.BossBird` |  |

### SetObserver(bool)

```csharp
private void SetObserver(bool active)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### StartCast()

```csharp
private void StartCast()
```
#INC


### StartDeadScene(WorkerModel)

```csharp
private void StartDeadScene(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### StopMovement()

```csharp
private void StopMovement()
```
#INC


### SuccessCast()

```csharp
private void SuccessCast()
```
#INC


### TryAttract(out WorkerModel)

```csharp
private bool TryAttract(out WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

