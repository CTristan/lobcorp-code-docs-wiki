---
uid: Global.MagicalGirl
canonical_path: /api/Global/IOBserver/MagicalGirl
---

# Class MagicalGirl

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MagicalGirl : CreatureBase, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → MagicalGirl

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Creature/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MagicalGirl()

```csharp
public MagicalGirl()
```

## Fields

### _animScript

```csharp
private MagicalGirlAnim _animScript
```

#### Field Value

**Type:** Global.MagicalGirlAnim

### _attackCoolTimeMax_Villain

```csharp
private const float _attackCoolTimeMax_Villain = 7
```

#### Field Value

**Type:** System.Single

### _attackCoolTimeMin_Villain

```csharp
private const float _attackCoolTimeMin_Villain = 5
```

#### Field Value

**Type:** System.Single

### _attackDmgMax_Hero

```csharp
private const int _attackDmgMax_Hero = 16
```

#### Field Value

**Type:** System.Int32

### _attackDmgMax_Villain_1st

```csharp
private const int _attackDmgMax_Villain_1st = 6
```

#### Field Value

**Type:** System.Int32

### _attackDmgMax_Villain_2nd

```csharp
private const int _attackDmgMax_Villain_2nd = 8
```

#### Field Value

**Type:** System.Int32

### _attackDmgMax_Villain_3rd

```csharp
private const int _attackDmgMax_Villain_3rd = 10
```

#### Field Value

**Type:** System.Int32

### _attackDmgMin_Hero

```csharp
private const int _attackDmgMin_Hero = 13
```

#### Field Value

**Type:** System.Int32

### _attackDmgMin_Villain_1st

```csharp
private const int _attackDmgMin_Villain_1st = 4
```

#### Field Value

**Type:** System.Int32

### _attackDmgMin_Villain_2nd

```csharp
private const int _attackDmgMin_Villain_2nd = 6
```

#### Field Value

**Type:** System.Int32

### _attackDmgMin_Villain_3rd

```csharp
private const int _attackDmgMin_Villain_3rd = 8
```

#### Field Value

**Type:** System.Int32

### _attackDmgType

```csharp
private const RwbpType _attackDmgType = B
```

#### Field Value

**Type:** Global.RwbpType

### _attackDmgType_Villain

```csharp
private const RwbpType _attackDmgType_Villain = B
```

#### Field Value

**Type:** Global.RwbpType

### _attackHealMax_Hp

```csharp
private const float _attackHealMax_Hp = 15
```

#### Field Value

**Type:** System.Single

### _attackHealMax_Mp

```csharp
private const float _attackHealMax_Mp = 15
```

#### Field Value

**Type:** System.Single

### _attackHealMax_Villain

```csharp
private const float _attackHealMax_Villain = 8
```

#### Field Value

**Type:** System.Single

### _attackHealMin_Hp

```csharp
private const float _attackHealMin_Hp = 13
```

#### Field Value

**Type:** System.Single

### _attackHealMin_Mp

```csharp
private const float _attackHealMin_Mp = 13
```

#### Field Value

**Type:** System.Single

### _attackHealMin_Villain

```csharp
private const float _attackHealMin_Villain = 5
```

#### Field Value

**Type:** System.Single

### _attackInitCoolTimeMax_Villain

```csharp
private const float _attackInitCoolTimeMax_Villain = 14
```

#### Field Value

**Type:** System.Single

### _attackInitCoolTimeMin_Villain

```csharp
private const float _attackInitCoolTimeMin_Villain = 10
```

#### Field Value

**Type:** System.Single

### _bangDmgMax_Hero

```csharp
private const int _bangDmgMax_Hero = 121
```

#### Field Value

**Type:** System.Int32

### _bangDmgMin_Hero

```csharp
private const int _bangDmgMin_Hero = 80
```

#### Field Value

**Type:** System.Int32

### _bangDmgType

```csharp
private const RwbpType _bangDmgType = B
```

#### Field Value

**Type:** Global.RwbpType

### _bangHealMax_Hp

```csharp
private const float _bangHealMax_Hp = 60
```

#### Field Value

**Type:** System.Single

### _bangHealMax_Mp

```csharp
private const float _bangHealMax_Mp = 60
```

#### Field Value

**Type:** System.Single

### _bangHealMin_Hp

```csharp
private const float _bangHealMin_Hp = 40
```

#### Field Value

**Type:** System.Single

### _bangHealMin_Mp

```csharp
private const float _bangHealMin_Mp = 40
```

#### Field Value

**Type:** System.Single

### _camp

```csharp
private MagicalGirl.Camp _camp
```

#### Field Value

**Type:** Global.MagicalGirl.Camp

### _gonnaBeHysteric

```csharp
private bool _gonnaBeHysteric
```

#### Field Value

**Type:** System.Boolean

### _groggyMax_Hero

```csharp
private const float _groggyMax_Hero = 8
```

#### Field Value

**Type:** System.Single

### _groggyMax_Villain

```csharp
private const float _groggyMax_Villain = 7
```

#### Field Value

**Type:** System.Single

### _groggyMin_Hero

```csharp
private const float _groggyMin_Hero = 5
```

#### Field Value

**Type:** System.Single

### _groggyMin_Villain

```csharp
private const float _groggyMin_Villain = 5
```

#### Field Value

**Type:** System.Single

### _helped

```csharp
private bool _helped
```

#### Field Value

**Type:** System.Boolean

### _heroSkillDmgRange

```csharp
private const float _heroSkillDmgRange = 15
```

#### Field Value

**Type:** System.Single

### _heroSkillRange

```csharp
private const float _heroSkillRange = 10
```

#### Field Value

**Type:** System.Single

### _hystericConditionInHero

```csharp
private const float _hystericConditionInHero = 0.2
```

#### Field Value

**Type:** System.Single

### _hystericTimeMax

```csharp
private const float _hystericTimeMax = 30
```

#### Field Value

**Type:** System.Single

### _hystericTimeMin

```csharp
private const float _hystericTimeMin = 25
```

#### Field Value

**Type:** System.Single

### _isTransforming

```csharp
private bool _isTransforming
```

#### Field Value

**Type:** System.Boolean

### _laserDmgMax_Hero_1st

```csharp
private const int _laserDmgMax_Hero_1st = 15
```

#### Field Value

**Type:** System.Int32

### _laserDmgMax_Hero_2nd

```csharp
private const int _laserDmgMax_Hero_2nd = 18
```

#### Field Value

**Type:** System.Int32

### _laserDmgMin_Hero_1st

```csharp
private const int _laserDmgMin_Hero_1st = 12
```

#### Field Value

**Type:** System.Int32

### _laserDmgMin_Hero_2nd

```csharp
private const int _laserDmgMin_Hero_2nd = 15
```

#### Field Value

**Type:** System.Int32

### _laserDmgType

```csharp
private const RwbpType _laserDmgType = B
```

#### Field Value

**Type:** Global.RwbpType

### _laserHealMax_Hp

```csharp
private const float _laserHealMax_Hp = 5
```

#### Field Value

**Type:** System.Single

### _laserHealMax_Mp

```csharp
private const float _laserHealMax_Mp = 8
```

#### Field Value

**Type:** System.Single

### _laserHealMin_Hp

```csharp
private const float _laserHealMin_Hp = 4.5
```

#### Field Value

**Type:** System.Single

### _laserHealMin_Mp

```csharp
private const float _laserHealMin_Mp = 7
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMax_Hero

```csharp
private const float _laserPatternTimeMax_Hero = 5.5
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMax_Villain_1st

```csharp
private const float _laserPatternTimeMax_Villain_1st = 3.5
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMax_Villain_2nd

```csharp
private const float _laserPatternTimeMax_Villain_2nd = 3.5
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMin_Hero

```csharp
private const float _laserPatternTimeMin_Hero = 4.5
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMin_Villain_1st

```csharp
private const float _laserPatternTimeMin_Villain_1st = 3
```

#### Field Value

**Type:** System.Single

### _laserPatternTimeMin_Villain_2nd

```csharp
private const float _laserPatternTimeMin_Villain_2nd = 3.45
```

#### Field Value

**Type:** System.Single

### _laserPhase

```csharp
private MagicalGirl.LaserPhase _laserPhase
```

#### Field Value

**Type:** Global.MagicalGirl.LaserPhase

### _motionDelayMax_Hero

```csharp
private const float _motionDelayMax_Hero = 0.6
```

#### Field Value

**Type:** System.Single

### _motionDelayMax_Villain

```csharp
private const float _motionDelayMax_Villain = 1.2
```

#### Field Value

**Type:** System.Single

### _motionDelayMin_Hero

```csharp
private const float _motionDelayMin_Hero = 0.4
```

#### Field Value

**Type:** System.Single

### _motionDelayMin_Villain

```csharp
private const float _motionDelayMin_Villain = 0.8
```

#### Field Value

**Type:** System.Single

### _overComeHystericCondition

```csharp
private const float _overComeHystericCondition = 0.7
```

#### Field Value

**Type:** System.Single

### _qliphothMax

```csharp
private const int _qliphothMax = 2
```

#### Field Value

**Type:** System.Int32

### _reducedWorkProbInHysteric

```csharp
private const int _reducedWorkProbInHysteric = -20
```

#### Field Value

**Type:** System.Int32

### _skillCastTimeMax_Villain

```csharp
private const float _skillCastTimeMax_Villain = 5
```

#### Field Value

**Type:** System.Single

### _skillCastTimeMin_Villain

```csharp
private const float _skillCastTimeMin_Villain = 3
```

#### Field Value

**Type:** System.Single

### _skillCoolTimeMax_Hero_Normal

```csharp
private const float _skillCoolTimeMax_Hero_Normal = 12
```

#### Field Value

**Type:** System.Single

### _skillCoolTimeMax_Hero_Special

```csharp
private const float _skillCoolTimeMax_Hero_Special = 25
```

#### Field Value

**Type:** System.Single

### _skillCoolTimeMin_Hero_Normal

```csharp
private const float _skillCoolTimeMin_Hero_Normal = 8
```

#### Field Value

**Type:** System.Single

### _skillCoolTimeMin_Hero_Special

```csharp
private const float _skillCoolTimeMin_Hero_Special = 20
```

#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMax_Hero_Normal

```csharp
private const float _skillInitCoolTimeMax_Hero_Normal = 16
```

#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMax_Hero_Special

```csharp
private const float _skillInitCoolTimeMax_Hero_Special = 35
```

#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMin_Hero_Normal

```csharp
private const float _skillInitCoolTimeMin_Hero_Normal = 12
```

#### Field Value

**Type:** System.Single

### _skillInitCoolTimeMin_Hero_Special

```csharp
private const float _skillInitCoolTimeMin_Hero_Special = 30
```

#### Field Value

**Type:** System.Single

### _skillRemainTimeMax_Hero

```csharp
private const float _skillRemainTimeMax_Hero = 10
```

#### Field Value

**Type:** System.Single

### _skillRemainTimeMax_Villain

```csharp
private const float _skillRemainTimeMax_Villain = 10
```

#### Field Value

**Type:** System.Single

### _skillRemainTimeMin_Hero

```csharp
private const float _skillRemainTimeMin_Hero = 9.8
```

#### Field Value

**Type:** System.Single

### _skillRemainTimeMin_Villain

```csharp
private const float _skillRemainTimeMin_Villain = 9.8
```

#### Field Value

**Type:** System.Single

### _speechTimeMax

```csharp
private const float _speechTimeMax = 20
```

#### Field Value

**Type:** System.Single

### _speechTimeMin

```csharp
private const float _speechTimeMin = 8
```

#### Field Value

**Type:** System.Single

### _subQliphothCondition_WorkerDie

```csharp
private const int _subQliphothCondition_WorkerDie = 3
```

#### Field Value

**Type:** System.Int32

### _teleportDmgMax_Villain

```csharp
private const int _teleportDmgMax_Villain = 26
```

#### Field Value

**Type:** System.Int32

### _teleportDmgMin_Villain

```csharp
private const int _teleportDmgMin_Villain = 20
```

#### Field Value

**Type:** System.Int32

### _teleportDmgType

```csharp
private const RwbpType _teleportDmgType = B
```

#### Field Value

**Type:** Global.RwbpType

### _teleportTimeMax

```csharp
private const float _teleportTimeMax = 15
```

#### Field Value

**Type:** System.Single

### _teleportTimeMin

```csharp
private const float _teleportTimeMin = 10
```

#### Field Value

**Type:** System.Single

### _villainTeleportDmgRange

```csharp
private const float _villainTeleportDmgRange = 4
```

#### Field Value

**Type:** System.Single

### _workProbInHysteric

```csharp
private const float _workProbInHysteric = 0.2
```

#### Field Value

**Type:** System.Single

### aliveWorkers

```csharp
private int aliveWorkers
```

#### Field Value

**Type:** System.Int32

### attackCoolTimer_Villain

```csharp
private Timer attackCoolTimer_Villain
```

#### Field Value

**Type:** Global.Timer

### deadInHero

```csharp
private List<WorkerModel> deadInHero
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### deadInThisLevel

```csharp
private List<WorkerModel> deadInThisLevel
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### encountered

```csharp
private List<UnitModel> encountered
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### groggyTimer

```csharp
private Timer groggyTimer
```

#### Field Value

**Type:** Global.Timer

### healTarget

```csharp
private AgentModel healTarget
```

#### Field Value

**Type:** Global.AgentModel

### hystericTimer

```csharp
private Timer hystericTimer
```

#### Field Value

**Type:** Global.Timer

### laserPatternTimer

```csharp
private Timer laserPatternTimer
```

#### Field Value

**Type:** Global.Timer

### motionDelayTimer

```csharp
private Timer motionDelayTimer
```

#### Field Value

**Type:** Global.Timer

### skillCastTimer_Villain

```csharp
private Timer skillCastTimer_Villain
```

#### Field Value

**Type:** Global.Timer

### skillCoolTimer_Hero_Normal

```csharp
private Timer skillCoolTimer_Hero_Normal
```

#### Field Value

**Type:** Global.Timer

### skillCoolTimer_Hero_Special

```csharp
private Timer skillCoolTimer_Hero_Special
```

#### Field Value

**Type:** Global.Timer

### skillRemainTimer_Hero

```csharp
private Timer skillRemainTimer_Hero
```

#### Field Value

**Type:** Global.Timer

### skillRemainTimer_Villain

```csharp
private Timer skillRemainTimer_Villain
```

#### Field Value

**Type:** Global.Timer

### speechNum

```csharp
private static int[] speechNum
```

#### Field Value

**Type:** System.Int32[]

### speechParam

```csharp
private static string[] speechParam
```

#### Field Value

**Type:** System.String[]

### speechTimer

```csharp
private Timer speechTimer
```

#### Field Value

**Type:** Global.Timer

### teleportCnt

```csharp
private int teleportCnt
```

#### Field Value

**Type:** System.Int32

### teleportTimer

```csharp
private Timer teleportTimer
```

#### Field Value

**Type:** Global.Timer

## Properties

### animScript

```csharp
public MagicalGirlAnim animScript { get; }
```

#### Property Value

**Type:** Global.MagicalGirlAnim

### attackCoolTime_Villain

```csharp
private static float attackCoolTime_Villain { get; }
```

#### Property Value

**Type:** System.Single

### AttackDamage_Hero

```csharp
public static DamageInfo AttackDamage_Hero { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### attackDmg_Villain_1st

```csharp
private static int attackDmg_Villain_1st { get; }
```

#### Property Value

**Type:** System.Int32

### attackDmg_Villain_2nd

```csharp
private static int attackDmg_Villain_2nd { get; }
```

#### Property Value

**Type:** System.Int32

### attackDmg_Villain_3rd

```csharp
private static int attackDmg_Villain_3rd { get; }
```

#### Property Value

**Type:** System.Int32

### AttackHeal_Hp

```csharp
public static float AttackHeal_Hp { get; }
```

#### Property Value

**Type:** System.Single

### AttackHeal_Mp

```csharp
public static float AttackHeal_Mp { get; }
```

#### Property Value

**Type:** System.Single

### AttackHeal_Villain

```csharp
public static float AttackHeal_Villain { get; }
```

#### Property Value

**Type:** System.Single

### attackInitCoolTime_Villain

```csharp
private static float attackInitCoolTime_Villain { get; }
```

#### Property Value

**Type:** System.Single

### BangDamage_Hero

```csharp
private static DamageInfo BangDamage_Hero { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### BangHeal_Hp

```csharp
private static float BangHeal_Hp { get; }
```

#### Property Value

**Type:** System.Single

### BangHeal_Mp

```csharp
private static float BangHeal_Mp { get; }
```

#### Property Value

**Type:** System.Single

### groggy_Hero

```csharp
private static float groggy_Hero { get; }
```

#### Property Value

**Type:** System.Single

### groggy_Villain

```csharp
private static float groggy_Villain { get; }
```

#### Property Value

**Type:** System.Single

### hystericTime

```csharp
private static float hystericTime { get; }
```

#### Property Value

**Type:** System.Single

### LaserDamage_Hero_1st

```csharp
public static int LaserDamage_Hero_1st { get; }
```

#### Property Value

**Type:** System.Int32

### LaserDamage_Hero_2nd

```csharp
public static int LaserDamage_Hero_2nd { get; }
```

#### Property Value

**Type:** System.Int32

### LaserHeal_Hp

```csharp
public static float LaserHeal_Hp { get; }
```

#### Property Value

**Type:** System.Single

### LaserHeal_Mp

```csharp
public static float LaserHeal_Mp { get; }
```

#### Property Value

**Type:** System.Single

### laserPatternTime_Hero

```csharp
private static float laserPatternTime_Hero { get; }
```

#### Property Value

**Type:** System.Single

### laserPatternTime_Villain_1st

```csharp
private static float laserPatternTime_Villain_1st { get; }
```

#### Property Value

**Type:** System.Single

### laserPatternTime_Villain_2nd

```csharp
private static float laserPatternTime_Villain_2nd { get; }
```

#### Property Value

**Type:** System.Single

### motionDelay_Hero

```csharp
private static float motionDelay_Hero { get; }
```

#### Property Value

**Type:** System.Single

### motionDelay_Villain

```csharp
private static float motionDelay_Villain { get; }
```

#### Property Value

**Type:** System.Single

### skillCastTime_Villain

```csharp
private static float skillCastTime_Villain { get; }
```

#### Property Value

**Type:** System.Single

### skillCoolTime_Hero_Normal

```csharp
private static float skillCoolTime_Hero_Normal { get; }
```

#### Property Value

**Type:** System.Single

### skillCoolTime_Hero_Special

```csharp
private static float skillCoolTime_Hero_Special { get; }
```

#### Property Value

**Type:** System.Single

### skillInitCoolTime_Hero_Normal

```csharp
private static float skillInitCoolTime_Hero_Normal { get; }
```

#### Property Value

**Type:** System.Single

### skillInitCoolTime_Hero_Special

```csharp
private static float skillInitCoolTime_Hero_Special { get; }
```

#### Property Value

**Type:** System.Single

### skillRemainTime_Hero

```csharp
private static float skillRemainTime_Hero { get; }
```

#### Property Value

**Type:** System.Single

### skillRemainTime_Villain

```csharp
private static float skillRemainTime_Villain { get; }
```

#### Property Value

**Type:** System.Single

### speechTime

```csharp
private static float speechTime { get; }
```

#### Property Value

**Type:** System.Single

### TeleportDamage_Villain

```csharp
private static DamageInfo TeleportDamage_Villain { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### teleportTime

```csharp
private static float teleportTime { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```

### AddedQliphothCounter()

```csharp
public override void AddedQliphothCounter()
```

### AttackStart(int)

```csharp
private void AttackStart(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### BeAHero()

```csharp
private void BeAHero()
```

### BeAVillain()

```csharp
private void BeAVillain()
```

### BeHysteric()

```csharp
private void BeHysteric()
```

### CanSpeech()

```csharp
private bool CanSpeech()
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

### CheckChu(UseSkill)

```csharp
private bool CheckChu(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### CheckMeetingCreature()

```csharp
private void CheckMeetingCreature()
```

### CheckOutside()

```csharp
private void CheckOutside()
```

### CheckOvercome(UseSkill)

```csharp
private bool CheckOvercome(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### Chu()

```csharp
public void Chu()
```

### ComeBack()

```csharp
private void ComeBack()
```

### CurrentAttackType()

```csharp
public int CurrentAttackType()
```

#### Returns

**Type:** System.Int32

### Escape()

```csharp
public override void Escape()
```

### FixedUpdate_Hero()

```csharp
private void FixedUpdate_Hero()
```

### FixedUpdate_Hysteric()

```csharp
private void FixedUpdate_Hysteric()
```

### FixedUpdate_Villain()

```csharp
private void FixedUpdate_Villain()
```

### GetAlive()

```csharp
private List<WorkerModel> GetAlive()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetAttackDamage_Villain()

```csharp
public DamageInfo GetAttackDamage_Villain()
```

#### Returns

**Type:** Global.DamageInfo

### GetAttackHeal_Villain()

```csharp
public float GetAttackHeal_Villain()
```

#### Returns

**Type:** System.Single

### GetDistance(UnitModel)

```csharp
private float GetDistance(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Single

### GetEscapedCreatures()

```csharp
private List<CreatureModel> GetEscapedCreatures()
```

#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### GetHealTargets(float, bool)

```csharp
private List<UnitModel> GetHealTargets(float range, bool needDir = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetLaserDamage_Hero()

```csharp
public DamageInfo GetLaserDamage_Hero()
```

#### Returns

**Type:** Global.DamageInfo

### GetLaserHealHp_Hero()

```csharp
public float GetLaserHealHp_Hero()
```

#### Returns

**Type:** System.Single

### GetLaserHealMP_Hero()

```csharp
public float GetLaserHealMP_Hero()
```

#### Returns

**Type:** System.Single

### GetNearest(float, bool)

```csharp
private UnitModel GetNearest(float range, bool needDir = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** Global.UnitModel

### GetParam(string)

```csharp
private CreatureStaticData.ParameterData GetParam(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetParamData(string)

```csharp
private string GetParamData(string key)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetTeleportTarget_Hero()

```csharp
private CreatureModel GetTeleportTarget_Hero()
```

#### Returns

**Type:** Global.CreatureModel

### GroggyEnd()

```csharp
private void GroggyEnd()
```

### GroggyStart()

```csharp
private void GroggyStart()
```

### IsAttacking()

```csharp
private bool IsAttacking()
```

#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public override bool IsAutoSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsHealTarget(MovableObjectNode)

```csharp
private bool IsHealTarget(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### IsHostile(MovableObjectNode)

```csharp
private bool IsHostile(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### IsInGroggy()

```csharp
private bool IsInGroggy()
```

#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float)

```csharp
private bool IsInRange(UnitModel target, float range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### IsInSkill()

```csharp
private bool IsInSkill()
```

#### Returns

**Type:** System.Boolean

### IsInView(UnitModel)

```csharp
private bool IsInView(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsMovable()

```csharp
private bool IsMovable()
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

### IsWorkable()

```csharp
public override bool IsWorkable()
```

#### Returns

**Type:** System.Boolean

### MakeDamageEffect(Vector3)

```csharp
public void MakeDamageEffect(Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |

### MakeMovement()

```csharp
private void MakeMovement()
```

### MakeMovement_Hero()

```csharp
private void MakeMovement_Hero()
```

### MakeMovement_Villain()

```csharp
private void MakeMovement_Villain()
```

### MotionDelay()

```csharp
private void MotionDelay()
```

### OnAfterDeadScene()

```csharp
public void OnAfterDeadScene()
```

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnBang()

```csharp
public void OnBang()
```

### OnBonusWorkProb()

```csharp
public override int OnBonusWorkProb()
```

#### Returns

**Type:** System.Int32

### OnEndTransformToVillain()

```csharp
public void OnEndTransformToVillain()
```

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGroggyEnd()

```csharp
public void OnGroggyEnd()
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

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```

#### Returns

**Type:** System.Boolean

### OnOverLoadLevelChanged()

```csharp
private void OnOverLoadLevelChanged()
```

### OnReleaseWork(UseSkill)

```csharp
public override void OnReleaseWork(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReturn()

```csharp
public override void OnReturn()
```

### OnShootLaser_Hero()

```csharp
public void OnShootLaser_Hero()
```

### OnShootLaser_Villain()

```csharp
public void OnShootLaser_Villain()
```

### OnSkillEnd(int)

```csharp
public void OnSkillEnd(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnStartHysteric()

```csharp
public void OnStartHysteric()
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

### OnWorkerDie(WorkerModel)

```csharp
private void OnWorkerDie(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### Overcome()

```csharp
private void Overcome()
```

### ParamInit()

```csharp
public override void ParamInit()
```

### ReducedQliphothCounter()

```csharp
public override void ReducedQliphothCounter()
```

### SetObserver(bool)

```csharp
private void SetObserver(bool active)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### ShootingEnd()

```csharp
public void ShootingEnd()
```

### ShootLaser_Villain(int)

```csharp
private void ShootLaser_Villain(int phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `System.Int32` |  |

### ShowSpeech(SpeechKey)

```csharp
public void ShowSpeech(MagicalGirl.SpeechKey key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `Global.MagicalGirl.SpeechKey` |  |

### SkillStart(int)

```csharp
private void SkillStart(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### StopMovement()

```csharp
private void StopMovement()
```

### SuppressSpeech(List<UnitModel>)

```csharp
public void SuppressSpeech(List<UnitModel> suppressed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `suppressed` | `System.Collections.Generic.List{UnitModel}` |  |

### Teleport(MapNode)

```csharp
private void Teleport(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### Teleport(UnitModel)

```csharp
private void Teleport(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### TeleportToPassage(UnitModel)

```csharp
private void TeleportToPassage(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### TeleportToWorker()

```csharp
private void TeleportToWorker()
```

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
