# Class BossBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBird : BirdCreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → [BirdCreatureBase](/api/BirdCreatureBase) → BossBird

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [OnInit()](/api/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/CreatureBase#onreturn), [UniqueEscape()](/api/CreatureBase#uniqueescape), [Escape()](/api/CreatureBase#escape), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [IsWorkable()](/api/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [HasRoomCounter()](/api/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BossBird()

```csharp
public BossBird()
```

## Fields

### _boss_gift_id

```csharp
public const int _boss_gift_id = 400038
```

#### Field Value

**Type:** System.Int32

### attractEffect

```csharp
public const string attractEffect = "Effect/Creature/BossBird/Particle/BossBirdAttractEffect"
```

#### Field Value

**Type:** System.String

### LaserCount

```csharp
public const int LaserCount = 26
```

#### Field Value

**Type:** System.Int32

### laserExplode

```csharp
public const string laserExplode = "Effect/Creature/BossBird/Particle/ExplodeEffect"
```

#### Field Value

**Type:** System.String

### meleeHit_1_EffectSrc

```csharp
public const string meleeHit_1_EffectSrc = "Effect/Creature/BossBird/Particle/BossBirdMeleeHit"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Claw_LeftEffectSrc

```csharp
public const string meleeHit_2_Claw_LeftEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectLeft"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Claw_RightEffectSrc

```csharp
public const string meleeHit_2_Claw_RightEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectRight"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Grep_LeftEffectSrc

```csharp
public const string meleeHit_2_Grep_LeftEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectLeft"
```

#### Field Value

**Type:** System.String

### meleeHit_2_Grep_RightEffectSrc

```csharp
public const string meleeHit_2_Grep_RightEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectRight"
```

#### Field Value

**Type:** System.String

### scaleEffect

```csharp
public const string scaleEffect = "Effect/Creature/BossBird/Particle/ScaleEffect"
```

#### Field Value

**Type:** System.String

### ultDeadEffecSrc

```csharp
public const string ultDeadEffecSrc = "Effect/Creature/BossBird/Particle/BossBirdAgentDead"
```

#### Field Value

**Type:** System.String

### ultHandLeftSrc

```csharp
public const string ultHandLeftSrc = "Effect/Creature/BossBird/Particle/UltShock_Left"
```

#### Field Value

**Type:** System.String

### ultHandRightSrc

```csharp
public const string ultHandRightSrc = "Effect/Creature/BossBird/Particle/UltShcok_Right"
```

#### Field Value

**Type:** System.String

### ultShootEffectLeftSrc

```csharp
public const string ultShootEffectLeftSrc = "Effect/Creature/BossBird/Particle/GutShootEffectLeft"
```

#### Field Value

**Type:** System.String

### ultShootEffectRightSrc

```csharp
public const string ultShootEffectRightSrc = "Effect/Creature/BossBird/Particle/GutShootEffectRight"
```

#### Field Value

**Type:** System.String

## Properties

### BigEggModel

```csharp
public EventCreatureModel BigEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### currentPhase

```csharp
public BossBird.Phase currentPhase { get; set; }
```

#### Property Value

**Type:** Global.BossBird.Phase

### GateWayModel

```csharp
public EventCreatureModel GateWayModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### LongEggModel

```csharp
public EventCreatureModel LongEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

### SmallEggModel

```csharp
public EventCreatureModel SmallEggModel { get; }
```

#### Property Value

**Type:** Global.EventCreatureModel

## Methods

### AttractPattern()

```csharp
public void AttractPattern()
```

### BitePattern()

```csharp
public void BitePattern()
```

### CancelNormalAttack()

```csharp
public void CancelNormalAttack()
```

### CancelPatternAttack()

```csharp
public void CancelPatternAttack()
```

### DeleteSound(SoundEffectPlayer)

```csharp
public void DeleteSound(SoundEffectPlayer sound)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sound` | `Global.SoundEffectPlayer` |  |

### EndNormalAttack()

```csharp
public void EndNormalAttack()
```

### EndPatternAttack()

```csharp
public void EndPatternAttack()
```

### EndTeleport()

```csharp
public void EndTeleport()
```

### EndUltShoot()

```csharp
public void EndUltShoot()
```

### FadeOutSound()

```csharp
public void FadeOutSound()
```

### GetAttackTarget()

```csharp
public List<UnitModel> GetAttackTarget()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetCurrentAttackType()

```csharp
public BossBird.AttackType GetCurrentAttackType()
```

#### Returns

**Type:** Global.BossBird.AttackType

### GetDirectionTarget()

```csharp
public List<UnitModel> GetDirectionTarget()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetDirectionTarget(List<UnitModel>, float, float)

```csharp
public List<UnitModel> GetDirectionTarget(List<UnitModel> targets, float max_dist, float min_dist)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `max_dist` | `System.Single` |  |
| `min_dist` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetName()

```csharp
public override string GetName()
```

#### Returns

**Type:** System.String

### GetNarrationKeyByEnum(NarrationState)

```csharp
public static string GetNarrationKeyByEnum(BossBird.NarrationState nar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nar` | `Global.BossBird.NarrationState` |  |

#### Returns

**Type:** System.String

### GetNarrationState(string)

```csharp
public static BossBird.NarrationState GetNarrationState(string state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.String` |  |

#### Returns

**Type:** Global.BossBird.NarrationState

### GetParam(string)

```csharp
public CreatureStaticData.ParameterData GetParam(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetParamData(string)

```csharp
public string GetParamData(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetRangeTarget(Vector3, float)

```csharp
public List<UnitModel> GetRangeTarget(Vector3 pos, float half_Range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `half_Range` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveMeleeDamage()

```csharp
public void GiveMeleeDamage()
```

### MakeBirdConcentrationGate()

```csharp
public void MakeBirdConcentrationGate()
```

### MakeMovementRandom()

```csharp
public void MakeMovementRandom()
```

### MakeMovementToEgg(BossEggBase)

```csharp
public void MakeMovementToEgg(BossEggBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossEggBase` |  |

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

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnBirdArrived(IBirdControl)

```csharp
public void OnBirdArrived(IBirdControl bird)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bird` | `Global.IBirdControl` |  |

### OnBirdEscape(LongBird, SmallBird, BigBird)

```csharp
public void OnBirdEscape(LongBird longBird, SmallBird small, BigBird big)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `small` | `Global.SmallBird` |  |
| `big` | `Global.BigBird` |  |

### OnCannotUsePlaySpeedSetting(int)

```csharp
public void OnCannotUsePlaySpeedSetting(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnCastingEnd()

```csharp
public void OnCastingEnd()
```

### OnEggBreakDown(BossEggBase)

```csharp
public void OnEggBreakDown(BossEggBase eggScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnEggHalfDamage(BossEggBase)

```csharp
public void OnEggHalfDamage(BossEggBase eggScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGateWaySuppressed()

```csharp
public void OnGateWaySuppressed()
```

### OnLaserParticleArrived(LaserAttackTargetData)

```csharp
public void OnLaserParticleArrived(BossBird.LaserAttackTargetData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBird.LaserAttackTargetData` |  |

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnSuppressed()

```csharp
public override void OnSuppressed()
```

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkerWakeUp(WorkerModel)

```csharp
public void OnWorkerWakeUp(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OpenBossBirdCollection()

```csharp
public void OpenBossBirdCollection()
```

### ParamInit()

```csharp
public override void ParamInit()
```

### PrevTeleport(MapNode)

```csharp
public void PrevTeleport(MapNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### ScalePattern()

```csharp
public void ScalePattern()
```

### SetBirds(LongBird, SmallBird, BigBird)

```csharp
public void SetBirds(LongBird longBird, SmallBird smallBird, BigBird bigBird)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `smallBird` | `Global.SmallBird` |  |
| `bigBird` | `Global.BigBird` |  |

### SetCastingSlider(Slider)

```csharp
public override bool SetCastingSlider(Slider castingSlider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetCreatureActivateState(bool)

```csharp
public void SetCreatureActivateState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetModel(CreatureModel)

```csharp
public override void SetModel(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### StartMeleeAttack()

```csharp
public void StartMeleeAttack()
```

### StartRangeAttack()

```csharp
public void StartRangeAttack()
```

### StopMovement()

```csharp
public void StopMovement()
```

### TakeUltDamage()

```csharp
public void TakeUltDamage()
```

### Teleport()

```csharp
public void Teleport()
```

### WakeUpWorker(WorkerModel)

```csharp
public void WakeUpWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
