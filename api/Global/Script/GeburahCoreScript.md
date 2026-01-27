---
uid: Global.GeburahCoreScript
canonical_path: /api/Global/Script/GeburahCoreScript
---

# Class GeburahCoreScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahCoreScript : CreatureBase
```

extends [CreatureBase](/api/Global/Creature/CreatureBase)

The Red Mist. [Geburah's core suppression](/api/Global/Misc/GeburahBossBase) ends when she is defeated. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → GeburahCoreScript

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahCoreScript()

```csharp
public GeburahCoreScript()
```

## Fields

### _actionQueue

```csharp
private Queue<GeburahAction> _actionQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{GeburahBoss.GeburahAction}

### _attackEndInvoked

```csharp
private GeburahActionMethod _attackEndInvoked
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahActionMethod

### _bloodyTreeFreq

```csharp
private MinMax _bloodyTreeFreq
```
#INC


#### Field Value

**Type:** Global.MinMax

### _bloodyTreeTimer

```csharp
private Timer _bloodyTreeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _currentAction

```csharp
private GeburahAction _currentAction
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahAction

### _damageInvoked

```csharp
private GeburahActionMethod _damageInvoked
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahActionMethod

### _eventCalledInvoked

```csharp
private GeburahEventCalled _eventCalledInvoked
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahEventCalled

### _isInvincible

```csharp
private bool _isInvincible
```
#INC


#### Field Value

**Type:** System.Boolean

### _phase

```csharp
private GeburahPhase _phase
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahPhase

### _phaseExecution

```csharp
private GeburahPhaseExectuion _phaseExecution
```
#INC


#### Field Value

**Type:** GeburahBoss.GeburahPhaseExectuion

### _recoverTimer

```csharp
private Timer _recoverTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### bossBase

```csharp
private GeburahBossBase bossBase
```
#INC


#### Field Value

**Type:** Global.GeburahBossBase

### damageCalculator

```csharp
public GeburahCoreScript.DamageCalculator damageCalculator
```

#### Field Value

**Type:** Global.GeburahCoreScript.DamageCalculator

### defaultSpeed

```csharp
private const float defaultSpeed = 4.8
```
#INC


#### Field Value

**Type:** System.Single

### GeburahKillEffect

```csharp
public const string GeburahKillEffect = "Effect/SefiraBoss/GeburahProjectile/GeburahKill"
```
#INC


#### Field Value

**Type:** System.String

### GeburahProjectileFolder

```csharp
public const string GeburahProjectileFolder = "Effect/SefiraBoss/GeburahProjectile/"
```
#INC


#### Field Value

**Type:** System.String

### GeburahProjectileSrc

```csharp
public const string GeburahProjectileSrc = "Effect/SefiraBoss/GeburahProjectile/GeburahProjectile"
```
#INC


#### Field Value

**Type:** System.String

### SpawnSrc

```csharp
public const string SpawnSrc = "GeburahSpawn"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### AnimScript

```csharp
public GeburahCoreAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.GeburahCoreAnim

### BossBase

```csharp
public GeburahBossBase BossBase { get; }
```

#### Property Value

**Type:** Global.GeburahBossBase

### GeburahSefira

```csharp
private Sefira GeburahSefira { get; }
```

#### Property Value

**Type:** Global.Sefira

### IsInvincible

```csharp
public bool IsInvincible { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Phase

```csharp
public GeburahPhase Phase { get; }
```

#### Property Value

**Type:** GeburahBoss.GeburahPhase

## Methods

### AttachProjectile(GeburahProjectile, string)

```csharp
public bool AttachProjectile(GeburahProjectile proj, string projectileName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `proj` | `Global.GeburahProjectile` |  |
| `projectileName` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### CanStartBloodyTree()

```csharp
public bool CanStartBloodyTree()
```
#INC


#### Returns

**Type:** System.Boolean

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

### ClearActionQueue()

```csharp
public void ClearActionQueue()
```
#INC


### ClearAttackEndInvoked()

```csharp
public void ClearAttackEndInvoked()
```
#INC


### ClearDamageFillEvent()

```csharp
public void ClearDamageFillEvent()
```
#INC


### ClearDamageInvoked()

```csharp
public void ClearDamageInvoked()
```
#INC


### ClearEventInvoked()

```csharp
public void ClearEventInvoked()
```
#INC


### EnqeueAction(GeburahAction)

```csharp
public void EnqeueAction(GeburahAction action)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GeburahBoss.GeburahAction` |  |

### GeburahGiveDamage(UnitModel, DamageInfo, bool)

```csharp
public void GeburahGiveDamage(UnitModel target, DamageInfo damage, bool maunualgutMake = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |
| `maunualgutMake` | `System.Boolean` |  |

### GenProjectile(Transform, ProjectileType, out GeburahProjectile)

```csharp
public bool GenProjectile(Transform pivot, ProjectileType type, out GeburahProjectile output)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pivot` | `UnityEngine.Transform` |  |
| `type` | `GeburahBoss.ProjectileType` |  |
| `output` | `Global.GeburahProjectile` |  |

#### Returns

**Type:** System.Boolean

### GetCurrentStandingSefira()

```csharp
public Sefira GetCurrentStandingSefira()
```
#INC


#### Returns

**Type:** Global.Sefira

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

### GetDamageInfo(int, int)

```csharp
public List<DamageInfo> GetDamageInfo(int attackType, int indexer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |
| `indexer` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{DamageInfo}

### GetDirectionWithTarget(UnitModel)

```csharp
public UnitDirection GetDirectionWithTarget(UnitModel target)
```
#INC


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
#INC


#### Returns

**Type:** System.String

### GetNearUnits()

```csharp
public List<UnitModel> GetNearUnits()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetNextAction()

```csharp
public GeburahAction GetNextAction()
```
#INC


#### Returns

**Type:** GeburahBoss.GeburahAction

### GetProjectileName(ProjectileType)

```csharp
private string GetProjectileName(ProjectileType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `GeburahBoss.ProjectileType` |  |

#### Returns

**Type:** System.String

### GetRandomMoveSefira(Sefira)

```csharp
public Sefira GetRandomMoveSefira(Sefira removeSefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `removeSefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.Sefira

### GetRangedTargets(List<UnitModel>, float, float)

```csharp
public List<UnitModel> GetRangedTargets(List<UnitModel> near, float front, float rear)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |
| `front` | `System.Single` |  |
| `rear` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### InterruptCurrentAction()

```csharp
public void InterruptCurrentAction()
```
#INC


### IsInRange(UnitModel, float)

```csharp
public bool IsInRange(UnitModel target, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

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

### LookTarget(UnitModel)

```csharp
public void LookTarget(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeBattleDesc(int)

```csharp
public void MakeBattleDesc(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### MakeBattleDesc(params int[])

```csharp
public void MakeBattleDesc(params int[] index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32[]` |  |

### MakeBloodyTree(WorkerModel)

```csharp
public void MakeBloodyTree(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### MakeSlash(UnitModel)

```csharp
public void MakeSlash(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeSound(string)

```csharp
public override SoundEffectPlayer MakeSound(string soundSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `soundSrc` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeTeleprot()

```csharp
public GeburahTeleport MakeTeleprot()
```
#INC


#### Returns

**Type:** Global.GeburahTeleport

### MimicriNearDamage(Vector3)

```csharp
public void MimicriNearDamage(Vector3 end)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `end` | `UnityEngine.Vector3` |  |

### MoveToNextPhase()

```csharp
public void MoveToNextPhase()
```
#INC


### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnDamage()

```csharp
public void OnDamage()
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

### OnKillWokrer(WorkerModel)

```csharp
public void OnKillWokrer(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnMakeGut(WorkerModel, UnitDirection)

```csharp
public void OnMakeGut(WorkerModel target, UnitDirection dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dir` | `Global.UnitDirection` |  |

### OnProjectileGiveDamage(UnitModel, GeburahProjectile)

```csharp
public void OnProjectileGiveDamage(UnitModel target, GeburahProjectile proj)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `proj` | `Global.GeburahProjectile` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### OnStartBloodyTreeTimer()

```csharp
public void OnStartBloodyTreeTimer()
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

### SetAttackEndInvoked(GeburahActionMethod)

```csharp
public void SetAttackEndInvoked(GeburahActionMethod actionMethod)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetBossBase(GeburahBossBase)

```csharp
public void SetBossBase(GeburahBossBase bossBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `Global.GeburahBossBase` |  |

### SetDamageFillEvent(GeburahActionMethod)

```csharp
public void SetDamageFillEvent(GeburahActionMethod actionMethod)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetDamageInvoked(GeburahActionMethod)

```csharp
public void SetDamageInvoked(GeburahActionMethod actionMethod)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetEventCalledInvoked(GeburahEventCalled)

```csharp
public void SetEventCalledInvoked(GeburahEventCalled actionMethod)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahEventCalled` |  |

### SetPhase(GeburahPhase)

```csharp
public void SetPhase(GeburahPhase phase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `GeburahBoss.GeburahPhase` |  |

### SetSpeed(float)

```csharp
public void SetSpeed(float speed = 4.8)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |
