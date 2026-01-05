# Class RedHood

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHood : CreatureBase, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → RedHood

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [Escape()](/api/CreatureBase#escape), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnStageEnd()](/api/CreatureBase#onstageend), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [GetName()](/api/CreatureBase#getname), [HasUniqueName()](/api/CreatureBase#hasuniquename), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Single

### QliphothMax

```csharp
public const int QliphothMax = 3
```

#### Field Value

**Type:** System.Int32

## Properties

### CurrentSpeedFactor

```csharp
public float CurrentSpeedFactor { get; }
```

#### Property Value

**Type:** System.Single

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

### CanCastMovingShoot()

```csharp
public bool CanCastMovingShoot()
```

#### Returns

**Type:** System.Boolean

### ClearBuf()

```csharp
public void ClearBuf()
```

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

### GetRequestCost(UnitModel)

```csharp
public int GetRequestCost(UnitModel unit)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```

#### Returns

**Type:** System.Boolean

### HasUniqueCommandAction(int)

```csharp
public override bool HasUniqueCommandAction(int workType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```

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

### IsWolf(UnitModel)

```csharp
public bool IsWolf(UnitModel unit)
```

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

### MakeGunFlame(Transform)

```csharp
public void MakeGunFlame(Transform tr)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tr` | `UnityEngine.Transform` |  |

### MakeMovement(MapNode, OnCommandEnd)

```csharp
public void MakeMovement(MapNode targetNode, CreatureCommand.OnCommandEnd end = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeMovement(MovableObjectNode, OnCommandEnd)

```csharp
public void MakeMovement(MovableObjectNode targetMovable, CreatureCommand.OnCommandEnd end = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeSlashEffect()

```csharp
public void MakeSlashEffect()
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

#### Returns

**Type:** System.Boolean

### OnApproachUpdate()

```csharp
public void OnApproachUpdate()
```

### OnArrivedRoom()

```csharp
public void OnArrivedRoom()
```

### OnAttackAnimEnd()

```csharp
public void OnAttackAnimEnd()
```

### OnAxeRespawned()

```csharp
public void OnAxeRespawned()
```

### OnDamageTime()

```csharp
public void OnDamageTime()
```

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
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

### OnGiveDamage(UnitModel, bool)

```csharp
public void OnGiveDamage(UnitModel target, bool isRanged)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `isRanged` | `System.Boolean` |  |

### OnHowlingAttacked()

```csharp
public void OnHowlingAttacked()
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

### OnOpenCommandWindow(Button[])

```csharp
public override void OnOpenCommandWindow(Button[] buttons)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```

#### Returns

**Type:** System.Boolean

### OnReadyForEscape()

```csharp
public void OnReadyForEscape()
```

### OnReturn()

```csharp
public override void OnReturn()
```

### OnSetTarget(UnitModel)

```csharp
public void OnSetTarget(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
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

### OnWolfSuppressedByOther()

```csharp
public void OnWolfSuppressedByOther()
```

### OnWolfSuppressedByRedHood()

```csharp
public void OnWolfSuppressedByRedHood()
```

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### ParamInit()

```csharp
public override void ParamInit()
```

### ResetMovement()

```csharp
public void ResetMovement()
```

### SetTargetDirection(UnitModel)

```csharp
public void SetTargetDirection(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StartRequest(UnitModel)

```csharp
public void StartRequest(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StopMovement(bool)

```csharp
public void StopMovement(bool clearDest = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clearDest` | `System.Boolean` |  |

### TryRequest()

```csharp
public void TryRequest()
```

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
