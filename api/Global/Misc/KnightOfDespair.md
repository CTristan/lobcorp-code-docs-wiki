---
uid: Global.KnightOfDespair
canonical_path: /api/Global/Misc/KnightOfDespair
---

# Class KnightOfDespair

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KnightOfDespair : CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → KnightOfDespair

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KnightOfDespair()

```csharp
public KnightOfDespair()
```

## Fields

### _attackDelayMax

```csharp
private const float _attackDelayMax = 3
```

#### Field Value

**Type:** System.Single

### _attackDelayMin

```csharp
private const float _attackDelayMin = 2
```

#### Field Value

**Type:** System.Single

### _attackDelayTimer

```csharp
private Timer _attackDelayTimer
```

#### Field Value

**Type:** Global.Timer

### _blessedWorker

```csharp
private WorkerModel _blessedWorker
```

#### Field Value

**Type:** Global.WorkerModel

### _currentAttackAnimIndex

```csharp
private Queue<int> _currentAttackAnimIndex
```

#### Field Value

**Type:** System.Collections.Generic.Queue{System.Int32}

### _currentDestNode

```csharp
private MapNode _currentDestNode
```

#### Field Value

**Type:** Global.MapNode

### _currentTarget

```csharp
private UnitModel _currentTarget
```

#### Field Value

**Type:** Global.UnitModel

### _currentTeleportNode

```csharp
private MapNode _currentTeleportNode
```

#### Field Value

**Type:** Global.MapNode

### _escapeDefaultSound

```csharp
private SoundEffectPlayer _escapeDefaultSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### _escapeSoundFreqMax

```csharp
private const float _escapeSoundFreqMax = 40
```

#### Field Value

**Type:** System.Single

### _escapeSoundFreqMin

```csharp
private const float _escapeSoundFreqMin = 30
```

#### Field Value

**Type:** System.Single

### _escapeSoundTimer

```csharp
private Timer _escapeSoundTimer
```

#### Field Value

**Type:** Global.Timer

### _isAtttackig

```csharp
private bool _isAtttackig
```

#### Field Value

**Type:** System.Boolean

### _isBlessing

```csharp
private bool _isBlessing
```

#### Field Value

**Type:** System.Boolean

### _isMoving

```csharp
private bool _isMoving
```

#### Field Value

**Type:** System.Boolean

### _isTeleporting

```csharp
private bool _isTeleporting
```

#### Field Value

**Type:** System.Boolean

### _readyForTeleport

```csharp
private bool _readyForTeleport
```

#### Field Value

**Type:** System.Boolean

### _teleportAfterDelay

```csharp
private Timer _teleportAfterDelay
```

#### Field Value

**Type:** Global.Timer

### _teleportDelayMax

```csharp
private const float _teleportDelayMax = 30
```

#### Field Value

**Type:** System.Single

### _teleportDelayMin

```csharp
private const float _teleportDelayMin = 15
```

#### Field Value

**Type:** System.Single

### _teleportTimer

```csharp
private Timer _teleportTimer
```

#### Field Value

**Type:** Global.Timer

### blessEffect

```csharp
private GameObject blessEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### blessEffectSrc

```csharp
public const string blessEffectSrc = "Effect/Creature/KnightOfDespair/KnightBufAurora"
```

#### Field Value

**Type:** System.String

### damageEffectSrc

```csharp
public const string damageEffectSrc = "Effect/Creature/KnightOfDespair/Spade"
```

#### Field Value

**Type:** System.String

### Damageinfo

```csharp
private static DamageInfo Damageinfo
```

#### Field Value

**Type:** Global.DamageInfo

### DefaultAttackIndex

```csharp
private static int[] DefaultAttackIndex
```

#### Field Value

**Type:** System.Int32[]

### LogPrefix

```csharp
private static string LogPrefix
```

#### Field Value

**Type:** System.String

### renableList

```csharp
private List<KnightOfDespair.SwordRenable> renableList
```

#### Field Value

**Type:** System.Collections.Generic.List{KnightOfDespair.SwordRenable}

### SoundKey_Attack

```csharp
public const string SoundKey_Attack = "Attack"
```

#### Field Value

**Type:** System.String

### SoundKey_Aura

```csharp
public const string SoundKey_Aura = "Aura"
```

#### Field Value

**Type:** System.String

### SoundKey_Bless

```csharp
public const string SoundKey_Bless = "Bless"
```

#### Field Value

**Type:** System.String

### SoundKey_Blink_1

```csharp
public const string SoundKey_Blink_1 = "Blink_1"
```

#### Field Value

**Type:** System.String

### SoundKey_Blink_2

```csharp
public const string SoundKey_Blink_2 = "Blink_2"
```

#### Field Value

**Type:** System.String

### SoundKey_Change_1

```csharp
public const string SoundKey_Change_1 = "Change_1"
```

#### Field Value

**Type:** System.String

### SoundKey_Change_2

```csharp
public const string SoundKey_Change_2 = "Change_2"
```

#### Field Value

**Type:** System.String

### SoundKey_Dead

```csharp
public const string SoundKey_Dead = "Dead"
```

#### Field Value

**Type:** System.String

### SoundKey_Default

```csharp
public const string SoundKey_Default = "Default"
```

#### Field Value

**Type:** System.String

### TeleportAppearEffect

```csharp
public const string TeleportAppearEffect = "Effect/Creature/MagicalGirl/Appear"
```

#### Field Value

**Type:** System.String

### TeleportDisappearEffect

```csharp
public const string TeleportDisappearEffect = "Effect/Creature/MagicalGirl/Disappear"
```

#### Field Value

**Type:** System.String

## Properties

### AnimScript

```csharp
public KnightOfDespairAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.KnightOfDespairAnim

### AttackDelay

```csharp
private float AttackDelay { get; }
```

#### Property Value

**Type:** System.Single

### BlessedWorker

```csharp
public WorkerModel BlessedWorker { get; }
```

#### Property Value

**Type:** Global.WorkerModel

### CurrentTarget

```csharp
public UnitModel CurrentTarget { get; }
```

#### Property Value

**Type:** Global.UnitModel

### TeleportDelay

```csharp
private float TeleportDelay { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ActivateBless(WorkerModel)

```csharp
private void ActivateBless(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AttackEnd()

```csharp
public void AttackEnd()
```

### CheckBless(UseSkill)

```csharp
private bool CheckBless(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### CheckSword()

```csharp
private void CheckSword()
```

### ClearBlessed()

```csharp
public void ClearBlessed()
```

### Escape()

```csharp
public override void Escape()
```

### GetAttackIndex()

```csharp
private List<int> GetAttackIndex()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int32}

### GetNearTargets()

```csharp
private List<UnitModel> GetNearTargets()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetRandomDestination()

```csharp
private MapNode GetRandomDestination()
```

#### Returns

**Type:** Global.MapNode

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

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```

#### Returns

**Type:** System.Boolean

### IsActivatedWorkDesc()

```csharp
public override bool IsActivatedWorkDesc()
```

#### Returns

**Type:** System.Boolean

### IsTeleportable()

```csharp
private bool IsTeleportable()
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

### MakeBlessSound()

```csharp
public void MakeBlessSound()
```

### MakeDeadSound()

```csharp
public void MakeDeadSound()
```

### MakeDefaultSound()

```csharp
private void MakeDefaultSound()
```

### MakeRandomMovement()

```csharp
private void MakeRandomMovement()
```

### MakeSound(string, Vector3)

```csharp
public SoundEffectPlayer MakeSound(string key, Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnBlessAnimEnded()

```csharp
public void OnBlessAnimEnded()
```

### OnBlessedWorkerEndangered()

```csharp
public void OnBlessedWorkerEndangered()
```

### OnReturn()

```csharp
public override void OnReturn()
```

### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnSuppressed()

```csharp
public override void OnSuppressed()
```

### OnSwordArrived(ProjectileModel)

```csharp
public void OnSwordArrived(ProjectileModel proj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `proj` | `Global.ProjectileModel` |  |

### OnTeleport()

```csharp
public void OnTeleport()
```

### OnThrowSword(KnightOfDespairSword)

```csharp
public void OnThrowSword(KnightOfDespairSword sword)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sword` | `Global.KnightOfDespairSword` |  |

### OnTransformEnded()

```csharp
public void OnTransformEnded()
```

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### ParamInit()

```csharp
public override void ParamInit()
```

### ResetState()

```csharp
private void ResetState()
```

### StartAttack(UnitModel)

```csharp
public void StartAttack(UnitModel mainTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.UnitModel` |  |

### StartTeleport()

```csharp
private void StartTeleport()
```

### StopAttack()

```csharp
private void StopAttack()
```

### StopMovement(bool)

```csharp
private void StopMovement(bool clearDest = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clearDest` | `System.Boolean` |  |

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
