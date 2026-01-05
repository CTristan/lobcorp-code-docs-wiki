# Class BinahCoreScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahCoreScript : CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → BinahCoreScript

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/CreatureBase#onreturn), [UniqueEscape()](/api/CreatureBase#uniqueescape), [Escape()](/api/CreatureBase#escape), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnStageEnd()](/api/CreatureBase#onstageend), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [IsWorkable()](/api/CreatureBase#isworkable), [ParamInit()](/api/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [HasRoomCounter()](/api/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [HasUniqueName()](/api/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahCoreScript()

```csharp
public BinahCoreScript()
```

## Fields

### ArriveStopTime

```csharp
public static MinMax ArriveStopTime
```

#### Field Value

**Type:** Global.MinMax

### defaultSpeed

```csharp
public const float defaultSpeed = 2.5
```

#### Field Value

**Type:** System.Single

### PrefabFolder

```csharp
public const string PrefabFolder = "Effect/SefiraBoss/BinahBoss/"
```

#### Field Value

**Type:** System.String

### workerSenseRange

```csharp
public const float workerSenseRange = 4
```

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
