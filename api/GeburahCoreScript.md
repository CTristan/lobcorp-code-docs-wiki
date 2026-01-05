# Class GeburahCoreScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahCoreScript : CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → GeburahCoreScript

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/CreatureBase#onreturn), [UniqueEscape()](/api/CreatureBase#uniqueescape), [Escape()](/api/CreatureBase#escape), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnStageEnd()](/api/CreatureBase#onstageend), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [IsWorkable()](/api/CreatureBase#isworkable), [ParamInit()](/api/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [HasRoomCounter()](/api/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/CreatureBase#hasuniquename), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GeburahCoreScript()

```csharp
public GeburahCoreScript()
```

## Fields

### damageCalculator

```csharp
public GeburahCoreScript.DamageCalculator damageCalculator
```

#### Field Value

**Type:** Global.GeburahCoreScript.DamageCalculator

### GeburahKillEffect

```csharp
public const string GeburahKillEffect = "Effect/SefiraBoss/GeburahProjectile/GeburahKill"
```

#### Field Value

**Type:** System.String

### GeburahProjectileFolder

```csharp
public const string GeburahProjectileFolder = "Effect/SefiraBoss/GeburahProjectile/"
```

#### Field Value

**Type:** System.String

### GeburahProjectileSrc

```csharp
public const string GeburahProjectileSrc = "Effect/SefiraBoss/GeburahProjectile/GeburahProjectile"
```

#### Field Value

**Type:** System.String

### SpawnSrc

```csharp
public const string SpawnSrc = "GeburahSpawn"
```

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

#### Returns

**Type:** System.Boolean

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

### ClearAttackEndInvoked()

```csharp
public void ClearAttackEndInvoked()
```

### ClearDamageFillEvent()

```csharp
public void ClearDamageFillEvent()
```

### ClearDamageInvoked()

```csharp
public void ClearDamageInvoked()
```

### ClearEventInvoked()

```csharp
public void ClearEventInvoked()
```

### EnqeueAction(GeburahAction)

```csharp
public void EnqeueAction(GeburahAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GeburahBoss.GeburahAction` |  |

### GeburahGiveDamage(UnitModel, DamageInfo, bool)

```csharp
public void GeburahGiveDamage(UnitModel target, DamageInfo damage, bool maunualgutMake = false)
```

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

#### Returns

**Type:** Global.Sefira

### GetDamageFactor(UnitModel, DamageInfo)

```csharp
public override float GetDamageFactor(UnitModel target, DamageInfo damage)
```

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

### GetNearUnits()

```csharp
public List<UnitModel> GetNearUnits()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetNextAction()

```csharp
public GeburahAction GetNextAction()
```

#### Returns

**Type:** GeburahBoss.GeburahAction

### GetRandomMoveSefira(Sefira)

```csharp
public Sefira GetRandomMoveSefira(Sefira removeSefira)
```

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

### IsInRange(UnitModel, float)

```csharp
public bool IsInRange(UnitModel target, float range)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |

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

### MakeBattleDesc(params int[])

```csharp
public void MakeBattleDesc(params int[] index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32[]` |  |

### MakeBloodyTree(WorkerModel)

```csharp
public void MakeBloodyTree(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### MakeSlash(UnitModel)

```csharp
public void MakeSlash(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeSound(string)

```csharp
public override SoundEffectPlayer MakeSound(string soundSrc)
```

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

#### Returns

**Type:** Global.GeburahTeleport

### MimicriNearDamage(Vector3)

```csharp
public void MimicriNearDamage(Vector3 end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `end` | `UnityEngine.Vector3` |  |

### MoveToNextPhase()

```csharp
public void MoveToNextPhase()
```

### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnDamage()

```csharp
public void OnDamage()
```

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnKillWokrer(WorkerModel)

```csharp
public void OnKillWokrer(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnMakeGut(WorkerModel, UnitDirection)

```csharp
public void OnMakeGut(WorkerModel target, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dir` | `Global.UnitDirection` |  |

### OnProjectileGiveDamage(UnitModel, GeburahProjectile)

```csharp
public void OnProjectileGiveDamage(UnitModel target, GeburahProjectile proj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `proj` | `Global.GeburahProjectile` |  |

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnStartBloodyTreeTimer()

```csharp
public void OnStartBloodyTreeTimer()
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

### SetAttackEndInvoked(GeburahActionMethod)

```csharp
public void SetAttackEndInvoked(GeburahActionMethod actionMethod)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetBossBase(GeburahBossBase)

```csharp
public void SetBossBase(GeburahBossBase bossBase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `Global.GeburahBossBase` |  |

### SetDamageFillEvent(GeburahActionMethod)

```csharp
public void SetDamageFillEvent(GeburahActionMethod actionMethod)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetDamageInvoked(GeburahActionMethod)

```csharp
public void SetDamageInvoked(GeburahActionMethod actionMethod)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahActionMethod` |  |

### SetEventCalledInvoked(GeburahEventCalled)

```csharp
public void SetEventCalledInvoked(GeburahEventCalled actionMethod)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actionMethod` | `GeburahBoss.GeburahEventCalled` |  |

### SetPhase(GeburahPhase)

```csharp
public void SetPhase(GeburahPhase phase)
```

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
