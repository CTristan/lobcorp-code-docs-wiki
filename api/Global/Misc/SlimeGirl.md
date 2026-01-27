---
uid: Global.SlimeGirl
canonical_path: /api/Global/Misc/SlimeGirl
---

# Class SlimeGirl

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirl : SlimeCreature
```

Melting Love.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [SlimeCreature](/api/Global/Creature/SlimeCreature) → SlimeGirl

## Inherited Members
[motionDelayTimer](/api/Global/Creature/SlimeCreature#motiondelaytimer), [_motionDelayTimeMin](/api/Global/Creature/SlimeCreature#motiondelaytimemin), [_motionDelayTimeMax](/api/Global/Creature/SlimeCreature#motiondelaytimemax), [defaultSoundTimer](/api/Global/Creature/SlimeCreature#defaultsoundtimer), [_soundTermMin](/api/Global/Creature/SlimeCreature#soundtermmin), [_soundTermMax](/api/Global/Creature/SlimeCreature#soundtermmax), [_name](/api/Global/Creature/SlimeCreature#name), [GetNearest(float, bool)](/api/Global/Creature/SlimeCreature#getnearest-float-bool), [GetTargets(float, bool)](/api/Global/Creature/SlimeCreature#gettargets-float-bool), [IsInRange(UnitModel, float)](/api/Global/Creature/SlimeCreature#isinrange-unitmodel-float), [IsInView(UnitModel)](/api/Global/Creature/SlimeCreature#isinview-unitmodel), [GetDistance(UnitModel)](/api/Global/Creature/SlimeCreature#getdistance-unitmodel), [IsHostile(MovableObjectNode)](/api/Global/Creature/SlimeCreature#ishostile-movableobjectnode), [GetTargetDirection(UnitModel)](/api/Global/Creature/SlimeCreature#gettargetdirection-unitmodel), [GetTargetsInSefira(Sefira)](/api/Global/Creature/SlimeCreature#gettargetsinsefira-sefira), [GetNearestTargetInGlobal()](/api/Global/Creature/SlimeCreature#getnearesttargetinglobal), [GetViewDist(UnitModel)](/api/Global/Creature/SlimeCreature#getviewdist-unitmodel), [MoveToNearest()](/api/Global/Creature/SlimeCreature#movetonearest), [RandomMovement()](/api/Global/Creature/SlimeCreature#randommovement), [GiveDamage(UnitModel, DamageInfo)](/api/Global/Creature/SlimeCreature#givedamage-unitmodel-damageinfo), [PrepareAttack(UnitModel)](/api/Global/Creature/SlimeCreature#prepareattack-unitmodel), [GetName()](/api/Global/Creature/SlimeCreature#getname), [GetSoundSrc(string)](/api/Global/Creature/SlimeCreature#getsoundsrc-string), [SoundMake(string, Vector3, float)](/api/Global/Creature/SlimeCreature#soundmake-string-vector3-float), [SoundMake(string, float)](/api/Global/Creature/SlimeCreature#soundmake-string-float), [SoundMakeLoop(string, float)](/api/Global/Creature/SlimeCreature#soundmakeloop-string-float), [MotionDelayTime](/api/Global/Creature/SlimeCreature#motiondelaytime), [SoundTerm](/api/Global/Creature/SlimeCreature#soundterm), [name](/api/Global/Creature/SlimeCreature#name), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimeGirl()

```csharp
public SlimeGirl()
```

## Fields

### _animScript

```csharp
private SlimeGirlAnim _animScript
```
#INC


#### Field Value

**Type:** Global.SlimeGirlAnim

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

### _atkDmgType

```csharp
private const RwbpType _atkDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _atkEnrageDmgMax

```csharp
private const int _atkEnrageDmgMax = 32
```
#INC


#### Field Value

**Type:** System.Int32

### _atkEnrageDmgMin

```csharp
private const int _atkEnrageDmgMin = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _atkEnrageDmgType

```csharp
private const RwbpType _atkEnrageDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _healCoolInitTimeMax

```csharp
private const float _healCoolInitTimeMax = 20
```
#INC


#### Field Value

**Type:** System.Single

### _healCoolInitTimeMin

```csharp
private const float _healCoolInitTimeMin = 15
```
#INC


#### Field Value

**Type:** System.Single

### _healCoolTimeMax

```csharp
private const float _healCoolTimeMax = 18
```
#INC


#### Field Value

**Type:** System.Single

### _healCoolTimeMin

```csharp
private const float _healCoolTimeMin = 12
```
#INC


#### Field Value

**Type:** System.Single

### _healTimeMax

```csharp
private const float _healTimeMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _healTimeMin

```csharp
private const float _healTimeMin = 7
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMax

```csharp
private const float _healValueMax = 200
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMin

```csharp
private const float _healValueMin = 200
```
#INC


#### Field Value

**Type:** System.Single

### _mentalHealMax

```csharp
private const float _mentalHealMax = 35
```
#INC


#### Field Value

**Type:** System.Single

### _mentalHealMin

```csharp
private const float _mentalHealMin = 25
```
#INC


#### Field Value

**Type:** System.Single

### _phase

```csharp
private SlimeGirl.Phase _phase
```

#### Field Value

**Type:** Global.SlimeGirl.Phase

### _sacrifce

```csharp
private SlimePawn _sacrifce
```
#INC


#### Field Value

**Type:** Global.SlimePawn

### _skillCoolInitTimeMax

```csharp
private const float _skillCoolInitTimeMax = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolInitTimeMin

```csharp
private const float _skillCoolInitTimeMin = 10
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMax

```csharp
private const float _skillCoolTimeMax = 15
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMin

```csharp
private const float _skillCoolTimeMin = 10
```
#INC


#### Field Value

**Type:** System.Single

### _skillDmgMax

```csharp
private const int _skillDmgMax = 45
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgMin

```csharp
private const int _skillDmgMin = 25
```
#INC


#### Field Value

**Type:** System.Int32

### _skillDmgType

```csharp
private const RwbpType _skillDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _skillEnrageDmgMax

```csharp
private const int _skillEnrageDmgMax = 60
```
#INC


#### Field Value

**Type:** System.Int32

### _skillEnrageDmgMin

```csharp
private const int _skillEnrageDmgMin = 30
```
#INC


#### Field Value

**Type:** System.Int32

### _skillEnrageDmgType

```csharp
private const RwbpType _skillEnrageDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _state

```csharp
private SlimeGirl.State _state
```

#### Field Value

**Type:** Global.SlimeGirl.State

### ATK_DMG_RANGE

```csharp
private const float ATK_DMG_RANGE = 2
```
#INC


#### Field Value

**Type:** System.Single

### ATTACK_RANGE

```csharp
private const float ATTACK_RANGE = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### enrageEffect

```csharp
private GameObject enrageEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### ESCAPE_CONDITION_PAWN_RATIO

```csharp
private const float ESCAPE_CONDITION_PAWN_RATIO = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### HEAL_DIST

```csharp
private const float HEAL_DIST = 3.1
```
#INC


#### Field Value

**Type:** System.Single

### HEAL_EFFECT_SRC

```csharp
private const string HEAL_EFFECT_SRC = "Effect/RecoverHP"
```
#INC


#### Field Value

**Type:** System.String

### HEAL_HP_CONDITION

```csharp
private const float HEAL_HP_CONDITION = 0.6
```
#INC


#### Field Value

**Type:** System.Single

### HEAL_RECOGNIZE_RANGE

```csharp
private const float HEAL_RECOGNIZE_RANGE = 15
```
#INC


#### Field Value

**Type:** System.Single

### healCoolTimer

```csharp
private Timer healCoolTimer
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

### lover

```csharp
private WorkerModel lover
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### LOVER_BONUS_WORK_PROB

```csharp
private const int LOVER_BONUS_WORK_PROB = 10
```
#INC


#### Field Value

**Type:** System.Int32

### loverCreature

```csharp
private SlimeLover loverCreature
```
#INC


#### Field Value

**Type:** Global.SlimeLover

### MENTAL_HEAL_PROB

```csharp
private const float MENTAL_HEAL_PROB = 1
```
#INC


#### Field Value

**Type:** System.Single

### PAUSE_SKILL_ID

```csharp
private const int PAUSE_SKILL_ID = 2
```
#INC


#### Field Value

**Type:** System.Int32

### PAUSE_SUCCESS_CONDITION

```csharp
private const int PAUSE_SUCCESS_CONDITION = 24
```
#INC


#### Field Value

**Type:** System.Int32

### pawns

```csharp
private List<SlimePawn> pawns
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SlimePawn}

### RECOGNIZE_RANGE

```csharp
private const float RECOGNIZE_RANGE = 15
```
#INC


#### Field Value

**Type:** System.Single

### SKILL_RANGE

```csharp
private const float SKILL_RANGE = 10
```
#INC


#### Field Value

**Type:** System.Single

### skillCoolTimer

```csharp
private Timer skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### UNTARGETABLE_ID

```csharp
private const int UNTARGETABLE_ID = 4
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### animScript

```csharp
public SlimeGirlAnim animScript { get; }
```

#### Property Value

**Type:** Global.SlimeGirlAnim

### AttackDmg

```csharp
private static DamageInfo AttackDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### AttackEnrageDmg

```csharp
private static DamageInfo AttackEnrageDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### HealCoolInitTime

```csharp
private static float HealCoolInitTime { get; }
```

#### Property Value

**Type:** System.Single

### HealCoolTime

```csharp
private static float HealCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### HealTime

```csharp
private static float HealTime { get; }
```

#### Property Value

**Type:** System.Single

### HealValue

```csharp
private static float HealValue { get; }
```

#### Property Value

**Type:** System.Single

### LoverCreature

```csharp
public SlimeLover LoverCreature { get; }
```

#### Property Value

**Type:** Global.SlimeLover

### MentalHealValue

```csharp
private static float MentalHealValue { get; }
```

#### Property Value

**Type:** System.Single

### PawnBufCnt

```csharp
public int PawnBufCnt { get; }
```

#### Property Value

**Type:** System.Int32

### phase

```csharp
public SlimeGirl.Phase phase { get; }
```

#### Property Value

**Type:** Global.SlimeGirl.Phase

### sacrifce

```csharp
public SlimePawn sacrifce { get; private set; }
```

#### Property Value

**Type:** Global.SlimePawn

### SkillCoolInitTime

```csharp
private static float SkillCoolInitTime { get; }
```

#### Property Value

**Type:** System.Single

### SkillCoolTime

```csharp
private static float SkillCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### SkillDmg

```csharp
private static DamageInfo SkillDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### SkillEnrageDmg

```csharp
private static DamageInfo SkillEnrageDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### state

```csharp
public SlimeGirl.State state { get; }
```

#### Property Value

**Type:** Global.SlimeGirl.State

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
#INC


### AttackStart()

```csharp
private void AttackStart()
```
#INC


### CheckIfBeingLover(UseSkill)

```csharp
private bool CheckIfBeingLover(UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### CheckIfProjectileHit(UnitModel)

```csharp
public bool CheckIfProjectileHit(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### ClearPawns()

```csharp
private void ClearPawns()
```
#INC


### Enrage()

```csharp
private void Enrage()
```
#INC


### Escape()

```csharp
public override void Escape()
```
#INC


### FinishHeal()

```csharp
private void FinishHeal()
```
#INC


### GetAttackDamageTarget()

```csharp
private UnitModel GetAttackDamageTarget()
```
#INC


#### Returns

**Type:** Global.UnitModel

### GetAttackTarget()

```csharp
private UnitModel GetAttackTarget()
```
#INC


#### Returns

**Type:** Global.UnitModel

### GetNearestPawn()

```csharp
private SlimePawn GetNearestPawn()
```
#INC


#### Returns

**Type:** Global.SlimePawn

### GetPawnBufWorkers()

```csharp
private WorkerModel[] GetPawnBufWorkers()
```
#INC


#### Returns

**Type:** Global.WorkerModel[]

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

### IsHealing()

```csharp
private bool IsHealing()
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

### MakeChildCreature(UnitModel, bool)

```csharp
public ChildCreatureModel MakeChildCreature(UnitModel origin, bool isLover)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |
| `isLover` | `System.Boolean` |  |

#### Returns

**Type:** Global.ChildCreatureModel

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

### MakeHealEffect()

```csharp
private GameObject MakeHealEffect()
```
#INC


#### Returns

**Type:** UnityEngine.GameObject

### MakeLover(WorkerModel)

```csharp
private void MakeLover(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### MakeMovement()

```csharp
private void MakeMovement()
```
#INC


### MakeMovement(MovableObjectNode)

```csharp
private void MakeMovement(MovableObjectNode movable)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

### MakeMovement(SlimePawn)

```csharp
private void MakeMovement(SlimePawn nearestPawn)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

### MentalHeal(WorkerModel)

```csharp
private void MentalHeal(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OnAttackDamageTimeCalled()

```csharp
public override void OnAttackDamageTimeCalled()
```
#INC


### OnAttackEnd()

```csharp
public override void OnAttackEnd()
```
#INC


### OnBonusWorkProb()

```csharp
public override int OnBonusWorkProb()
```
#INC


#### Returns

**Type:** System.Int32

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

### OnHealEnd()

```csharp
public void OnHealEnd()
```
#INC


### OnJoin()

```csharp
public void OnJoin()
```
#INC


### OnLoverCreatureDie()

```csharp
public void OnLoverCreatureDie()
```
#INC


### OnLoverDie()

```csharp
public void OnLoverDie()
```
#INC


### OnLoverGen()

```csharp
public void OnLoverGen()
```
#INC


### OnProjectileHit(UnitModel)

```csharp
public void OnProjectileHit(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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


### OnSkillEnd()

```csharp
public void OnSkillEnd()
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

### OnStageEnd()

```csharp
public override void OnStageEnd()
```
#INC


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


### OnSuppressed()

```csharp
public override void OnSuppressed()
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

### ParamInit()

```csharp
public override void ParamInit()
```
#INC


### RemoveEnrageEffect()

```csharp
private void RemoveEnrageEffect()
```
#INC


### RemoveLover()

```csharp
public void RemoveLover()
```
#INC


### SkillStart()

```csharp
private void SkillStart()
```
#INC


### StartHeal(SlimePawn)

```csharp
private void StartHeal(SlimePawn nearestPawn)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

### StopMovement()

```csharp
protected override void StopMovement()
```
#INC


### SubQliphothCounter()

```csharp
private void SubQliphothCounter()
```
#INC


### SubQliphothCounterAll()

```csharp
private void SubQliphothCounterAll()
```
#INC


### TryHeal(SlimePawn)

```csharp
private bool TryHeal(SlimePawn nearestPawn)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

#### Returns

**Type:** System.Boolean

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

