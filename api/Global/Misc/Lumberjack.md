---
uid: Global.Lumberjack
canonical_path: /api/Global/Misc/Lumberjack
---

# Class Lumberjack

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Lumberjack : CreatureBase
```

Warm-Hearted Woodsman.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → Lumberjack

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Lumberjack()

```csharp
public Lumberjack()
```

## Fields

### _animScript

```csharp
private LumberjackAnim _animScript
```
#INC


#### Field Value

**Type:** Global.LumberjackAnim

### _atkDmgRange

```csharp
private const float _atkDmgRange = 4.5
```
#INC


#### Field Value

**Type:** System.Single

### _attackDmgMax

```csharp
private const int _attackDmgMax = 10
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgMin

```csharp
private const int _attackDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Int32

### _attackRange

```csharp
private const float _attackRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### _defaultSpecialAtkProb

```csharp
private const int _defaultSpecialAtkProb = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _escapeTime

```csharp
private const float _escapeTime = 5
```
#INC


#### Field Value

**Type:** System.Single

### _filterReadyTime

```csharp
private static float _filterReadyTime
```
#INC


#### Field Value

**Type:** System.Single

### _filterTime

```csharp
private static float _filterTime
```
#INC


#### Field Value

**Type:** System.Single

### _healMax

```csharp
private const int _healMax = 35
```
#INC


#### Field Value

**Type:** System.Int32

### _healMin

```csharp
private const int _healMin = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _lootRange

```csharp
private const float _lootRange = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _motionDelayTime

```csharp
private const float _motionDelayTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### _qliphothMax

```csharp
private const int _qliphothMax = 1
```
#INC


#### Field Value

**Type:** System.Int32

### _recognizeRange

```csharp
private const float _recognizeRange = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillProbPerAttackStack

```csharp
private const int _skillProbPerAttackStack = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _smashDmgRange

```csharp
private const float _smashDmgRange = 5
```
#INC


#### Field Value

**Type:** System.Single

### _sound_atk1

```csharp
private const string _sound_atk1 = "atk1"
```
#INC


#### Field Value

**Type:** System.String

### _sound_atk2

```csharp
private const string _sound_atk2 = "atk2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_dead1

```csharp
public const string _sound_dead1 = "dead1"
```
#INC


#### Field Value

**Type:** System.String

### _sound_dead2

```csharp
public const string _sound_dead2 = "dead2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_default

```csharp
private const string _sound_default = "default"
```
#INC


#### Field Value

**Type:** System.String

### _sound_escape

```csharp
private const string _sound_escape = "escape"
```
#INC


#### Field Value

**Type:** System.String

### _sound_special

```csharp
public const string _sound_special = "special"
```
#INC


#### Field Value

**Type:** System.String

### _specialCoolTimeMax

```csharp
private const float _specialCoolTimeMax = 15
```
#INC


#### Field Value

**Type:** System.Single

### _specialCoolTimeMin

```csharp
private const float _specialCoolTimeMin = 8
```
#INC


#### Field Value

**Type:** System.Single

### _specialDmgMax

```csharp
private const int _specialDmgMax = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _specialDmgMin

```csharp
private const int _specialDmgMin = 3
```
#INC


#### Field Value

**Type:** System.Int32

### _specialDmgRange

```csharp
private const float _specialDmgRange = 4.5
```
#INC


#### Field Value

**Type:** System.Single

### _specialSmashMax

```csharp
private const int _specialSmashMax = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _specialSmashMin

```csharp
private const int _specialSmashMin = 15
```
#INC


#### Field Value

**Type:** System.Int32

### _temperanceCondition

```csharp
private const int _temperanceCondition = 3
```
#INC


#### Field Value

**Type:** System.Int32

### attackStack

```csharp
private int attackStack
```
#INC


#### Field Value

**Type:** System.Int32

### dead

```csharp
private WorkerModel dead
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### defaultSound

```csharp
private SoundEffectPlayer defaultSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### escapeTimer

```csharp
private Timer escapeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### filterReadyTimer

```csharp
private Timer filterReadyTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### filterTimer

```csharp
private Timer filterTimer
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

### specialCoolTimer

```csharp
private Timer specialCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### victim

```csharp
private AgentModel victim
```
#INC


#### Field Value

**Type:** Global.AgentModel

## Properties

### animScript

```csharp
public LumberjackAnim animScript { get; }
```

#### Property Value

**Type:** Global.LumberjackAnim

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### healRand

```csharp
private static int healRand { get; }
```

#### Property Value

**Type:** System.Int32

### specialCoolTime

```csharp
private static float specialCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### specialDmg

```csharp
private static int specialDmg { get; }
```

#### Property Value

**Type:** System.Int32

### specialSmash

```csharp
private static int specialSmash { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AttackStart(int)

```csharp
private void AttackStart(int pattern)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `System.Int32` |  |

### Escape()

```csharp
public override void Escape()
```
#INC


### GetDeads()

```csharp
private List<WorkerModel> GetDeads()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetDistance(UnitModel)

```csharp
private float GetDistance(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Single

### GetNearestInRange(float, bool)

```csharp
private UnitModel GetNearestInRange(float range, bool hasDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns

**Type:** Global.UnitModel

### GetSoundSrc(string)

```csharp
private string GetSoundSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetTargetsInRange(float, bool)

```csharp
private List<UnitModel> GetTargetsInRange(float range, bool hasDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### Heal()

```csharp
public void Heal()
```
#INC


### IsInRange(UnitModel, float, bool)

```csharp
private bool IsInRange(UnitModel target, float range, bool hasDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### KillAgentInRoom()

```csharp
public void KillAgentInRoom()
```
#INC


### Loot()

```csharp
public void Loot()
```
#INC


### LootStart()

```csharp
private void LootStart()
```
#INC


### MakeExplodeEffect(WorkerModel, float)

```csharp
public void MakeExplodeEffect(WorkerModel target, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

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

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAttackDamageTimeCalled()

```csharp
public void OnAttackDamageTimeCalled()
```
#INC


### OnAttackEnd(int)

```csharp
public void OnAttackEnd(int pattern)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `System.Int32` |  |

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnLootingEnd()

```csharp
public void OnLootingEnd()
```
#INC


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


### OnSpecialDamageTimeCalled()

```csharp
public void OnSpecialDamageTimeCalled()
```
#INC


### OnSpecialSmashTimeCalled()

```csharp
public void OnSpecialSmashTimeCalled()
```
#INC


### OnStageEnd()

```csharp
public override void OnStageEnd()
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

### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated


### RemoveDefaultSound()

```csharp
private void RemoveDefaultSound()
```
#INC


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

