---
uid: Global.FixerClaw
canonical_path: /api/Global/Misc/FixerClaw
---

# Class FixerClaw

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerClaw : FixerCreature
```

The Claw.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [FixerCreature](/api/Global/Creature/FixerCreature) → FixerClaw

## Inherited Members
[_ordealScript](/api/Global/Creature/FixerCreature#ordealscript), [_risk](/api/Global/Creature/FixerCreature#risk), [_name](/api/Global/Creature/FixerCreature#name), [GetOrdealName()](/api/Global/Creature/FixerCreature#getordealname), [SetOrdeal(FixerOrdeal, RiskLevel, string)](/api/Global/Creature/FixerCreature#setordeal-fixerordeal-risklevel-string), [OnDie()](/api/Global/Creature/FixerCreature#ondie), [GetNearest(float, bool)](/api/Global/Creature/FixerCreature#getnearest-float-bool), [GetTargets(float, bool)](/api/Global/Creature/FixerCreature#gettargets-float-bool), [IsInRange(UnitModel, float)](/api/Global/Creature/FixerCreature#isinrange-unitmodel-float), [IsInView(UnitModel)](/api/Global/Creature/FixerCreature#isinview-unitmodel), [GetDistance(UnitModel)](/api/Global/Creature/FixerCreature#getdistance-unitmodel), [IsHostile(MovableObjectNode)](/api/Global/Creature/FixerCreature#ishostile-movableobjectnode), [GetTargetDirection(UnitModel)](/api/Global/Creature/FixerCreature#gettargetdirection-unitmodel), [Risk](/api/Global/Creature/FixerCreature#risk), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Creature/CreatureBase#uniqueescape), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FixerClaw()

```csharp
public FixerClaw()
```

## Fields

### _animScript

```csharp
private FixerClawAnim _animScript
```
#INC


#### Field Value

**Type:** Global.FixerClawAnim

### _atkDmgMax

```csharp
private const int _atkDmgMax = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _atkDmgMin

```csharp
private const int _atkDmgMin = 15
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

### _atkDmgType

```csharp
private const RwbpType _atkDmgType = R
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkRange

```csharp
private const float _atkRange = 3
```
#INC


#### Field Value

**Type:** System.Single

### _atkSpecialProb

```csharp
private const float _atkSpecialProb = 0.4
```
#INC


#### Field Value

**Type:** System.Single

### _blueAtkMax

```csharp
private const int _blueAtkMax = 8
```
#INC


#### Field Value

**Type:** System.Int32

### _blueAttackTimeMax

```csharp
private const float _blueAttackTimeMax = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _blueAttackTimeMin

```csharp
private const float _blueAttackTimeMin = 0.45
```
#INC


#### Field Value

**Type:** System.Single

### _blueCapsuleProb

```csharp
private const float _blueCapsuleProb = 0.4
```
#INC


#### Field Value

**Type:** System.Single

### _blueDmgMax

```csharp
private const int _blueDmgMax = 35
```
#INC


#### Field Value

**Type:** System.Int32

### _blueDmgMin

```csharp
private const int _blueDmgMin = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _blueDmgType

```csharp
private const RwbpType _blueDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _cancelNeededDmg

```csharp
private const float _cancelNeededDmg = 200
```
#INC


#### Field Value

**Type:** System.Single

### _capsuleCoolTimeMax

```csharp
private const float _capsuleCoolTimeMax = 45
```
#INC


#### Field Value

**Type:** System.Single

### _capsuleCoolTimeMin

```csharp
private const float _capsuleCoolTimeMin = 40
```
#INC


#### Field Value

**Type:** System.Single

### _capsuleInitCoolTimeMax

```csharp
private const float _capsuleInitCoolTimeMax = 30
```
#INC


#### Field Value

**Type:** System.Single

### _capsuleInitCoolTimeMin

```csharp
private const float _capsuleInitCoolTimeMin = 30
```
#INC


#### Field Value

**Type:** System.Single

### _colliderSrc

```csharp
private const string _colliderSrc = "Effect/Creature/FixerClaw/FixerClawUltimateCollider"
```
#INC


#### Field Value

**Type:** System.String

### _greenCapsuleNeededDmg

```csharp
private const float _greenCapsuleNeededDmg = 120
```
#INC


#### Field Value

**Type:** System.Single

### _groggyTimeMax

```csharp
private const float _groggyTimeMax = 12
```
#INC


#### Field Value

**Type:** System.Single

### _groggyTimeMin

```csharp
private const float _groggyTimeMin = 10
```
#INC


#### Field Value

**Type:** System.Single

### _healEffectSrc

```csharp
private const string _healEffectSrc = "Effect/RecoverHP"
```
#INC


#### Field Value

**Type:** System.String

### _healTimeMax

```csharp
private const float _healTimeMax = 10
```
#INC


#### Field Value

**Type:** System.Single

### _healTimeMin

```csharp
private const float _healTimeMin = 8
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMax

```csharp
private const float _healValueMax = 150
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMin

```csharp
private const float _healValueMin = 150
```
#INC


#### Field Value

**Type:** System.Single

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

### _movementScale_Orange

```csharp
private const float _movementScale_Orange = 25
```
#INC


#### Field Value

**Type:** System.Single

### _orangeDmgMax

```csharp
private const int _orangeDmgMax = 100
```
#INC


#### Field Value

**Type:** System.Int32

### _orangeDmgMin

```csharp
private const int _orangeDmgMin = 100
```
#INC


#### Field Value

**Type:** System.Int32

### _orangeDmgRange

```csharp
private const float _orangeDmgRange = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _orangeDmgType

```csharp
private const RwbpType _orangeDmgType = R
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _phase

```csharp
private FixerClaw.Phase _phase
```

#### Field Value

**Type:** Global.FixerClaw.Phase

### _recognizeRange

```csharp
private const float _recognizeRange = 15
```
#INC


#### Field Value

**Type:** System.Single

### _strFirstDmgMax

```csharp
private const int _strFirstDmgMax = 40
```
#INC


#### Field Value

**Type:** System.Int32

### _strFirstDmgMin

```csharp
private const int _strFirstDmgMin = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _strFirstDmgType

```csharp
private const RwbpType _strFirstDmgType = R
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _strongBloodEffectSrc

```csharp
private const string _strongBloodEffectSrc = "Effect/Creature/FixerClaw/FixerClawStrongBlood"
```
#INC


#### Field Value

**Type:** System.String

### _strSecondDmgMax

```csharp
private const int _strSecondDmgMax = 40
```
#INC


#### Field Value

**Type:** System.Int32

### _strSecondDmgMin

```csharp
private const int _strSecondDmgMin = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _strSecondDmgType

```csharp
private const RwbpType _strSecondDmgType = R
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _ultiAtkMax

```csharp
private const int _ultiAtkMax = 6
```
#INC


#### Field Value

**Type:** System.Int32

### _ultiAttackTimeMax

```csharp
private const float _ultiAttackTimeMax = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _ultiAttackTimeMin

```csharp
private const float _ultiAttackTimeMin = 0.45
```
#INC


#### Field Value

**Type:** System.Single

### _ultiCapsuleCoolTimeMax

```csharp
private const float _ultiCapsuleCoolTimeMax = 85
```
#INC


#### Field Value

**Type:** System.Single

### _ultiCapsuleCoolTimeMin

```csharp
private const float _ultiCapsuleCoolTimeMin = 60
```
#INC


#### Field Value

**Type:** System.Single

### _ultiCastingTimeMax

```csharp
private const float _ultiCastingTimeMax = 9
```
#INC


#### Field Value

**Type:** System.Single

### _ultiCastingTimeMin

```csharp
private const float _ultiCastingTimeMin = 6
```
#INC


#### Field Value

**Type:** System.Single

### _ultiCondition_Hp

```csharp
private const float _ultiCondition_Hp = 0.25
```
#INC


#### Field Value

**Type:** System.Single

### _ultiDmgMax

```csharp
private const int _ultiDmgMax = 85
```
#INC


#### Field Value

**Type:** System.Int32

### _ultiDmgMin

```csharp
private const int _ultiDmgMin = 60
```
#INC


#### Field Value

**Type:** System.Int32

### _ultiDmgType

```csharp
private const RwbpType _ultiDmgType = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _ultiMoveDmgMax

```csharp
private const int _ultiMoveDmgMax = 65
```
#INC


#### Field Value

**Type:** System.Int32

### _ultiMoveDmgMin

```csharp
private const int _ultiMoveDmgMin = 60
```
#INC


#### Field Value

**Type:** System.Int32

### _ultiMoveDmgType

```csharp
private const RwbpType _ultiMoveDmgType = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### accumulatedDmg_green

```csharp
private float accumulatedDmg_green
```
#INC


#### Field Value

**Type:** System.Single

### accumulatedDmg_groggy

```csharp
private float accumulatedDmg_groggy
```
#INC


#### Field Value

**Type:** System.Single

### blueAttackTimer

```csharp
private Timer blueAttackTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### capsuleCoolTimer

```csharp
private Timer capsuleCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### damagedUnits

```csharp
private List<UnitModel> damagedUnits
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### groggyTimer

```csharp
private Timer groggyTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### healTimer

```csharp
private Timer healTimer
```
#INC


#### Field Value

**Type:** Global.Timer

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

### orangeTargetNode

```csharp
private MapNode orangeTargetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### skillTargets

```csharp
private List<UnitModel> skillTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### speedUp

```csharp
private bool speedUp
```
#INC


#### Field Value

**Type:** System.Boolean

### ultiAttackTimer

```csharp
private Timer ultiAttackTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### ultiCapsuleCoolTimer

```csharp
private Timer ultiCapsuleCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### ultiCastingTimer

```csharp
private Timer ultiCastingTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Properties

### animScript

```csharp
public FixerClawAnim animScript { get; }
```

#### Property Value

**Type:** Global.FixerClawAnim

### atkDmg

```csharp
private static DamageInfo atkDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### blueAttackTime

```csharp
private static float blueAttackTime { get; }
```

#### Property Value

**Type:** System.Single

### blueDmg

```csharp
private static DamageInfo blueDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### capsuleCoolTime

```csharp
private static float capsuleCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### capsuleInitCoolTime

```csharp
private static float capsuleInitCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### groggyTime

```csharp
private static float groggyTime { get; }
```

#### Property Value

**Type:** System.Single

### healTime

```csharp
private static float healTime { get; }
```

#### Property Value

**Type:** System.Single

### healValue

```csharp
private static float healValue { get; }
```

#### Property Value

**Type:** System.Single

### motionDelay

```csharp
private static float motionDelay { get; }
```

#### Property Value

**Type:** System.Single

### orangeDmg

```csharp
private static DamageInfo orangeDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### strFirstDmg

```csharp
private static DamageInfo strFirstDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### strSecondDmg

```csharp
private static DamageInfo strSecondDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### ultiAttackTime

```csharp
private static float ultiAttackTime { get; }
```

#### Property Value

**Type:** System.Single

### ultiCapsuleCoolTime

```csharp
private static float ultiCapsuleCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### ultiCastingTime

```csharp
private static float ultiCastingTime { get; }
```

#### Property Value

**Type:** System.Single

### ultiDmg

```csharp
private static DamageInfo ultiDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### ultiMoveDmg

```csharp
private static DamageInfo ultiMoveDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### AttackLast()

```csharp
private void AttackLast()
```
#INC


### AttackNext()

```csharp
private void AttackNext()
```
#INC


### AttackStart()

```csharp
private void AttackStart()
```
#INC


### BlueAttackNext()

```csharp
private void BlueAttackNext()
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

### CheckPassage(PassageObjectModel)

```csharp
private bool CheckPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** System.Boolean

### CheckTargetCondition(UnitModel)

```csharp
private bool CheckTargetCondition(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CheckUlti()

```csharp
private bool CheckUlti()
```
#INC


#### Returns

**Type:** System.Boolean

### ClearSkillTarget(UnitModel)

```csharp
private void ClearSkillTarget(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ClearSkillTargets()

```csharp
private void ClearSkillTargets()
```
#INC


### GetAvailableTargets()

```csharp
private List<UnitModel> GetAvailableTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetHorizontalPassages()

```csharp
private List<PassageObjectModel> GetHorizontalPassages()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetNextTarget()

```csharp
private UnitModel GetNextTarget()
```
#INC


#### Returns

**Type:** Global.UnitModel

### GetOrangeTargetNode()

```csharp
private MapNode GetOrangeTargetNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetSidePassages(PassageObjectModel)

```csharp
private List<PassageObjectModel> GetSidePassages(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetSkillTargets(Capsule)

```csharp
private bool GetSkillTargets(FixerClaw.Capsule capsule)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `capsule` | `Global.FixerClaw.Capsule` |  |

#### Returns

**Type:** System.Boolean

### GetSkillType()

```csharp
private FixerClaw.Capsule GetSkillType()
```

#### Returns

**Type:** Global.FixerClaw.Capsule

### GetTargetNode()

```csharp
private MapNode GetTargetNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetTargetNodes()

```csharp
private List<MapNode> GetTargetNodes()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{MapNode}

### GiveDamage(UnitModel, DamageInfo)

```csharp
private void GiveDamage(UnitModel target, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### GroggyTimerEnd()

```csharp
private void GroggyTimerEnd()
```
#INC


### HasEscapeUI()

```csharp
public override bool HasEscapeUI()
```
#INC


#### Returns

**Type:** System.Boolean

### Heal()

```csharp
private void Heal()
```
#INC


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

### MakeClawEffects(string, bool)

```csharp
private void MakeClawEffects(string src, bool setParent = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `setParent` | `System.Boolean` |  |

### MakeEffect(GameObject, string, bool)

```csharp
private GameObject MakeEffect(GameObject position, string src, bool setParent = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.GameObject` |  |
| `src` | `System.String` |  |
| `setParent` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

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


### OnBlueAttackEnd()

```csharp
public void OnBlueAttackEnd()
```
#INC


### OnBlueAttackStart()

```csharp
public void OnBlueAttackStart()
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

### OnFixedUpdate_Capsule_All()

```csharp
private void OnFixedUpdate_Capsule_All()
```
#INC


### OnFixedUpdate_Default()

```csharp
private void OnFixedUpdate_Default()
```
#INC


### OnFixedUpdate_Groggy()

```csharp
private void OnFixedUpdate_Groggy()
```
#INC


### OnFixedUpdate_Skill_All()

```csharp
private void OnFixedUpdate_Skill_All()
```
#INC


### OnFixedUpdate_Skill_Blue()

```csharp
private void OnFixedUpdate_Skill_Blue()
```
#INC


### OnFixedUpdate_Skill_Green()

```csharp
private void OnFixedUpdate_Skill_Green()
```
#INC


### OnFixedUpdate_Skill_Orange()

```csharp
private void OnFixedUpdate_Skill_Orange()
```
#INC


### OnGroggyEnd()

```csharp
public void OnGroggyEnd()
```
#INC


### OnOrangeArrive()

```csharp
public void OnOrangeArrive()
```
#INC


### OnOrangeRunStart()

```csharp
public void OnOrangeRunStart()
```
#INC


### OnSkillEnd()

```csharp
public void OnSkillEnd()
```
#INC


### OnStartHealing()

```csharp
public void OnStartHealing()
```
#INC


### OnStrongAttack(bool)

```csharp
public void OnStrongAttack(bool isFirst)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isFirst` | `System.Boolean` |  |

### OnTakeDamage(UnitModel, DamageInfo, float)

```csharp
public override void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
| `value` | `System.Single` |  |

### OnTakeDamage_Capsule(float)

```csharp
private void OnTakeDamage_Capsule(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### OnUltimateAttackEnd()

```csharp
public void OnUltimateAttackEnd()
```
#INC


### OnUltimateAttackStart()

```csharp
public void OnUltimateAttackStart()
```
#INC


### OnUltimateCollide(UnitModel)

```csharp
public bool OnUltimateCollide(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### OnUltimateSkillEnd()

```csharp
public void OnUltimateSkillEnd()
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

### PrepareAttack(UnitModel)

```csharp
private void PrepareAttack(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ReadPassage(PassageObjectModel, ref List<PassageObjectModel>)

```csharp
private void ReadPassage(PassageObjectModel passage, ref List<PassageObjectModel> targets)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
| `targets` | `System.Collections.Generic.List{PassageObjectModel}` |  |

### SkillStart(Capsule)

```csharp
private void SkillStart(FixerClaw.Capsule capsule)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `capsule` | `Global.FixerClaw.Capsule` |  |

### SpeedDown()

```csharp
private void SpeedDown()
```
#INC


### SpeedUp()

```csharp
private void SpeedUp()
```
#INC


### StartGroggy()

```csharp
private void StartGroggy()
```
#INC


### StartHeal()

```csharp
private void StartHeal()
```
#INC


### StopMovement()

```csharp
private void StopMovement()
```
#INC


### TeleportToNode()

```csharp
private void TeleportToNode()
```
#INC


### TeleportToTarget(UnitModel, Capsule)

```csharp
private void TeleportToTarget(UnitModel target, FixerClaw.Capsule capsule)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `capsule` | `Global.FixerClaw.Capsule` |  |

### TryRabbitTeleport(MapNode)

```csharp
public override bool TryRabbitTeleport(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** System.Boolean

### UltiAttackNext()

```csharp
private void UltiAttackNext()
```
#INC

