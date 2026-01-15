---
uid: Global.BigBadWolf
canonical_path: /api/Global/IOBserver/BigBadWolf
---

# Class BigBadWolf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBadWolf : CreatureBase, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → BigBadWolf

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BigBadWolf()

```csharp
public BigBadWolf()
```

## Fields

### _activateEvent

```csharp
private bool _activateEvent
```

#### Field Value

**Type:** System.Boolean

### _castingGroggyTimer

```csharp
private Timer _castingGroggyTimer
```

#### Field Value

**Type:** Global.Timer

### _castingNode

```csharp
private MapNode _castingNode
```

#### Field Value

**Type:** Global.MapNode

### _currentApproachingTarget

```csharp
private UnitModel _currentApproachingTarget
```

#### Field Value

**Type:** Global.UnitModel

### _currentAttackType

```csharp
private BigBadWolf.WolfAttackType _currentAttackType
```

#### Field Value

**Type:** Global.BigBadWolf.WolfAttackType

### _currentMoveTargetMovable

```csharp
private MovableObjectNode _currentMoveTargetMovable
```

#### Field Value

**Type:** Global.MovableObjectNode

### _currentMoveTargetNode

```csharp
private MapNode _currentMoveTargetNode
```

#### Field Value

**Type:** Global.MapNode

### _defaultAttackRange

```csharp
private const float _defaultAttackRange = 4
```

#### Field Value

**Type:** System.Single

### _entryPassage

```csharp
private PassageObjectModel _entryPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### _filterDisplayTime

```csharp
private const float _filterDisplayTime = 20
```

#### Field Value

**Type:** System.Single

### _filterElapSave

```csharp
private float _filterElapSave
```

#### Field Value

**Type:** System.Single

### _filterTimer

```csharp
private Timer _filterTimer
```

#### Field Value

**Type:** Global.Timer

### _filterType

```csharp
private BigBadWolf.FilterType _filterType
```

#### Field Value

**Type:** Global.BigBadWolf.FilterType

### _getawayGroggyTimer

```csharp
private Timer _getawayGroggyTimer
```

#### Field Value

**Type:** Global.Timer

### _getaWayStdDamage

```csharp
private const float _getaWayStdDamage = 300
```

#### Field Value

**Type:** System.Single

### _groggyCasting

```csharp
private const float _groggyCasting = 3
```

#### Field Value

**Type:** System.Single

### _groggyTime

```csharp
private const float _groggyTime = 7.5
```

#### Field Value

**Type:** System.Single

### _howlingDamageMax

```csharp
private const int _howlingDamageMax = 20
```

#### Field Value

**Type:** System.Int32

### _howlingDamageMin

```csharp
private const int _howlingDamageMin = 15
```

#### Field Value

**Type:** System.Int32

### _howlingDelay

```csharp
private const float _howlingDelay = 20
```

#### Field Value

**Type:** System.Single

### _howlingDelayTimer

```csharp
private Timer _howlingDelayTimer
```

#### Field Value

**Type:** Global.Timer

### _initialHealthRate

```csharp
private const float _initialHealthRate = 0.8
```

#### Field Value

**Type:** System.Single

### _isApproaching

```csharp
private bool _isApproaching
```

#### Field Value

**Type:** System.Boolean

### _isAttacking

```csharp
private bool _isAttacking
```

#### Field Value

**Type:** System.Boolean

### _isMovingToSefira

```csharp
private bool _isMovingToSefira
```

#### Field Value

**Type:** System.Boolean

### _isRedHoodSuppressed

```csharp
private bool _isRedHoodSuppressed
```

#### Field Value

**Type:** System.Boolean

### _nextGetawaySefira

```csharp
private Sefira _nextGetawaySefira
```

#### Field Value

**Type:** Global.Sefira

### _normalFortitudeLevel

```csharp
private const int _normalFortitudeLevel = 3
```

#### Field Value

**Type:** System.Int32

### _qliphothMax

```csharp
private const int _qliphothMax = 2
```

#### Field Value

**Type:** System.Int32

### _qlipothSubCount

```csharp
private int _qlipothSubCount
```

#### Field Value

**Type:** System.Int32

### _radius

```csharp
private const float _radius = 2
```

#### Field Value

**Type:** System.Single

### _redHood

```csharp
private RedHood _redHood
```

#### Field Value

**Type:** Global.RedHood

### _redHoodWorker

```csharp
private AgentModel _redHoodWorker
```

#### Field Value

**Type:** Global.AgentModel

### _redMoonValue

```csharp
private const float _redMoonValue = 0.5
```

#### Field Value

**Type:** System.Single

### BiteSrc

```csharp
public const string BiteSrc = "Effect/Creature/BigBadWolf/Charge1-{0}"
```

#### Field Value

**Type:** System.String

### ChargeSrc

```csharp
public const string ChargeSrc = "Effect/Creature/BigBadWolf/Scratch{0}"
```

#### Field Value

**Type:** System.String

### CheckedUnit

```csharp
private List<UnitModel> CheckedUnit
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### damageModule

```csharp
private BigBadWolf.DamageCumlative damageModule
```

#### Field Value

**Type:** Global.BigBadWolf.DamageCumlative

### eatenWorker

```csharp
private List<Uncontrollable_WolfEaten> eatenWorker
```

#### Field Value

**Type:** System.Collections.Generic.List{Uncontrollable_WolfEaten}

### eatFilter_1

```csharp
private IsolateFilter eatFilter_1
```

#### Field Value

**Type:** Global.IsolateFilter

### eatFilter_2

```csharp
private IsolateFilter eatFilter_2
```

#### Field Value

**Type:** Global.IsolateFilter

### GiftId

```csharp
public const int GiftId = 1033
```

#### Field Value

**Type:** System.Int32

### SlashSrc

```csharp
public const string SlashSrc = "Effect/Creature/BigBadWolf/Slash"
```

#### Field Value

**Type:** System.String

### vomitFilter_1

```csharp
private IsolateFilter vomitFilter_1
```

#### Field Value

**Type:** Global.IsolateFilter

### vomitFilter_2

```csharp
private IsolateFilter vomitFilter_2
```

#### Field Value

**Type:** Global.IsolateFilter

## Properties

### _defaultHowlingDamage

```csharp
public DamageInfo _defaultHowlingDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### AnimScript

```csharp
public BigBadWolfAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.BigBadWolfAnim

### BiteDamage

```csharp
public DamageInfo BiteDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### ChargeDamage

```csharp
public DamageInfo ChargeDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### CurrentAttackType

```csharp
public BigBadWolf.WolfAttackType CurrentAttackType { get; }
```

#### Property Value

**Type:** Global.BigBadWolf.WolfAttackType

### CurrentPos

```csharp
private Vector3 CurrentPos { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### IsRedHoodExist

```csharp
private bool IsRedHoodExist { get; }
```

#### Property Value

**Type:** System.Boolean

### IsRedMoon

```csharp
private bool IsRedMoon { get; }
```

#### Property Value

**Type:** System.Boolean

### ScratchDamage

```csharp
public DamageInfo ScratchDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### SenseRadius

```csharp
private float SenseRadius { get; set; }
```

#### Property Value

**Type:** System.Single

### SenseRadiusDouble

```csharp
private float SenseRadiusDouble { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ActivateEatEvent(AgentModel)

```csharp
private void ActivateEatEvent(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```

### AddDefenseBuf(UnitModel, float, float)

```csharp
public void AddDefenseBuf(UnitModel target, float factor, float lifeTime = -1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `factor` | `System.Single` |  |
| `lifeTime` | `System.Single` |  |

### AddGift(AgentModel)

```csharp
public void AddGift(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Approach(UnitModel)

```csharp
private void Approach(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CanTakeDamage(UnitModel, DamageInfo)

```csharp
public override bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### CheckPassage()

```csharp
private void CheckPassage()
```

### CheckRange(UnitModel, float, bool)

```csharp
private bool CheckRange(UnitModel target, float range, bool ignoreDirection = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `ignoreDirection` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### FindRedHood()

```csharp
private void FindRedHood()
```

### Getaway()

```csharp
private void Getaway()
```

### GetCurrentStandingSefira()

```csharp
private Sefira GetCurrentStandingSefira()
```

#### Returns

**Type:** Global.Sefira

### GetDamagedTarget(List<UnitModel>, float, bool)

```csharp
private List<UnitModel> GetDamagedTarget(List<UnitModel> near, float range, bool ignoreDir = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |
| `range` | `System.Single` |  |
| `ignoreDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetDirection(UnitModel)

```csharp
private UnitDirection GetDirection(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.UnitDirection

### GetDistDouble(UnitModel)

```csharp
private float GetDistDouble(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Single

### GetDoubleValue(float)

```csharp
private float GetDoubleValue(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetNearTarget()

```csharp
private List<UnitModel> GetNearTarget()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetRadius()

```csharp
public override float GetRadius()
```

#### Returns

**Type:** System.Single

### GetSoundSrc(string)

```csharp
public string GetSoundSrc(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetTargetsInRange()

```csharp
private List<UnitModel> GetTargetsInRange()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### Howling()

```csharp
private void Howling()
```

### HowlingDamageToAgent(AgentModel)

```csharp
private void HowlingDamageToAgent(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### InitialEscapeAction()

```csharp
public void InitialEscapeAction()
```

### InitialEscapeArrived()

```csharp
public void InitialEscapeArrived()
```

### IsRedHood(UnitModel)

```csharp
private bool IsRedHood(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsRedHood(UnitModel, out RedHood)

```csharp
private bool IsRedHood(UnitModel target, out RedHood redHood)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `redHood` | `Global.RedHood` |  |

#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public override bool IsWorkable()
```

#### Returns

**Type:** System.Boolean

### Log(string)

```csharp
public static void Log(string log)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |

### MakeBiteEffect()

```csharp
public void MakeBiteEffect()
```

### MakeCastingAttackEffect(UnitModel)

```csharp
private void MakeCastingAttackEffect(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### MakeMovement(MapNode, OnCommandEnd)

```csharp
public void MakeMovement(MapNode targetNode, CreatureCommand.OnCommandEnd commandEnd = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `commandEnd` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeMovement(MovableObjectNode, OnCommandEnd)

```csharp
public void MakeMovement(MovableObjectNode movable, CreatureCommand.OnCommandEnd commandEnd = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |
| `commandEnd` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeScratchEffect()

```csharp
public void MakeScratchEffect()
```

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

### OnArriveGetaway()

```csharp
public void OnArriveGetaway()
```

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnCastingArrived()

```csharp
public void OnCastingArrived()
```

### OnCastingAttack()

```csharp
public void OnCastingAttack()
```

### OnCastingReady()

```csharp
public void OnCastingReady()
```

### OnDamage()

```csharp
public void OnDamage()
```

### OnDamageFilled()

```csharp
public void OnDamageFilled()
```

### OnEatAnimEnd()

```csharp
private void OnEatAnimEnd()
```

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFinishWork(UseSkill)

```csharp
public override void OnFinishWork(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnInit()

```csharp
public override void OnInit()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnReadyForEscape()

```csharp
public void OnReadyForEscape()
```

### OnRedHoodSuppressed()

```csharp
public void OnRedHoodSuppressed()
```

### OnReturn()

```csharp
public override void OnReturn()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnSuppressedByRedHood()

```csharp
public void OnSuppressedByRedHood()
```

### OnTakeDamage(UnitModel, DamageInfo, float)

```csharp
public override void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkClosed(UseSkill, int)

```csharp
public override void OnWorkClosed(UseSkill skill, int successCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |
| `successCount` | `System.Int32` |  |

### ParamInit()

```csharp
public override void ParamInit()
```

### ReadyForEscape()

```csharp
private void ReadyForEscape()
```

### Recover(float)

```csharp
private void Recover(float recoverValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `recoverValue` | `System.Single` |  |

### ResetQliphothCounter()

```csharp
public override void ResetQliphothCounter()
```

### RoomSpriteInit()

```csharp
public override void RoomSpriteInit()
```

### SetGetawaySefira()

```csharp
private void SetGetawaySefira()
```

### StartAttack(UnitModel)

```csharp
private void StartAttack(UnitModel mainTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.UnitModel` |  |

### StopMovement(bool)

```csharp
public void StopMovement(bool clearTarget = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clearTarget` | `System.Boolean` |  |

### UniqueEscape()

```csharp
public override void UniqueEscape()
```

### UniqueMoveControl()

```csharp
public override bool UniqueMoveControl()
```

#### Returns

**Type:** System.Boolean

### VomitEatenWorker()

```csharp
private void VomitEatenWorker()
```

### VomitStart()

```csharp
private void VomitStart()
```
