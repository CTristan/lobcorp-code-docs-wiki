---
uid: Global.FireBird
canonical_path: /api/Global/IOBserver/FireBird
---

# Class FireBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FireBird : CreatureBase, IObserver
```

The Firebird.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → FireBird

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FireBird()

```csharp
public FireBird()
```

## Fields

### _animScript

```csharp
private FireBirdAnim _animScript
```
#INC


#### Field Value

**Type:** Global.FireBirdAnim

### _ARRIVE_RANGE

```csharp
private const float _ARRIVE_RANGE = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _ATTACK_DMG_MAX

```csharp
private const int _ATTACK_DMG_MAX = 110
```
#INC


#### Field Value

**Type:** System.Int32

### _ATTACK_DMG_MIN

```csharp
private const int _ATTACK_DMG_MIN = 90
```
#INC


#### Field Value

**Type:** System.Int32

### _ATTACK_DMG_RANGE

```csharp
private const float _ATTACK_DMG_RANGE = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _ATTACK_DMG_TYPE

```csharp
private const RwbpType _ATTACK_DMG_TYPE = W
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _comeBackTimeMax

```csharp
private const float _comeBackTimeMax = 90
```
#INC


#### Field Value

**Type:** System.Single

### _comeBackTimeMin

```csharp
private const float _comeBackTimeMin = 45
```
#INC


#### Field Value

**Type:** System.Single

### _EQUIPMENT_ID

```csharp
private const int _EQUIPMENT_ID = 200061
```
#INC


#### Field Value

**Type:** System.Int32

### _FILTER_ALPHA

```csharp
private readonly float[] _FILTER_ALPHA
```
#INC


#### Field Value

**Type:** System.Single[]

### _FILTER_NAME

```csharp
private const string _FILTER_NAME = "FireBirdBurningFilter"
```
#INC


#### Field Value

**Type:** System.String

### _FILTER_SRC

```csharp
private const string _FILTER_SRC = "Sprites/CreatureSprite/FireBird/PassageFilter"
```
#INC


#### Field Value

**Type:** System.String

### _HEAL_CONDITION_QLIPHOTH

```csharp
private const int _HEAL_CONDITION_QLIPHOTH = 1
```
#INC


#### Field Value

**Type:** System.Int32

### _HEAL_HP_CONDITION

```csharp
private const float _HEAL_HP_CONDITION = 0.2
```
#INC


#### Field Value

**Type:** System.Single

### _MOVEMENT_ATTACK

```csharp
private const float _MOVEMENT_ATTACK = 20
```
#INC


#### Field Value

**Type:** System.Single

### _PASSAGE_DMG_MAX

```csharp
private const int _PASSAGE_DMG_MAX = 5
```
#INC


#### Field Value

**Type:** System.Int32

### _PASSAGE_DMG_MIN

```csharp
private const int _PASSAGE_DMG_MIN = 5
```
#INC


#### Field Value

**Type:** System.Int32

### _PASSAGE_DMG_TYPE

```csharp
private const RwbpType _PASSAGE_DMG_TYPE = R
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _phase

```csharp
private FireBird.Phase _phase
```

#### Field Value

**Type:** Global.FireBird.Phase

### _QLIPHOTH_MAX

```csharp
private const int _QLIPHOTH_MAX = 3
```
#INC


#### Field Value

**Type:** System.Int32

### _RECOGNIZE_RANGE

```csharp
private const float _RECOGNIZE_RANGE = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMax

```csharp
private const float _skillCoolTimeMax = 10
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMin

```csharp
private const float _skillCoolTimeMin = 8
```
#INC


#### Field Value

**Type:** System.Single

### _SUB_PROB_NORM

```csharp
private const float _SUB_PROB_NORM = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _TREE_SRC

```csharp
private const string _TREE_SRC = "Unit/ETC/FireBirdTree"
```
#INC


#### Field Value

**Type:** System.String

### _WORK_DMG_RATIO

```csharp
private readonly float[] _WORK_DMG_RATIO
```
#INC


#### Field Value

**Type:** System.Single[]

### annoyed

```csharp
private bool annoyed
```
#INC


#### Field Value

**Type:** System.Boolean

### burningPassage

```csharp
private FireBird.BurningPassage burningPassage
```

#### Field Value

**Type:** Global.FireBird.BurningPassage

### comeBackTimer

```csharp
private Timer comeBackTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### damaged

```csharp
private List<UnitModel> damaged
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### healTarget

```csharp
private WorkerModel healTarget
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### isSuppressed

```csharp
private bool isSuppressed
```
#INC


#### Field Value

**Type:** System.Boolean

### moveTarget

```csharp
private WorkerModel moveTarget
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### oldPassage

```csharp
private PassageObjectModel oldPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### skillCoolTimer

```csharp
private Timer skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### speedUp

```csharp
private bool speedUp
```
#INC


#### Field Value

**Type:** System.Boolean

### targetNode

```csharp
private MapNode targetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### tree

```csharp
private GameObject tree
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### animScript

```csharp
public FireBirdAnim animScript { get; }
```

#### Property Value

**Type:** Global.FireBirdAnim

### AttackDmg

```csharp
private static DamageInfo AttackDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### ComeBackTime

```csharp
private static float ComeBackTime { get; }
```

#### Property Value

**Type:** System.Single

### Filter

```csharp
private IsolateFilter Filter { get; }
```

#### Property Value

**Type:** Global.IsolateFilter

### PassageDmg

```csharp
public static DamageInfo PassageDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### SkillCoolTime

```csharp
private static float SkillCoolTime { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### AddBurningPassage(PassageObjectModel)

```csharp
private void AddBurningPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddedQliphothCounter()

```csharp
public override void AddedQliphothCounter()
```
#INC


### AddQliphothCounter()

```csharp
private void AddQliphothCounter()
```
#INC


### AttackDamage(UnitModel)

```csharp
private void AttackDamage(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### AttackEnd()

```csharp
private void AttackEnd()
```
#INC


### AttackStart(UnitDirection)

```csharp
private void AttackStart(UnitDirection dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |

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

### CheckHeal(UseSkill)

```csharp
private bool CheckHeal(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### CheckMoveCondition(WorkerModel)

```csharp
private bool CheckMoveCondition(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### CheckPassage()

```csharp
private void CheckPassage()
```
#INC


### Escape()

```csharp
public override void Escape()
```
#INC


### FixedUpdate_Attacking()

```csharp
private void FixedUpdate_Attacking()
```
#INC


### FixedUpdate_ComeBack()

```csharp
private void FixedUpdate_ComeBack()
```
#INC


### FixedUpdate_Default()

```csharp
private void FixedUpdate_Default()
```
#INC


### GetDamageMultiplierInWork(UseSkill)

```csharp
public override float GetDamageMultiplierInWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Single

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

### GetTargetInAll()

```csharp
private WorkerModel GetTargetInAll()
```
#INC


#### Returns

**Type:** Global.WorkerModel

### GetTargetInSefira(Sefira)

```csharp
private WorkerModel GetTargetInSefira(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.WorkerModel

### GetTargets(float, bool)

```csharp
public List<UnitModel> GetTargets(float range, bool needDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetWorkersInAll()

```csharp
private List<WorkerModel> GetWorkersInAll()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetWorkersInSefira(Sefira)

```csharp
private List<WorkerModel> GetWorkersInSefira(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### HealStart(AgentModel)

```csharp
private void HealStart(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

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

### IsSuppressable()

```csharp
public override bool IsSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeMovement(bool)

```csharp
private void MakeMovement(bool init = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `init` | `System.Boolean` |  |

### MakeMovement_Back()

```csharp
private void MakeMovement_Back()
```
#INC


### OnCastEnd()

```csharp
public void OnCastEnd()
```
#INC


### OnDelayEnd()

```csharp
public void OnDelayEnd()
```
#INC


### OnFinishWork(UseSkill)

```csharp
public override void OnFinishWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnHeal()

```csharp
public void OnHeal()
```
#INC


### OnHealEnd()

```csharp
public void OnHealEnd()
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


### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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


### OnSuppressed()

```csharp
public override void OnSuppressed()
```
#INC


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

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### Present()

```csharp
private void Present()
```
#INC


### ReducedQliphothCounter()

```csharp
public override void ReducedQliphothCounter()
```
#INC


### RemoveBurningPassage()

```csharp
private void RemoveBurningPassage()
```
#INC


### RoomSpriteInit()

```csharp
public override void RoomSpriteInit()
```
#INC


### SetFilterAlpha()

```csharp
private void SetFilterAlpha()
```
#INC


### Shoot()

```csharp
private void Shoot()
```
#INC


### SpeedDown()

```csharp
private void SpeedDown()
```
#INC


### SpeedUp()

```csharp
private void SpeedUp()
```
#INC


### StopMovement()

```csharp
private void StopMovement()
```
#INC


### SubQliphothCounter()

```csharp
private void SubQliphothCounter()
```
#INC


### TreeOff()

```csharp
private void TreeOff()
```
#INC


### TreeOn()

```csharp
private void TreeOn()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

