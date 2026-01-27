---
uid: Global.FixerPale
canonical_path: /api/Global/Misc/FixerPale
---

# Class FixerPale

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerPale : FixerCreature
```

Pale Fixer. Shows up only during White Dusk.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [FixerCreature](/api/Global/Creature/FixerCreature) → FixerPale

## Inherited Members
[_ordealScript](/api/Global/Creature/FixerCreature#ordealscript), [_risk](/api/Global/Creature/FixerCreature#risk), [_name](/api/Global/Creature/FixerCreature#name), [GetOrdealName()](/api/Global/Creature/FixerCreature#getordealname), [SetOrdeal(FixerOrdeal, RiskLevel, string)](/api/Global/Creature/FixerCreature#setordeal-fixerordeal-risklevel-string), [OnDie()](/api/Global/Creature/FixerCreature#ondie), [GetNearest(float, bool)](/api/Global/Creature/FixerCreature#getnearest-float-bool), [GetTargets(float, bool)](/api/Global/Creature/FixerCreature#gettargets-float-bool), [IsInRange(UnitModel, float)](/api/Global/Creature/FixerCreature#isinrange-unitmodel-float), [IsInView(UnitModel)](/api/Global/Creature/FixerCreature#isinview-unitmodel), [GetDistance(UnitModel)](/api/Global/Creature/FixerCreature#getdistance-unitmodel), [IsHostile(MovableObjectNode)](/api/Global/Creature/FixerCreature#ishostile-movableobjectnode), [GetTargetDirection(UnitModel)](/api/Global/Creature/FixerCreature#gettargetdirection-unitmodel), [Risk](/api/Global/Creature/FixerCreature#risk), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FixerPale()

```csharp
public FixerPale()
```

## Fields

### _animScript

```csharp
private FixerPaleAnim _animScript
```
#INC


#### Field Value

**Type:** Global.FixerPaleAnim

### _atkFarDmgMax

```csharp
private const int _atkFarDmgMax = 9
```
#INC


#### Field Value

**Type:** System.Int32

### _atkFarDmgMin

```csharp
private const int _atkFarDmgMin = 8
```
#INC


#### Field Value

**Type:** System.Int32

### _atkFarDmgRange

```csharp
private const float _atkFarDmgRange = 16
```
#INC


#### Field Value

**Type:** System.Single

### _atkFarRange

```csharp
private const float _atkFarRange = 15
```
#INC


#### Field Value

**Type:** System.Single

### _atkFarType

```csharp
private const RwbpType _atkFarType = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearDmgMax_1st

```csharp
private const int _atkNearDmgMax_1st = 6
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_2nd

```csharp
private const int _atkNearDmgMax_2nd = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_3rd

```csharp
private const int _atkNearDmgMax_3rd = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_4th

```csharp
private const int _atkNearDmgMax_4th = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_5th

```csharp
private const int _atkNearDmgMax_5th = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_6th

```csharp
private const int _atkNearDmgMax_6th = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMax_7th

```csharp
private const int _atkNearDmgMax_7th = 12
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_1st

```csharp
private const int _atkNearDmgMin_1st = 5
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_2nd

```csharp
private const int _atkNearDmgMin_2nd = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_3rd

```csharp
private const int _atkNearDmgMin_3rd = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_4th

```csharp
private const int _atkNearDmgMin_4th = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_5th

```csharp
private const int _atkNearDmgMin_5th = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_6th

```csharp
private const int _atkNearDmgMin_6th = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgMin_7th

```csharp
private const int _atkNearDmgMin_7th = 10
```
#INC


#### Field Value

**Type:** System.Int32

### _atkNearDmgRange

```csharp
private const float _atkNearDmgRange = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### _atkNearRange

```csharp
private const float _atkNearRange = 3
```
#INC


#### Field Value

**Type:** System.Single

### _atkNearType_1st

```csharp
private const RwbpType _atkNearType_1st = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_2nd

```csharp
private const RwbpType _atkNearType_2nd = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_3rd

```csharp
private const RwbpType _atkNearType_3rd = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_4th

```csharp
private const RwbpType _atkNearType_4th = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_5th

```csharp
private const RwbpType _atkNearType_5th = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_6th

```csharp
private const RwbpType _atkNearType_6th = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkNearType_7th

```csharp
private const RwbpType _atkNearType_7th = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _dSceneDmgMax

```csharp
private const int _dSceneDmgMax = 70
```
#INC


#### Field Value

**Type:** System.Int32

### _dSceneDmgMin

```csharp
private const int _dSceneDmgMin = 50
```
#INC


#### Field Value

**Type:** System.Int32

### _dSceneDmgRange

```csharp
private const float _dSceneDmgRange = 2
```
#INC


#### Field Value

**Type:** System.Single

### _dSceneDmgType

```csharp
private const RwbpType _dSceneDmgType = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _motionDelayMax

```csharp
private const float _motionDelayMax = 1
```
#INC


#### Field Value

**Type:** System.Single

### _motionDelayMin

```csharp
private const float _motionDelayMin = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _phase

```csharp
private FixerPale.Phase _phase
```

#### Field Value

**Type:** Global.FixerPale.Phase

### _recognizeRange

```csharp
private const float _recognizeRange = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMax

```csharp
private const float _skillCoolTimeMax = 19
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMin

```csharp
private const float _skillCoolTimeMin = 17
```
#INC


#### Field Value

**Type:** System.Single

### _skillDmgMax_1st

```csharp
private const int _skillDmgMax_1st = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgMax_2nd

```csharp
private const int _skillDmgMax_2nd = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgMin_1st

```csharp
private const int _skillDmgMin_1st = 15
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgMin_2nd

```csharp
private const int _skillDmgMin_2nd = 15
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgRange

```csharp
private const float _skillDmgRange = 9
```
#INC


#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMax

```csharp
private const float _skillInitCoolTimeMax = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMin

```csharp
private const float _skillInitCoolTimeMin = 12
```
#INC


#### Field Value

**Type:** System.Single

### _skillType_1st

```csharp
private const RwbpType _skillType_1st = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _skillType_2nd

```csharp
private const RwbpType _skillType_2nd = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _teleportCoolTimeMax

```csharp
private const float _teleportCoolTimeMax = 35
```
#INC


#### Field Value

**Type:** System.Single

### _teleportCoolTimeMin

```csharp
private const float _teleportCoolTimeMin = 25
```
#INC


#### Field Value

**Type:** System.Single

### _teleportDelayMax

```csharp
private const float _teleportDelayMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### _teleportDelayMin

```csharp
private const float _teleportDelayMin = 3.5
```
#INC


#### Field Value

**Type:** System.Single

### dmgs

```csharp
private static DamageInfo[] dmgs
```
#INC


#### Field Value

**Type:** Global.DamageInfo[]

### motionDelayTimer

```csharp
private Timer motionDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### moveTarget

```csharp
private UnitModel moveTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### skillCoolTimer

```csharp
private Timer skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportCoolTimer

```csharp
private Timer teleportCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportDelayTimer

```csharp
private Timer teleportDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Properties

### animScript

```csharp
public FixerPaleAnim animScript { get; }
```

#### Property Value

**Type:** Global.FixerPaleAnim

### atkFarDmg

```csharp
private static DamageInfo atkFarDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_1st

```csharp
private static DamageInfo atkNearDmg_1st { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_2nd

```csharp
private static DamageInfo atkNearDmg_2nd { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_3rd

```csharp
private static DamageInfo atkNearDmg_3rd { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_4th

```csharp
private static DamageInfo atkNearDmg_4th { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_5th

```csharp
private static DamageInfo atkNearDmg_5th { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_6th

```csharp
private static DamageInfo atkNearDmg_6th { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### atkNearDmg_7th

```csharp
private static DamageInfo atkNearDmg_7th { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### dSceneDmg

```csharp
private static DamageInfo dSceneDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### motionDelay

```csharp
private static float motionDelay { get; }
```

#### Property Value

**Type:** System.Single

### skillCoolTime

```csharp
private static float skillCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### skillDmg_1st

```csharp
private static DamageInfo skillDmg_1st { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### skillDmg_2nd

```csharp
private static DamageInfo skillDmg_2nd { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### skillInitCoolTime

```csharp
private static float skillInitCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### teleportCoolTime

```csharp
private static float teleportCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### teleportDelay

```csharp
private static float teleportDelay { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AttackStart(bool)

```csharp
private void AttackStart(bool isNear)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isNear` | `System.Boolean` |  |

### CanTakeDamage(UnitModel, DamageInfo)

```csharp
public override bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### CheckTeleportCondition(WorkerModel)

```csharp
private bool CheckTeleportCondition(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### GetTargetAgent(List<WorkerModel>)

```csharp
private WorkerModel GetTargetAgent(List<WorkerModel> agents)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agents` | `System.Collections.Generic.List{WorkerModel}` |  |

#### Returns

**Type:** Global.WorkerModel

### GetTeleportTarget()

```csharp
private WorkerModel GetTeleportTarget()
```
#INC


#### Returns

**Type:** Global.WorkerModel

### IsAttacking()

```csharp
private bool IsAttacking()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsInSkill()

```csharp
private bool IsInSkill()
```
#INC


#### Returns

**Type:** System.Boolean

### IsMovable()

```csharp
private bool IsMovable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSensoredInPassage()

```csharp
public override bool IsSensoredInPassage()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSuppressable()

```csharp
public override bool IsSuppressable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsTeleporting()

```csharp
private bool IsTeleporting()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeMovement()

```csharp
private void MakeMovement()
```
#INC


### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnAttackFarEnd()

```csharp
public void OnAttackFarEnd()
```
#INC


### OnDamageCalled(int)

```csharp
public void OnDamageCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnSkillEnd()

```csharp
public void OnSkillEnd()
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

### SkillStart()

```csharp
private void SkillStart()
```
#INC


### StopMovement()

```csharp
private void StopMovement()
```
#INC


### Teleport()

```csharp
public void Teleport()
```
#INC


### TeleportStart()

```csharp
private void TeleportStart()
```
#INC

