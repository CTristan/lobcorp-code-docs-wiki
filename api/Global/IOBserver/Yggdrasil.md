---
uid: Global.Yggdrasil
canonical_path: /api/Global/IOBserver/Yggdrasil
---

# Class Yggdrasil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Yggdrasil : CreatureBase, IObserver
```

Parasite Tree.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → Yggdrasil

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Yggdrasil()

```csharp
public Yggdrasil()
```

## Fields

### _animScript

```csharp
private YggdrasilAnim _animScript
```
#INC


#### Field Value

**Type:** Global.YggdrasilAnim

### _defaultSoundFreqMax

```csharp
private const float _defaultSoundFreqMax = 10
```
#INC


#### Field Value

**Type:** System.Single

### _defaultSoundFreqMin

```csharp
private const float _defaultSoundFreqMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _FILTER_NAME

```csharp
private const string _FILTER_NAME = "YggdrasilSporeFilter"
```
#INC


#### Field Value

**Type:** System.String

### _FILTER_SRC

```csharp
private const string _FILTER_SRC = "Sprites/CreatureSprite/Yggdrasil/filter_hall"
```
#INC


#### Field Value

**Type:** System.String

### _PASSAGE_DMG_MAX

```csharp
private const int _PASSAGE_DMG_MAX = 12
```
#INC


#### Field Value

**Type:** System.Int32

### _PASSAGE_DMG_MIN

```csharp
private const int _PASSAGE_DMG_MIN = 9
```
#INC


#### Field Value

**Type:** System.Int32

### _PASSAGE_DMG_TYPE

```csharp
private const RwbpType _PASSAGE_DMG_TYPE = W
```
#INC


#### Field Value

**Type:** Global.RwbpType

### BLESS_OVERLOAD_CNT

```csharp
private int BLESS_OVERLOAD_CNT
```
#INC


#### Field Value

**Type:** System.Int32

### blessedList

```csharp
private List<WorkerModel> blessedList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### blessTarget

```csharp
private WorkerModel blessTarget
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### defaultSoundTimer

```csharp
private Timer defaultSoundTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### FILTER_DECREASE_TIME

```csharp
private const float FILTER_DECREASE_TIME = 1
```
#INC


#### Field Value

**Type:** System.Single

### FILTER_INCREASE_TIME

```csharp
private const float FILTER_INCREASE_TIME = 1
```
#INC


#### Field Value

**Type:** System.Single

### filterDecreaseTimer

```csharp
private Timer filterDecreaseTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### filterIncreaseTimer

```csharp
private Timer filterIncreaseTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### gonnaSubQliphoth

```csharp
private bool gonnaSubQliphoth
```
#INC


#### Field Value

**Type:** System.Boolean

### infestedPassages

```csharp
private Dictionary<PassageObjectModel, Yggdrasil.InfestedPassage> infestedPassages
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{PassageObjectModel,Yggdrasil.InfestedPassage}

### isInSkill

```csharp
private bool isInSkill
```
#INC


#### Field Value

**Type:** System.Boolean

### loopSound

```csharp
private SoundEffectPlayer loopSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### SUB_QLIPHOTH_ESCAPE_PROB

```csharp
private float SUB_QLIPHOTH_ESCAPE_PROB
```
#INC


#### Field Value

**Type:** System.Single

### SUB_QLIPHOTH_WORK_OHTER_CNT

```csharp
private int SUB_QLIPHOTH_WORK_OHTER_CNT
```
#INC


#### Field Value

**Type:** System.Int32

### TARGET_SKILL_ID

```csharp
private int TARGET_SKILL_ID
```
#INC


#### Field Value

**Type:** System.Int32

### workOtherCnt

```csharp
private int workOtherCnt
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### animScript

```csharp
public YggdrasilAnim animScript { get; }
```

#### Property Value

**Type:** Global.YggdrasilAnim

### BlessedCnt

```csharp
private int BlessedCnt { get; }
```

#### Property Value

**Type:** System.Int32

### ChildAlive

```csharp
private bool ChildAlive { get; }
```

#### Property Value

**Type:** System.Boolean

### DEFAULT_SOUND_FREQ

```csharp
private static float DEFAULT_SOUND_FREQ { get; }
```

#### Property Value

**Type:** System.Single

### PassageDmg

```csharp
public static DamageInfo PassageDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### ActivateSkill()

```csharp
private void ActivateSkill()
```
#INC


### AddBlessedList(WorkerModel)

```csharp
public void AddBlessedList(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AddFilters(float)

```csharp
private void AddFilters(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### AddFlower()

```csharp
private void AddFlower()
```
#INC


### AddWorkCount()

```csharp
private void AddWorkCount()
```
#INC


### Attract(WorkerModel)

```csharp
private void Attract(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### Bless(WorkerModel)

```csharp
private void Bless(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### BlessOverload()

```csharp
private void BlessOverload()
```
#INC


### BlessOverloadEnd()

```csharp
private void BlessOverloadEnd()
```
#INC


### BlessStart()

```csharp
private void BlessStart()
```
#INC


### CancelAttract(WorkerModel)

```csharp
public void CancelAttract(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### CheckAttractCondition(WorkerModel)

```csharp
private bool CheckAttractCondition(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### CheckBlessCondition(WorkerModel)

```csharp
private bool CheckBlessCondition(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### GetAttractTargets()

```csharp
private WorkerModel[] GetAttractTargets()
```
#INC


#### Returns

**Type:** Global.WorkerModel[]

### GetAttractTargets(Sefira)

```csharp
private WorkerModel[] GetAttractTargets(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.WorkerModel[]

### GetSoundSrc(string)

```csharp
private string GetSoundSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetTargets(PassageObjectModel)

```csharp
public UnitModel[] GetTargets(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.UnitModel[]

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```
#INC


#### Returns

**Type:** System.Boolean

### InitFlower()

```csharp
private void InitFlower()
```
#INC


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

### IsTransformed()

```csharp
private bool IsTransformed()
```
#INC


#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public override bool IsWorkable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeChildCreature(UnitModel)

```csharp
public override ChildCreatureModel MakeChildCreature(UnitModel origin)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.ChildCreatureModel

### MakeSound(string, Vector3, float)

```csharp
public SoundEffectPlayer MakeSound(string src, Vector3 pos, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string, Transform, float)

```csharp
public SoundEffectPlayer MakeSoundLoop(string src, Transform trans, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `trans` | `UnityEngine.Transform` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnArrive(WorkerModel)

```csharp
public void OnArrive(WorkerModel arrived)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `arrived` | `Global.WorkerModel` |  |

### OnChildSuppressed(ChildCreatureModel)

```csharp
public override void OnChildSuppressed(ChildCreatureModel child)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.ChildCreatureModel` |  |

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFinishWork(UseSkill)

```csharp
public override void OnFinishWork(UseSkill skill)
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

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### OnWorkerAnimCalled(int)

```csharp
public void OnWorkerAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### ReduceFilters(float)

```csharp
private void ReduceFilters(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### ReduceFlower()

```csharp
private void ReduceFlower()
```
#INC


### RemoveBlessedWorker(WorkerModel)

```csharp
public void RemoveBlessedWorker(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### RemoveLoopSound()

```csharp
private void RemoveLoopSound()
```
#INC


### Reset()

```csharp
private void Reset()
```
#INC


### ResetWorkCount()

```csharp
private void ResetWorkCount()
```
#INC


### SetFilters(float)

```csharp
private void SetFilters(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetTransform(bool)

```csharp
private void SetTransform(bool isTransform)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isTransform` | `System.Boolean` |  |

### SubQliphothCounter()

```csharp
private void SubQliphothCounter()
```
#INC

