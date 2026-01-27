---
uid: Global.RedHood
canonical_path: /api/Global/IOBserver/RedHood
---

# Class RedHood

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHood : CreatureBase, IObserver
```

Little Red Riding Hooded Mercenary.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → RedHood

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RedHood()

```csharp
public RedHood()
```

## Fields

### _axeRespawn

```csharp
public const float _axeRespawn = 10
```
#INC


#### Field Value

**Type:** System.Single

### _changeTargetAsWolf

```csharp
private bool _changeTargetAsWolf
```
#INC


#### Field Value

**Type:** System.Boolean

### _chase

```csharp
private bool _chase
```
#INC


#### Field Value

**Type:** System.Boolean

### _currentAgentPrevWorkIsWolf

```csharp
private bool _currentAgentPrevWorkIsWolf
```
#INC


#### Field Value

**Type:** System.Boolean

### _currentAttackType

```csharp
private RedHood.AttackType _currentAttackType
```

#### Field Value

**Type:** Global.RedHood.AttackType

### _currentDestMovable

```csharp
private MovableObjectNode _currentDestMovable
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### _currentDestNode

```csharp
private MapNode _currentDestNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _currentMoveCommand

```csharp
private CreatureCommand.OnCommandEnd _currentMoveCommand
```
#INC


#### Field Value

**Type:** Global.CreatureCommand.OnCommandEnd

### _currentSpeedFactor

```csharp
private float _currentSpeedFactor
```
#INC


#### Field Value

**Type:** System.Single

### _entryPassage

```csharp
private PassageObjectModel _entryPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### _freezeReturnTimer

```csharp
private Timer _freezeReturnTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _initialSpeed

```csharp
private float _initialSpeed
```
#INC


#### Field Value

**Type:** System.Single

### _isApproaching

```csharp
private bool _isApproaching
```
#INC


#### Field Value

**Type:** System.Boolean

### _isAttacking

```csharp
private bool _isAttacking
```
#INC


#### Field Value

**Type:** System.Boolean

### _isAxeThrowed

```csharp
private bool _isAxeThrowed
```
#INC


#### Field Value

**Type:** System.Boolean

### _isWaiting

```csharp
private bool _isWaiting
```
#INC


#### Field Value

**Type:** System.Boolean

### _isWolfSuppressed

```csharp
private bool _isWolfSuppressed
```
#INC


#### Field Value

**Type:** System.Boolean

### _oldTargetNode

```csharp
private MapNode _oldTargetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _state

```csharp
private RedHood.RedHoodState _state
```

#### Field Value

**Type:** Global.RedHood.RedHoodState

### _target

```csharp
private UnitModel _target
```
#INC


#### Field Value

**Type:** Global.UnitModel

### _text_exclam

```csharp
private const string _text_exclam = "...!"
```
#INC


#### Field Value

**Type:** System.String

### _text_norm

```csharp
private const string _text_norm = "..."
```
#INC


#### Field Value

**Type:** System.String

### _throwingRespawnTimer

```csharp
private Timer _throwingRespawnTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _wolf

```csharp
private BigBadWolf _wolf
```
#INC


#### Field Value

**Type:** Global.BigBadWolf

### bufDictionary

```csharp
private Dictionary<UnitModel, RedHoodBleedBuf> bufDictionary
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{UnitModel,RedHoodBleedBuf}

### GunFire_Left

```csharp
private const string GunFire_Left = "Effect/Creature/RedHood/GunFireLeft"
```
#INC


#### Field Value

**Type:** System.String

### GunFire_Right

```csharp
private const string GunFire_Right = "Effect/Creature/RedHood/GunFireRight"
```
#INC


#### Field Value

**Type:** System.String

### MeleeAttackRange

```csharp
private const float MeleeAttackRange = 2
```
#INC


#### Field Value

**Type:** System.Single

### QliphothMax

```csharp
public const int QliphothMax = 3
```
#INC


#### Field Value

**Type:** System.Int32

### RequestCostFactor

```csharp
private const int RequestCostFactor = 40
```
#INC


#### Field Value

**Type:** System.Int32

### SlashSrc

```csharp
private const string SlashSrc = "Effect/Creature/RedHood/RedHoodSlash{0}_{1}"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### AnimScript

```csharp
private RedHoodAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.RedHoodAnim

### CurrentSpeedFactor

```csharp
public float CurrentSpeedFactor { get; }
```

#### Property Value

**Type:** System.Single

### IsBigBadWolfExist

```csharp
private bool IsBigBadWolfExist { get; }
```

#### Property Value

**Type:** System.Boolean

### MeleeDamage

```csharp
public DamageInfo MeleeDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### RangeDamage

```csharp
public DamageInfo RangeDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### target

```csharp
private UnitModel target { get; set; }
```

#### Property Value

**Type:** Global.UnitModel

### ThrowingDamage

```csharp
public DamageInfo ThrowingDamage { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### Approach()

```csharp
private void Approach()
```
#INC


### CanCastMovingShoot()

```csharp
public bool CanCastMovingShoot()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckRange(UnitModel, float, bool)

```csharp
private bool CheckRange(UnitModel target, float range, bool ignoreDirection = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `ignoreDirection` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### CheckTargetPassage()

```csharp
private bool CheckTargetPassage()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckWolf(List<UnitModel>)

```csharp
private void CheckWolf(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### ClearBuf()

```csharp
public void ClearBuf()
```
#INC


### EscapeMovementArrived()

```csharp
private void EscapeMovementArrived()
```
#INC


### EscapeUpdate()

```csharp
private void EscapeUpdate()
```
#INC


### FindBadWolf()

```csharp
private void FindBadWolf()
```
#INC


### GenThrowing()

```csharp
private void GenThrowing()
```
#INC


### GetBuf(UnitModel)

```csharp
private RedHoodBleedBuf GetBuf(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.RedHoodBleedBuf

### GetDamageFactor(UnitModel, DamageInfo)

```csharp
public override float GetDamageFactor(UnitModel target, DamageInfo damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### GetDamageTargets(float, bool)

```csharp
private List<UnitModel> GetDamageTargets(float dist = -1, bool ignoreDirection = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dist` | `System.Single` |  |
| `ignoreDirection` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetRequestCost(UnitModel)

```csharp
public int GetRequestCost(UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Int32

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

### GiveAxeThrowingDamage(UnitModel)

```csharp
public void GiveAxeThrowingDamage(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### GiveDamage(DamageInfo, List<UnitModel>, AttackType)

```csharp
private void GiveDamage(DamageInfo damageInfo, List<UnitModel> targets, RedHood.AttackType attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageInfo` | `Global.DamageInfo` |  |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `attackType` | `Global.RedHood.AttackType` |  |

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueCommandAction(int)

```csharp
public override bool HasUniqueCommandAction(int workType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### HuntingUpdate()

```csharp
private void HuntingUpdate()
```
#INC


### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSensoredInPassage()

```csharp
public override bool IsSensoredInPassage()
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

### IsWolf(UnitModel)

```csharp
public bool IsWolf(UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public override bool IsWorkable()
```
#INC


#### Returns

**Type:** System.Boolean

### Log(string)

```csharp
public static void Log(string log)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |

### MakeGunFlame(Transform)

```csharp
public void MakeGunFlame(Transform tr)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tr` | `UnityEngine.Transform` |  |

### MakeMovement(MapNode, OnCommandEnd)

```csharp
public void MakeMovement(MapNode targetNode, CreatureCommand.OnCommandEnd end = null)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeMovement(MovableObjectNode, OnCommandEnd)

```csharp
public void MakeMovement(MovableObjectNode targetMovable, CreatureCommand.OnCommandEnd end = null)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeSlashEffect()

```csharp
public void MakeSlashEffect()
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

### MakeThrowEffect(UnitModel, float)

```csharp
public void MakeThrowEffect(UnitModel target, float heightFctor = 2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `heightFctor` | `System.Single` |  |

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnApproachUpdate()

```csharp
public void OnApproachUpdate()
```
#INC


### OnArrivedRoom()

```csharp
public void OnArrivedRoom()
```
#INC


### OnAttackAnimEnd()

```csharp
public void OnAttackAnimEnd()
```
#INC


### OnAxeRespawned()

```csharp
public void OnAxeRespawned()
```
#INC


### OnDamageTime()

```csharp
public void OnDamageTime()
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

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGiveDamage(UnitModel, bool)

```csharp
public void OnGiveDamage(UnitModel target, bool isRanged)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `isRanged` | `System.Boolean` |  |

### OnHowlingAttacked()

```csharp
public void OnHowlingAttacked()
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

### OnOpenCommandWindow(Button[])

```csharp
public override void OnOpenCommandWindow(Button[] buttons)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnReadyForEscape()

```csharp
public void OnReadyForEscape()
```
#INC


### OnReturn()

```csharp
public override void OnReturn()
```
#INC


### OnSetTarget(UnitModel)

```csharp
public void OnSetTarget(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWolfSuppressedByOther()

```csharp
public void OnWolfSuppressedByOther()
```
#INC


### OnWolfSuppressedByRedHood()

```csharp
public void OnWolfSuppressedByRedHood()
```
#INC


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
#code-generated


### ResetMovement()

```csharp
public void ResetMovement()
```
#INC


### SetTargetDirection(UnitModel)

```csharp
public void SetTargetDirection(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StartAttack()

```csharp
private void StartAttack()
```
#INC


### StartRequest(UnitModel)

```csharp
public void StartRequest(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StopMovement(bool)

```csharp
public void StopMovement(bool clearDest = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clearDest` | `System.Boolean` |  |

### TryRequest()

```csharp
public void TryRequest()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC


### UniqueMoveControl()

```csharp
public override bool UniqueMoveControl()
```
#INC


#### Returns

**Type:** System.Boolean

### ValidateTarget()

```csharp
private bool ValidateTarget()
```
#INC


#### Returns

**Type:** System.Boolean
