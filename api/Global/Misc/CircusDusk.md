---
uid: Global.CircusDusk
canonical_path: /api/Global/Misc/CircusDusk
---

# Class CircusDusk

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusDusk : CircusOrdealCreature
```

Crimson Dusk creature.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [CircusOrdealCreature](/api/Global/Creature/CircusOrdealCreature) → CircusDusk

## Inherited Members
[_ordealScript](/api/Global/Creature/CircusOrdealCreature#ordealscript), [_level](/api/Global/Creature/CircusOrdealCreature#level), [_risk](/api/Global/Creature/CircusOrdealCreature#risk), [_spawnDown](/api/Global/Creature/CircusOrdealCreature#spawndown), [_name](/api/Global/Creature/CircusOrdealCreature#name), [GetOrdealName()](/api/Global/Creature/CircusOrdealCreature#getordealname), [SetOrdeal(CircusOrdeal, OrdealLevel, RiskLevel, string)](/api/Global/Creature/CircusOrdealCreature#setordeal-circusordeal-ordeallevel-risklevel-string), [OnDie()](/api/Global/Creature/CircusOrdealCreature#ondie), [Risk](/api/Global/Creature/CircusOrdealCreature#risk), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CircusDusk()

```csharp
public CircusDusk()
```

## Fields

### _animScript

```csharp
private CircusDuskAnim _animScript
```
#INC


#### Field Value

**Type:** Global.CircusDuskAnim

### _attackDmgMax

```csharp
private const int _attackDmgMax = 14
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgMin

```csharp
private const int _attackDmgMin = 12
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgRange

```csharp
private const float _attackDmgRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### _attackRange

```csharp
private const float _attackRange = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### _defaultMoveProb

```csharp
private const int _defaultMoveProb = 10
```
#INC


#### Field Value

**Type:** System.Int32

### _defaultSpecialProb

```csharp
private const int _defaultSpecialProb = 30
```
#INC


#### Field Value

**Type:** System.Int32

### _groggyDelayMax

```csharp
private const float _groggyDelayMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _groggyDelayMin

```csharp
private const float _groggyDelayMin = 5
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

### _moveCoolTimeMax

```csharp
private const float _moveCoolTimeMax = 30
```
#INC


#### Field Value

**Type:** System.Single

### _moveCoolTimeMin

```csharp
private const float _moveCoolTimeMin = 20
```
#INC


#### Field Value

**Type:** System.Single

### _moveDmgDelayMax

```csharp
private const float _moveDmgDelayMax = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _moveDmgDelayMin

```csharp
private const float _moveDmgDelayMin = 1
```
#INC


#### Field Value

**Type:** System.Single

### _moveDmgMax

```csharp
private const int _moveDmgMax = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _moveDmgMin

```csharp
private const int _moveDmgMin = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _moveDmgRange

```csharp
private const float _moveDmgRange = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### _moveProbPerAttackStack

```csharp
private const int _moveProbPerAttackStack = 15
```
#INC


#### Field Value

**Type:** System.Int32

### _sound_Atk1

```csharp
private const string _sound_Atk1 = "Atk1"
```
#INC


#### Field Value

**Type:** System.String

### _sound_Atk2

```csharp
private const string _sound_Atk2 = "Atk2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_Bleed1

```csharp
private const string _sound_Bleed1 = "Bleed1"
```
#INC


#### Field Value

**Type:** System.String

### _sound_Bleed2

```csharp
private const string _sound_Bleed2 = "Bleed2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_Dead

```csharp
private const string _sound_Dead = "Dead"
```
#INC


#### Field Value

**Type:** System.String

### _sound_Move

```csharp
private const string _sound_Move = "Move"
```
#INC


#### Field Value

**Type:** System.String

### _specialCoolTimeMax

```csharp
private const float _specialCoolTimeMax = 12
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
private const int _specialDmgMax = 30
```
#INC


#### Field Value

**Type:** System.Int32

### _specialDmgMin

```csharp
private const int _specialDmgMin = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _specialProbPerAttackStack

```csharp
private const int _specialProbPerAttackStack = 15
```
#INC


#### Field Value

**Type:** System.Int32

### _targetPassage

```csharp
private PassageObjectModel _targetPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### attackDelays

```csharp
private List<CircusDusk.AttackDelay> attackDelays
```

#### Field Value

**Type:** System.Collections.Generic.List{CircusDusk.AttackDelay}

### attackDmgType

```csharp
private RwbpType attackDmgType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### attackStackForMove

```csharp
private int attackStackForMove
```
#INC


#### Field Value

**Type:** System.Int32

### attackStackForSpecial

```csharp
private int attackStackForSpecial
```
#INC


#### Field Value

**Type:** System.Int32

### motionDelayTimer

```csharp
private Timer motionDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### moveCoolTimer

```csharp
private Timer moveCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### moveDmgType

```csharp
private RwbpType moveDmgType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### specialCoolTimer

```csharp
private Timer specialCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### specialDmgType

```csharp
private RwbpType specialDmgType
```
#INC


#### Field Value

**Type:** Global.RwbpType

## Properties

### animScript

```csharp
public CircusDuskAnim animScript { get; }
```

#### Property Value

**Type:** Global.CircusDuskAnim

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### groggyDelay

```csharp
private static float groggyDelay { get; }
```

#### Property Value

**Type:** System.Single

### motionDelay

```csharp
private static float motionDelay { get; }
```

#### Property Value

**Type:** System.Single

### moveCoolTime

```csharp
private static float moveCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### moveDmg

```csharp
private static int moveDmg { get; }
```

#### Property Value

**Type:** System.Int32

### moveDmgDelay

```csharp
private static float moveDmgDelay { get; }
```

#### Property Value

**Type:** System.Single

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

## Methods

### AttackStart()

```csharp
private void AttackStart()
```
#INC


### CheckInElevator()

```csharp
private bool CheckInElevator()
```
#INC


#### Returns

**Type:** System.Boolean

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

### GetMoveProb()

```csharp
private int GetMoveProb()
```
#INC


#### Returns

**Type:** System.Int32

### GetNearest(float, bool)

```csharp
private UnitModel GetNearest(float range, bool needDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** Global.UnitModel

### GetPassage()

```csharp
private PassageObjectModel GetPassage()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### GetPassages()

```csharp
private List<PassageObjectModel> GetPassages()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{PassageObjectModel}

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

### GetSpecialProb()

```csharp
private int GetSpecialProb()
```
#INC


#### Returns

**Type:** System.Int32

### GetTargetDirection(UnitModel)

```csharp
private UnitDirection GetTargetDirection(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.UnitDirection

### GetTargetNode(PassageObjectModel)

```csharp
private MapNode GetTargetNode(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.MapNode

### GetTargets(float, bool)

```csharp
private List<UnitModel> GetTargets(float range, bool needDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveMoveDamage()

```csharp
private void GiveMoveDamage()
```
#INC


### IsAttacking()

```csharp
private bool IsAttacking()
```
#INC


#### Returns

**Type:** System.Boolean

### IsHostile(MovableObjectNode)

```csharp
private bool IsHostile(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float)

```csharp
private bool IsInRange(UnitModel target, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### IsInView(UnitModel)

```csharp
private bool IsInView(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsMoving()

```csharp
private bool IsMoving()
```
#INC


#### Returns

**Type:** System.Boolean

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

### OnArrive()

```csharp
public void OnArrive()
```
#INC


### OnAttackDamage()

```csharp
public void OnAttackDamage()
```
#INC


### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnBreakDown()

```csharp
public void OnBreakDown()
```
#INC


### OnDeadEffect()

```csharp
public void OnDeadEffect()
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

### OnSpecialDamage(bool)

```csharp
public void OnSpecialDamage(bool isFront)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isFront` | `System.Boolean` |  |

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

### StartMoveInPassage()

```csharp
private void StartMoveInPassage()
```
#INC


### StopMovement()

```csharp
private void StopMovement()
```
#INC

