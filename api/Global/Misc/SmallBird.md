---
uid: Global.SmallBird
canonical_path: /api/Global/Misc/SmallBird
---

# Class SmallBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SmallBird : BirdCreatureBase, IObserver, IBirdControl
```

Punishing Bird.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [BirdCreatureBase](/api/Global/Misc/BirdCreatureBase) → SmallBird

## Implements
[IObserver](/api/Global/Misc/IObserver), [IBirdControl](/api/Global/Control/IBirdControl)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SmallBird()

```csharp
public SmallBird()
```

## Fields

### _animScript

```csharp
private SmallBirdAnim _animScript
```
#INC


#### Field Value

**Type:** Global.SmallBirdAnim

### _otherBirdState

```csharp
private BossBird.OtherBirdState _otherBirdState
```
#INC


#### Field Value

**Type:** Global.BossBird.OtherBirdState

### attackPattern

```csharp
private SmallBird.AttackPattern attackPattern
```

#### Field Value

**Type:** Global.SmallBird.AttackPattern

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

### changeTargetFreq

```csharp
private const float changeTargetFreq = 3
```
#INC


#### Field Value

**Type:** System.Single

### changeTargetTimer

```csharp
private Timer changeTargetTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### currentAttackedDamage

```csharp
private float currentAttackedDamage
```
#INC


#### Field Value

**Type:** System.Single

### distanceRange

```csharp
private const float distanceRange = 1.7
```
#INC


#### Field Value

**Type:** System.Single

### elevatorBlockTime

```csharp
private const float elevatorBlockTime = 10
```
#INC


#### Field Value

**Type:** System.Single

### elevatorEscapeTimer

```csharp
private Timer elevatorEscapeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### encountered

```csharp
private List<WorkerModel> encountered
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### escapePattern

```csharp
private SmallBird.EscapePattern escapePattern
```

#### Field Value

**Type:** Global.SmallBird.EscapePattern

### escapeProb

```csharp
private const float escapeProb = 0.2
```
#INC


#### Field Value

**Type:** System.Single

### FactionCode

```csharp
private const string FactionCode = "11"
```
#INC


#### Field Value

**Type:** System.String

### isAttacking

```csharp
private bool isAttacking
```
#INC


#### Field Value

**Type:** System.Boolean

### madDmgMax

```csharp
private const float madDmgMax = 1200
```
#INC


#### Field Value

**Type:** System.Single

### madDmgMin

```csharp
private const float madDmgMin = 800
```
#INC


#### Field Value

**Type:** System.Single

### madMode

```csharp
private bool madMode
```
#INC


#### Field Value

**Type:** System.Boolean

### mentalHealMax

```csharp
private const float mentalHealMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### mentalHealMin

```csharp
private const float mentalHealMin = 3
```
#INC


#### Field Value

**Type:** System.Single

### oldTargetNode

```csharp
private MapNode oldTargetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### redDmgMax

```csharp
private const float redDmgMax = 1
```
#INC


#### Field Value

**Type:** System.Single

### redDmgMin

```csharp
private const float redDmgMin = 1
```
#INC


#### Field Value

**Type:** System.Single

### returnCommandActivated

```csharp
private bool returnCommandActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### targetAgent

```csharp
private AgentModel targetAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### totalDmgMax

```csharp
private const int totalDmgMax = 12
```
#INC


#### Field Value

**Type:** System.Int32

### totalDmgMin

```csharp
private const int totalDmgMin = 8
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### animScript

```csharp
public SmallBirdAnim animScript { get; }
```

#### Property Value

**Type:** Global.SmallBirdAnim

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

### madDmg

```csharp
private static float madDmg { get; }
```

#### Property Value

**Type:** System.Single

### mentalHeal

```csharp
private static float mentalHeal { get; }
```

#### Property Value

**Type:** System.Single

### OtherBirdState

```csharp
public BossBird.OtherBirdState OtherBirdState { get; }
```

#### Property Value

**Type:** Global.BossBird.OtherBirdState

### redDmg

```csharp
private static float redDmg { get; }
```

#### Property Value

**Type:** System.Single

### totalDmg

```csharp
private static int totalDmg { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
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

### CheckDistance()

```csharp
private bool CheckDistance()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckNearWorkerEncounting(out List<WorkerModel>)

```csharp
public List<AgentModel> CheckNearWorkerEncounting(out List<WorkerModel> nearWorkers)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nearWorkers` | `System.Collections.Generic.List{WorkerModel}` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### EndAttack()

```csharp
public void EndAttack()
```
#INC


### Escape()

```csharp
public override void Escape()
```
#INC


### GiveDamage()

```csharp
public void GiveDamage()
```
#INC


### HasUniqueFaction()

```csharp
public override bool HasUniqueFaction()
```
#INC
#code-generated


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

### IsSuppressable()

```csharp
public override bool IsSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### MadRelease()

```csharp
public void MadRelease()
```
#INC


### MakeExplodeEffect(UnitDirection, WorkerModel, float)

```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

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

### OnArrivedAndHide()

```csharp
public void OnArrivedAndHide()
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


### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnGateSuppressed()

```csharp
public void OnGateSuppressed()
```
#INC


### OnInit()

```csharp
public override void OnInit()
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

### OnReturn()

```csharp
public override void OnReturn()
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


### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### ReturnCommand()

```csharp
private void ReturnCommand()
```
#INC


### ReturnExecute()

```csharp
private void ReturnExecute()
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

### SetDirection(MovableObjectNode)

```csharp
private void SetDirection(MovableObjectNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |

### SetObserver(bool)

```csharp
public void SetObserver(bool activate)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `activate` | `System.Boolean` |  |

### SetPattern(EscapePattern)

```csharp
private void SetPattern(SmallBird.EscapePattern pattern)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `Global.SmallBird.EscapePattern` |  |

### StartAttackProcess(AttackPattern)

```csharp
private void StartAttackProcess(SmallBird.AttackPattern pattern)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `Global.SmallBird.AttackPattern` |  |

### StartMadMode(AgentModel)

```csharp
private void StartMadMode(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### StopMovement()

```csharp
private void StopMovement()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

