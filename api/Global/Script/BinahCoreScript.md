---
uid: Global.BinahCoreScript
canonical_path: /api/Global/Script/BinahCoreScript
---

# Class BinahCoreScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahCoreScript : CreatureBase
```

extends [CreatureBase](/api/Global/Creature/CreatureBase)

An Arbiter, from [Binah's core suppression](/api/Global/Misc/BinahBossBase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → BinahCoreScript

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahCoreScript()

```csharp
public BinahCoreScript()
```

## Fields

### _actionQueue

```csharp
private Queue<BinahAction> _actionQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{BinahBoss.BinahAction}

### _currentAction

```csharp
private BinahAction _currentAction
```
#INC


#### Field Value

**Type:** BinahBoss.BinahAction

### _currentPhase

```csharp
private BinahPhase _currentPhase
```
#INC


#### Field Value

**Type:** BinahBoss.BinahPhase

### _defenseTimer

```csharp
private Timer _defenseTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _isHalted

```csharp
private bool _isHalted
```
#INC


#### Field Value

**Type:** System.Boolean

### _isInvincible

```csharp
private bool _isInvincible
```
#INC


#### Field Value

**Type:** System.Boolean

### _phaseExecution

```csharp
private BinahPhaseExecution _phaseExecution
```
#INC


#### Field Value

**Type:** BinahBoss.BinahPhaseExecution

### _recoverTimer

```csharp
private Timer _recoverTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _waves

```csharp
private List<ProjectileModel> _waves
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ProjectileModel}

### AnimIntegerEvent

```csharp
private BinahIntegerAction AnimIntegerEvent
```
#INC


#### Field Value

**Type:** BinahBoss.BinahIntegerAction

### ArriveStopTime

```csharp
public static MinMax ArriveStopTime
```
#INC


#### Field Value

**Type:** Global.MinMax

### AttackEndEvent

```csharp
private BinahVoidAction AttackEndEvent
```
#INC


#### Field Value

**Type:** BinahBoss.BinahVoidAction

### binahDefenseType

```csharp
private BinahDefenseType binahDefenseType
```
#INC


#### Field Value

**Type:** BinahBoss.BinahDefenseType

### bossBase

```csharp
private BinahBossBase bossBase
```
#INC


#### Field Value

**Type:** Global.BinahBossBase

### currentOverload

```csharp
private BinahOverload currentOverload
```
#INC


#### Field Value

**Type:** BinahBoss.BinahOverload

### DamageEvent

```csharp
private BinahVoidAction DamageEvent
```
#INC


#### Field Value

**Type:** BinahBoss.BinahVoidAction

### defaultSpeed

```csharp
public const float defaultSpeed = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### movementModule

```csharp
private BinahMovementModule movementModule
```
#INC


#### Field Value

**Type:** BinahBoss.BinahMovementModule

### overloads

```csharp
private Dictionary<OverloadType, BinahOverload> overloads
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{OverloadType,BinahBoss.BinahOverload}

### PrefabFolder

```csharp
public const string PrefabFolder = "Effect/SefiraBoss/BinahBoss/"
```
#INC


#### Field Value

**Type:** System.String

### workerSenseRange

```csharp
public const float workerSenseRange = 4
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### AnimScript

```csharp
public BinahCoreAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.BinahCoreAnim

### BossBase

```csharp
public BinahBossBase BossBase { get; }
```

#### Property Value

**Type:** Global.BinahBossBase

### IsInvincible

```csharp
public bool IsInvincible { get; set; }
```

#### Property Value

**Type:** System.Boolean

### MovementModule

```csharp
public BinahMovementModule MovementModule { get; }
```

#### Property Value

**Type:** BinahBoss.BinahMovementModule

### Phase

```csharp
public BinahPhase Phase { get; }
```

#### Property Value

**Type:** BinahBoss.BinahPhase

## Methods

### AddOverload(BinahOverload)

```csharp
public void AddOverload(BinahOverload overload)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overload` | `BinahBoss.BinahOverload` |  |

### AddWave(ProjectileModel)

```csharp
public void AddWave(ProjectileModel wave)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `wave` | `Global.ProjectileModel` |  |

### AttachProjectile(BinahProjectile, string)

```csharp
private bool AttachProjectile(BinahProjectile projectile, string restSrc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `projectile` | `BinahBoss.BinahProjectile` |  |
| `restSrc` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### BinahGiveDamage(UnitModel, DamageInfo, bool)

```csharp
public void BinahGiveDamage(UnitModel target, DamageInfo damage, bool makeGut = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |
| `makeGut` | `System.Boolean` |  |

### BinahWaveGiveDamage(UnitModel, DamageInfo)

```csharp
public void BinahWaveGiveDamage(UnitModel target, DamageInfo damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

### CancelDefenseTimer()

```csharp
public void CancelDefenseTimer()
```

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

### ClearActionQueue()

```csharp
public void ClearActionQueue()
```

### ClearEvents()

```csharp
public void ClearEvents()
```

### ClearOverload(OverloadType)

```csharp
public void ClearOverload(OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### ClearWave()

```csharp
public void ClearWave()
```

### EnqueueAction(BinahAction)

```csharp
public void EnqueueAction(BinahAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahAction` |  |

### GenProjectile(Vector3, float, BinahProjectileType, out BinahProjectile)

```csharp
public bool GenProjectile(Vector3 position, float scale, BinahProjectileType type, out BinahProjectile binahProjectile)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |
| `scale` | `System.Single` |  |
| `type` | `BinahBoss.BinahProjectileType` |  |
| `binahProjectile` | `BinahBoss.BinahProjectile` |  |

#### Returns

**Type:** System.Boolean

### GetCurrentPhaseOverload()

```csharp
public OverloadType GetCurrentPhaseOverload()
```

#### Returns

**Type:** Global.OverloadType

### GetDirectionWithTarget(UnitModel)

```csharp
public UnitDirection GetDirectionWithTarget(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.UnitDirection

### GetName()

```csharp
public override string GetName()
```

#### Returns

**Type:** System.String

### GetNear<T>(bool, float)

```csharp
public List<T> GetNear<T>(bool careDirection = false, float range = -1) where T : UnitModel
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `careDirection` | `System.Boolean` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{{T}}

### GetOverload(OverloadType)

```csharp
public BinahOverload GetOverload(OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

#### Returns

**Type:** BinahBoss.BinahOverload

### GetProjectileSrc(BinahProjectileType)

```csharp
private string GetProjectileSrc(BinahProjectileType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `BinahBoss.BinahProjectileType` |  |

#### Returns

**Type:** System.String

### HaltExecution()

```csharp
public void HaltExecution()
```

### HasOverload()

```csharp
public bool HasOverload()
```

#### Returns

**Type:** System.Boolean

### InterruptClear()

```csharp
public void InterruptClear()
```

### InterruptCurrentAction()

```csharp
public void InterruptCurrentAction()
```

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsIndirectSuppressable()

```csharp
public override bool IsIndirectSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float, bool)

```csharp
public bool IsInRange(UnitModel target, float range, bool careDirection = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `careDirection` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### IsSensoredInPassage()

```csharp
public override bool IsSensoredInPassage()
```

#### Returns

**Type:** System.Boolean

### IsSuppressable()

```csharp
public override bool IsSuppressable()
```

#### Returns

**Type:** System.Boolean

### Log(string, bool)

```csharp
public static void Log(string log, bool isError = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |
| `isError` | `System.Boolean` |  |

### LookTarget(UnitModel)

```csharp
public void LookTarget(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeBattleDesc(int)

```csharp
public void MakeBattleDesc(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### MakeBattleDesc(int[])

```csharp
public void MakeBattleDesc(int[] id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32[]` |  |

### MakeNearSlowDown()

```csharp
private void MakeNearSlowDown()
```

### MakeOverload(CreatureModel, OverloadType)

```csharp
public void MakeOverload(CreatureModel target, OverloadType type = OverloadType.DEFAULT)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |
| `type` | `Global.OverloadType` |  |

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

### MoveToNextPhase()

```csharp
public void MoveToNextPhase()
```

### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnCollision(BinahCollision)

```csharp
public void OnCollision(BinahCollision collision)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collision` | `BinahBoss.BinahCollision` |  |

### OnCollision(BinahCollision, BinahProjectile)

```csharp
public void OnCollision(BinahCollision collider, BinahProjectile projectile)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collider` | `BinahBoss.BinahCollision` |  |
| `projectile` | `BinahBoss.BinahProjectile` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGiveDamage()

```csharp
public void OnGiveDamage()
```

### OnMakeGut(WorkerModel, UnitDirection)

```csharp
public void OnMakeGut(WorkerModel target, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dir` | `Global.UnitDirection` |  |

### OnOverloadSuccessParticle(OverloadType)

```csharp
public void OnOverloadSuccessParticle(OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### OnParticleArrived(BinahOverloadClearParticle)

```csharp
public void OnParticleArrived(BinahOverloadClearParticle ps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ps` | `BinahBoss.BinahOverloadClearParticle` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC
#code-generated


### OnSuppressed()

```csharp
public override void OnSuppressed()
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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SetAnimCalledEvent(BinahIntegerAction)

```csharp
public void SetAnimCalledEvent(BinahIntegerAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahIntegerAction` |  |

### SetAttackEndEvent(BinahVoidAction)

```csharp
public void SetAttackEndEvent(BinahVoidAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahVoidAction` |  |

### SetBossBase(BinahBossBase)

```csharp
public void SetBossBase(BinahBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `Global.BinahBossBase` |  |

### SetDamageEvent(BinahVoidAction)

```csharp
public void SetDamageEvent(BinahVoidAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahVoidAction` |  |

### SetDefenseReturnTimer(float)

```csharp
public void SetDefenseReturnTimer(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### SetDefenseType(BinahDefenseType)

```csharp
public void SetDefenseType(BinahDefenseType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `BinahBoss.BinahDefenseType` |  |

### SetHpSlider(Slider)

```csharp
public override bool SetHpSlider(Slider slider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetPhase(BinahPhase)

```csharp
public void SetPhase(BinahPhase phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `BinahBoss.BinahPhase` |  |

### SetSpeed(float)

```csharp
public void SetSpeed(float speed = 2.5)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |

### UniqueMoveControl()

```csharp
public override bool UniqueMoveControl()
```

#### Returns

**Type:** System.Boolean

### Update()

```csharp
public void Update()
```
