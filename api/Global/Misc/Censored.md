---
uid: Global.Censored
canonical_path: /api/Global/Misc/Censored
---

# Class Censored

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Censored : CensoredCreatureBase, IRouletteWindowMessage
```

CENSORED.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [CensoredCreatureBase](/api/Global/Misc/CensoredCreatureBase) → Censored

## Implements
[IRouletteWindowMessage](/api/Global/Misc/IRouletteWindowMessage)

## Inherited Members
[motionDelayTimer](/api/Global/Misc/CensoredCreatureBase#motiondelaytimer), [_motionDelayMax](/api/Global/Misc/CensoredCreatureBase#motiondelaymax), [_motionDelayMin](/api/Global/Misc/CensoredCreatureBase#motiondelaymin), [_agentLevelCondition](/api/Global/Misc/CensoredCreatureBase#agentlevelcondition), [recognizeRange](/api/Global/Misc/CensoredCreatureBase#recognizerange), [attackRange](/api/Global/Misc/CensoredCreatureBase#attackrange), [attackDmgRange](/api/Global/Misc/CensoredCreatureBase#attackdmgrange), [GetNearest(float, bool)](/api/Global/Misc/CensoredCreatureBase#getnearest-float-bool), [GetTargets(float, bool)](/api/Global/Misc/CensoredCreatureBase#gettargets-float-bool), [IsInRange(UnitModel, float)](/api/Global/Misc/CensoredCreatureBase#isinrange-unitmodel-float), [IsInView(UnitModel)](/api/Global/Misc/CensoredCreatureBase#isinview-unitmodel), [GetDistance(UnitModel)](/api/Global/Misc/CensoredCreatureBase#getdistance-unitmodel), [IsHostile(MovableObjectNode)](/api/Global/Misc/CensoredCreatureBase#ishostile-movableobjectnode), [GetTargetDirection(UnitModel)](/api/Global/Misc/CensoredCreatureBase#gettargetdirection-unitmodel), [CheckNear()](/api/Global/Misc/CensoredCreatureBase#checknear), [motionDelay](/api/Global/Misc/CensoredCreatureBase#motiondelay), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Censored()

```csharp
public Censored()
```

## Fields

### _animScript

```csharp
private CensoredAnim _animScript
```
#INC


#### Field Value

**Type:** Global.CensoredAnim

### _attackDmgMax

```csharp
private const int _attackDmgMax = 26
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgMin

```csharp
private const int _attackDmgMin = 23
```
#INC


#### Field Value

**Type:** System.Int32

### _attackDmgRange

```csharp
private const float _attackDmgRange = 4
```
#INC


#### Field Value

**Type:** System.Single

### _attackRange

```csharp
private const float _attackRange = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### _childOrigin

```csharp
private WorkerModel _childOrigin
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### _currentVictim

```csharp
private WorkerModel _currentVictim
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### _dead

```csharp
private WorkerModel _dead
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### _deadDmgMax

```csharp
private const int _deadDmgMax = 17
```
#INC


#### Field Value

**Type:** System.Int32

### _deadDmgMin

```csharp
private const int _deadDmgMin = 12
```
#INC


#### Field Value

**Type:** System.Int32

### _deadSceneRange

```csharp
private const float _deadSceneRange = 0
```
#INC


#### Field Value

**Type:** System.Single

### _deadWorkerSpeed

```csharp
private const float _deadWorkerSpeed = 3
```
#INC


#### Field Value

**Type:** System.Single

### _healRatio

```csharp
private const float _healRatio = 0.05
```
#INC


#### Field Value

**Type:** System.Single

### _inSkill

```csharp
private bool _inSkill
```
#INC


#### Field Value

**Type:** System.Boolean

### _isKilling

```csharp
private bool _isKilling
```
#INC


#### Field Value

**Type:** System.Boolean

### _lootRange

```csharp
private const float _lootRange = 0.2
```
#INC


#### Field Value

**Type:** System.Single

### _qliphothCounterMax

```csharp
private const int _qliphothCounterMax = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _recognizeRange

```csharp
private const float _recognizeRange = 30
```
#INC


#### Field Value

**Type:** System.Single

### _sound_atk

```csharp
private const string _sound_atk = "attack"
```
#INC


#### Field Value

**Type:** System.String

### _sound_dScene

```csharp
private const string _sound_dScene = "deadScene"
```
#INC


#### Field Value

**Type:** System.String

### _sound_heal

```csharp
private const string _sound_heal = "heal"
```
#INC


#### Field Value

**Type:** System.String

### _sound_sacri

```csharp
private const string _sound_sacri = "sacrifice"
```
#INC


#### Field Value

**Type:** System.String

### attackType

```csharp
private RwbpType attackType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### deadDmgType

```csharp
private RwbpType deadDmgType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### HealHorrorDamage

```csharp
private static DamageInfo HealHorrorDamage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

## Properties

### animScript

```csharp
public CensoredAnim animScript { get; }
```

#### Property Value

**Type:** Global.CensoredAnim

### attackDmg

```csharp
private static int attackDmg { get; }
```

#### Property Value

**Type:** System.Int32

### deadDmg

```csharp
private static int deadDmg { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### AttackStart()

```csharp
protected override void AttackStart()
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

### Escape()

```csharp
public override void Escape()
```
#INC


### ExplodeDead()

```csharp
public void ExplodeDead()
```
#INC


### GetDeads()

```csharp
private List<WorkerModel> GetDeads()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

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

### HasUniqueCommandAction(int)

```csharp
public override bool HasUniqueCommandAction(int workType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### Heal()

```csharp
public void Heal()
```
#INC


### Init()

```csharp
private void Init()
```
#INC


### InvokeNearMentalDamage()

```csharp
private void InvokeNearMentalDamage()
```
#INC


### IsInDeadScene()

```csharp
private bool IsInDeadScene()
```
#INC


#### Returns

**Type:** System.Boolean

### IsMovable()

```csharp
protected override bool IsMovable()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeChild()

```csharp
public void MakeChild()
```
#INC


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

### MakeExplodeEffect(WorkerModel, float)

```csharp
public void MakeExplodeEffect(WorkerModel target, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### MakeMovement()

```csharp
protected override void MakeMovement()
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

### MakeSound(string, float)

```csharp
public override SoundEffectPlayer MakeSound(string src, float volume = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `volume` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

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


### OnCameraMoveEnd()

```csharp
public void OnCameraMoveEnd()
```
#INC


### OnDeadSceneEnd()

```csharp
public void OnDeadSceneEnd()
```
#INC


### OnDeadSceneStart()

```csharp
public void OnDeadSceneStart()
```
#INC


### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFirstHeal()

```csharp
public void OnFirstHeal()
```
#INC


### OnGiveDeadSceneDmg()

```csharp
public void OnGiveDeadSceneDmg()
```
#INC


### OnOpenCommandWindow(Button[])

```csharp
public override void OnOpenCommandWindow(Button[] buttons)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```
#INC


#### Returns

**Type:** System.Boolean

### OnReleaseWork(UseSkill)

```csharp
public override void OnReleaseWork(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReturn()

```csharp
public override void OnReturn()
```
#INC


### OnSacrificeFail()

```csharp
public void OnSacrificeFail()
```
#INC


### OnSacrificeSuccess()

```csharp
public void OnSacrificeSuccess()
```
#INC


### OnSpecialEnd()

```csharp
public void OnSpecialEnd()
```
#INC


### OnStageEnd()

```csharp
public override void OnStageEnd()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### OnVictimArrived()

```csharp
public void OnVictimArrived()
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

### OnWorkerAllocated(WorkerModel)

```csharp
public void OnWorkerAllocated(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OpenRouletteWindow()

```csharp
private void OpenRouletteWindow()
```
#INC


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated


### RouletteCancel()

```csharp
public void RouletteCancel()
```
#INC


### RouletteOpen()

```csharp
public void RouletteOpen()
```
#INC


### Sacrifice()

```csharp
public void Sacrifice()
```
#INC


### SelectVictim()

```csharp
public void SelectVictim()
```
#INC


### SetDeadScene(WorkerModel)

```csharp
private void SetDeadScene(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### SpecialStart(WorkerModel)

```csharp
private void SpecialStart(WorkerModel dead)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dead` | `Global.WorkerModel` |  |

### StartSacrifice()

```csharp
private void StartSacrifice()
```
#INC


### StopMovement()

```csharp
protected override void StopMovement()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC


### VictimAllocated()

```csharp
private void VictimAllocated()
```
#INC

