---
uid: Global.YoungPrinceFriend
canonical_path: /api/Global/Misc/YoungPrinceFriend
---

# Class YoungPrinceFriend

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YoungPrinceFriend : CreatureBase
```

One of [The Little Prince](/api/Global/IOBserver/YoungPrince)'s minions.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → YoungPrinceFriend

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### YoungPrinceFriend()

```csharp
public YoungPrinceFriend()
```

## Fields

### _animScript

```csharp
private YoungPrinceFriendAnim _animScript
```
#INC


#### Field Value

**Type:** Global.YoungPrinceFriendAnim

### _atkDmgMax

```csharp
private const int _atkDmgMax = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkDmgMin

```csharp
private const int _atkDmgMin = 6
```
#INC


#### Field Value

**Type:** System.Int32

### _atkDmgRange

```csharp
private const float _atkDmgRange = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### _attackRange

```csharp
private const float _attackRange = 3
```
#INC


#### Field Value

**Type:** System.Single

### _infestProb

```csharp
private const int _infestProb = 40
```
#INC


#### Field Value

**Type:** System.Int32

### _motionDelayMax

```csharp
private const float _motionDelayMax = 1.2
```
#INC


#### Field Value

**Type:** System.Single

### _motionDelayMin

```csharp
private const float _motionDelayMin = 0.8
```
#INC


#### Field Value

**Type:** System.Single

### _moveFreqMax

```csharp
private const float _moveFreqMax = 2
```
#INC


#### Field Value

**Type:** System.Single

### _moveFreqMin

```csharp
private const float _moveFreqMin = 1
```
#INC


#### Field Value

**Type:** System.Single

### _smashDmgMax

```csharp
private const int _smashDmgMax = 7
```
#INC


#### Field Value

**Type:** System.Int32

### _smashDmgMin

```csharp
private const int _smashDmgMin = 10
```
#INC


#### Field Value

**Type:** System.Int32

### _smashDmgRange

```csharp
private const float _smashDmgRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### _smashProb

```csharp
private const int _smashProb = 20
```
#INC


#### Field Value

**Type:** System.Int32

### aggro

```csharp
private UnitModel aggro
```
#INC


#### Field Value

**Type:** Global.UnitModel

### atkType

```csharp
private RwbpType atkType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### effects

```csharp
public SoundEffectPlayer[] effects
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer[]

### escapeDelay

```csharp
private const float escapeDelay = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### escapeInit

```csharp
private bool escapeInit
```
#INC


#### Field Value

**Type:** System.Boolean

### isMovable

```csharp
public bool isMovable
```
#INC


#### Field Value

**Type:** System.Boolean

### isRoamer

```csharp
private bool isRoamer
```
#INC


#### Field Value

**Type:** System.Boolean

### leftSpore

```csharp
private YoungPrinceFriend.Spore leftSpore
```

#### Field Value

**Type:** Global.YoungPrinceFriend.Spore

### motionDelayTimer

```csharp
private Timer motionDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### moveTimer

```csharp
private Timer moveTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### nextSporeId

```csharp
public long nextSporeId
```
#INC


#### Field Value

**Type:** System.Int64

### passage

```csharp
private PassageObjectModel passage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### prince

```csharp
public YoungPrince prince
```
#INC


#### Field Value

**Type:** Global.YoungPrince

### rightSpore

```csharp
private YoungPrinceFriend.Spore rightSpore
```

#### Field Value

**Type:** Global.YoungPrinceFriend.Spore

### smashType

```csharp
private RwbpType smashType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### sound_Atk1

```csharp
public const string sound_Atk1 = "Atk1"
```
#INC


#### Field Value

**Type:** System.String

### sound_Atk2_Base

```csharp
public const string sound_Atk2_Base = "Atk2_base"
```
#INC


#### Field Value

**Type:** System.String

### sound_Atk2_Hit

```csharp
public const string sound_Atk2_Hit = "Atk2_atk"
```
#INC


#### Field Value

**Type:** System.String

### sound_Dead

```csharp
public const string sound_Dead = "Dead"
```
#INC


#### Field Value

**Type:** System.String

### sound_Default

```csharp
public const string sound_Default = "Default"
```
#INC


#### Field Value

**Type:** System.String

### sound_Walk

```csharp
public const string sound_Walk = "Walk"
```
#INC


#### Field Value

**Type:** System.String

### soundPath

```csharp
public const string soundPath = "creature/YoungPrince/Friend/Prince_Child_"
```
#INC


#### Field Value

**Type:** System.String

### sporeList

```csharp
private List<YoungPrinceFriend.Spore> sporeList
```

#### Field Value

**Type:** System.Collections.Generic.List{YoungPrinceFriend.Spore}

### spreadFreq

```csharp
private const float spreadFreq = 0.2
```
#INC


#### Field Value

**Type:** System.Single

### spreadTimer

```csharp
private Timer spreadTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### volume

```csharp
private const float volume = 1
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### animScript

```csharp
public YoungPrinceFriendAnim animScript { get; }
```

#### Property Value

**Type:** Global.YoungPrinceFriendAnim

### atkDmg

```csharp
private static int atkDmg { get; }
```

#### Property Value

**Type:** System.Int32

### motionDelay

```csharp
private static float motionDelay { get; }
```

#### Property Value

**Type:** System.Single

### moveFreq

```csharp
private static float moveFreq { get; }
```

#### Property Value

**Type:** System.Single

### smashDmg

```csharp
private static int smashDmg { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AttackStart()

```csharp
private void AttackStart()
```
#INC


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

### Chase()

```csharp
private void Chase()
```
#INC


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

### GetName()

```csharp
public override string GetName()
```
#INC


#### Returns

**Type:** System.String

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

### GetNearestByDoor()

```csharp
private UnitModel GetNearestByDoor()
```
#INC


#### Returns

**Type:** Global.UnitModel

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

### GetTargets(float, bool)

```csharp
private List<UnitModel> GetTargets(float range, bool needDir = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### Infest()

```csharp
private void Infest()
```
#INC


### IsAttackable(UnitModel)

```csharp
private bool IsAttackable(UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsAttacking()

```csharp
private bool IsAttacking()
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

### MakeMovement()

```csharp
private void MakeMovement()
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

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAttackDamageTimeCalled()

```csharp
public void OnAttackDamageTimeCalled()
```
#INC


### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnSmashDamageTimeCalled()

```csharp
public void OnSmashDamageTimeCalled()
```
#INC


### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### Roam()

```csharp
private void Roam()
```
#INC


### SetModel(CreatureModel)

```csharp
public override void SetModel(CreatureModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SetPrince(YoungPrince)

```csharp
public void SetPrince(YoungPrince prince)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `prince` | `Global.YoungPrince` |  |

### SpreadSpore()

```csharp
private bool SpreadSpore()
```
#INC


#### Returns

**Type:** System.Boolean

### StopMovement()

```csharp
private void StopMovement()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

