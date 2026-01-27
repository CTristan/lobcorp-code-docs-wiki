---
uid: WhiteNightSpace.PlagueDoctor
canonical_path: /api/WhiteNightSpace/PlagueDoctor
---

# Class PlagueDoctor

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlagueDoctor : CreatureBase, IObserver
```

Plague Doctor!!!!!!!!!!


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → PlagueDoctor

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PlagueDoctor()

```csharp
public PlagueDoctor()
```

## Fields

### _angel

```csharp
private DeathAngel _angel
```
#INC


#### Field Value

**Type:** WhiteNightSpace.DeathAngel

### _animScript

```csharp
private PlagueDoctorAnim _animScript
```
#INC


#### Field Value

**Type:** WhiteNightSpace.PlagueDoctorAnim

### _apostleCount

```csharp
private const int _apostleCount = 12
```
#INC


#### Field Value

**Type:** System.Int32

### _attractFreq

```csharp
private static MinMax _attractFreq
```
#INC


#### Field Value

**Type:** Global.MinMax

### _currentKissAnim

```csharp
private Animator _currentKissAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### _currentKissTarget

```csharp
private AgentModel _currentKissTarget
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _currentWork

```csharp
private UseSkill _currentWork
```
#INC


#### Field Value

**Type:** Global.UseSkill

### _genData

```csharp
private List<ApostleGenData> _genData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}

### _genDay

```csharp
private int _genDay
```
#INC


#### Field Value

**Type:** System.Int32

### _isKiss

```csharp
private bool _isKiss
```
#INC


#### Field Value

**Type:** System.Boolean

### _kissDurationTimer

```csharp
private Timer _kissDurationTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _kissEnd_1

```csharp
private static float _kissEnd_1
```
#INC


#### Field Value

**Type:** System.Single

### _kissEndTimer

```csharp
private Timer _kissEndTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _kissMovementTimer

```csharp
private Timer _kissMovementTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _kissSound

```csharp
private SoundEffectPlayer _kissSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### _kissTargetInitialScale

```csharp
private Vector3 _kissTargetInitialScale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### _kissTime

```csharp
private static MinMax _kissTime
```
#INC


#### Field Value

**Type:** Global.MinMax

### _save

```csharp
private static string[] _save
```
#INC


#### Field Value

**Type:** System.String[]

### _workerAnimatorScale

```csharp
private static float _workerAnimatorScale
```
#INC


#### Field Value

**Type:** System.Single

### AdventLevel

```csharp
private const int AdventLevel = 12
```
#INC


#### Field Value

**Type:** System.Int32

### apostleData

```csharp
private List<ApostleData> apostleData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleData}

### Bell

```csharp
public const string Bell = "creature/deathangel/Lucifer_Bell0"
```
#INC


#### Field Value

**Type:** System.String

### giftId

```csharp
public static int giftId
```
#INC


#### Field Value

**Type:** System.Int32

### ID

```csharp
public static long ID
```
#INC


#### Field Value

**Type:** System.Int64

### KissSoundSrc

```csharp
public static string KissSoundSrc
```
#INC


#### Field Value

**Type:** System.String

### QliphothCounterMax

```csharp
private const int QliphothCounterMax = 1
```
#INC


#### Field Value

**Type:** System.Int32

### TickSound

```csharp
public const string TickSound = "creature/deathangel/Lucifer_Tick1"
```
#INC


#### Field Value

**Type:** System.String

### WhiteNightID

```csharp
public static long WhiteNightID
```
#INC


#### Field Value

**Type:** System.Int64

## Properties

### AnimScript

```csharp
public PlagueDoctorAnim AnimScript { get; }
```

#### Property Value

**Type:** WhiteNightSpace.PlagueDoctorAnim

### ApostleLevel

```csharp
public int ApostleLevel { get; }
```

#### Property Value

**Type:** System.Int32

### AttractFreq

```csharp
private static float AttractFreq { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### AddApostle(AgentModel)

```csharp
public void AddApostle(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### AdventWhiteNight()

```csharp
public void AdventWhiteNight()
```
#INC


### BlessedAgentWorkCheck()

```csharp
public bool BlessedAgentWorkCheck()
```
#INC


#### Returns

**Type:** System.Boolean

### CancelAttract()

```csharp
public void CancelAttract()
```
#INC


### ChangeIsolateRoom()

```csharp
public void ChangeIsolateRoom()
```
#INC


### CheckAdvent()

```csharp
public static bool CheckAdvent()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckApostle(AgentModel)

```csharp
public bool CheckApostle(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### ClearKiss()

```csharp
public void ClearKiss()
```
#INC


### ClearKissSound()

```csharp
private void ClearKissSound()
```
#INC


### GenDeathAngel()

```csharp
public CreatureModel GenDeathAngel()
```
#INC


#### Returns

**Type:** Global.CreatureModel

### GetApostleDesc(int)

```csharp
public CreatureStaticData.ParameterData GetApostleDesc(int targetindex)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetindex` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetApostleDescRefined(int)

```csharp
public string GetApostleDescRefined(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetApostleDescRefined(int, List<ApostleGenData>)

```csharp
public static string GetApostleDescRefined(int index, List<ApostleGenData> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `data` | `System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}` |  |

#### Returns

**Type:** System.String

### GetApostleNames()

```csharp
public List<string> GetApostleNames()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetApostleSaveData()

```csharp
private Dictionary<int, Dictionary<string, object>> GetApostleSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.Dictionary{System.String,System.Object}}

### GetSaveData()

```csharp
public override Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```
#INC


#### Returns

**Type:** System.Boolean

### HasScriptSaveData()

```csharp
public override bool HasScriptSaveData()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueCollectionCost(string, out string)

```csharp
public override bool HasUniqueCollectionCost(string areaName, out string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `areaName` | `System.String` |  |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### IsKissing()

```csharp
public bool IsKissing()
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

### LoadApostleSaveData(int, Dictionary<int, Dictionary<string, object>>)

```csharp
private void LoadApostleSaveData(int max, Dictionary<int, Dictionary<string, object>> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |
| `data` | `System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.Dictionary{System.String,System.Object}}` |  |

### LoadData(Dictionary<string, object>)

```csharp
public override void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

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

### MoveWorkerToCustomNode(WorkerModel)

```csharp
private void MoveWorkerToCustomNode(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnAdventEnd()

```csharp
public void OnAdventEnd()
```
#INC


### OnClockUIEnd()

```csharp
public void OnClockUIEnd()
```
#INC


### OnEndKiss()

```csharp
public void OnEndKiss()
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

### OnGamemanagerInit()

```csharp
public override void OnGamemanagerInit()
```
#INC


### OnInit()

```csharp
public override void OnInit()
```
#INC
#code-generated


### OnInitialBuild()

```csharp
public override void OnInitialBuild()
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

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnPlagueDoctorAdventEnd()

```csharp
public void OnPlagueDoctorAdventEnd()
```
#INC


### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### StartKiss(AgentModel)

```csharp
public void StartKiss(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |
