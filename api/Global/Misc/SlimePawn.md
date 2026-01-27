---
uid: Global.SlimePawn
canonical_path: /api/Global/Misc/SlimePawn
---

# Class SlimePawn

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimePawn : SlimeCreature
```

One of [Melting Love](/api/Global/Misc/SlimeGirl)'s small minions.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → [SlimeCreature](/api/Global/Creature/SlimeCreature) → SlimePawn

## Inherited Members
[motionDelayTimer](/api/Global/Creature/SlimeCreature#motiondelaytimer), [_motionDelayTimeMin](/api/Global/Creature/SlimeCreature#motiondelaytimemin), [_motionDelayTimeMax](/api/Global/Creature/SlimeCreature#motiondelaytimemax), [defaultSoundTimer](/api/Global/Creature/SlimeCreature#defaultsoundtimer), [_soundTermMin](/api/Global/Creature/SlimeCreature#soundtermmin), [_soundTermMax](/api/Global/Creature/SlimeCreature#soundtermmax), [_name](/api/Global/Creature/SlimeCreature#name), [GetNearest(float, bool)](/api/Global/Creature/SlimeCreature#getnearest-float-bool), [GetTargets(float, bool)](/api/Global/Creature/SlimeCreature#gettargets-float-bool), [IsInRange(UnitModel, float)](/api/Global/Creature/SlimeCreature#isinrange-unitmodel-float), [IsInView(UnitModel)](/api/Global/Creature/SlimeCreature#isinview-unitmodel), [GetDistance(UnitModel)](/api/Global/Creature/SlimeCreature#getdistance-unitmodel), [IsHostile(MovableObjectNode)](/api/Global/Creature/SlimeCreature#ishostile-movableobjectnode), [GetTargetDirection(UnitModel)](/api/Global/Creature/SlimeCreature#gettargetdirection-unitmodel), [GetTargetsInSefira(Sefira)](/api/Global/Creature/SlimeCreature#gettargetsinsefira-sefira), [GetNearestTargetInGlobal()](/api/Global/Creature/SlimeCreature#getnearesttargetinglobal), [GetViewDist(UnitModel)](/api/Global/Creature/SlimeCreature#getviewdist-unitmodel), [MoveToNearest()](/api/Global/Creature/SlimeCreature#movetonearest), [RandomMovement()](/api/Global/Creature/SlimeCreature#randommovement), [OnAttackEnd()](/api/Global/Creature/SlimeCreature#onattackend), [GiveDamage(UnitModel, DamageInfo)](/api/Global/Creature/SlimeCreature#givedamage-unitmodel-damageinfo), [PrepareAttack(UnitModel)](/api/Global/Creature/SlimeCreature#prepareattack-unitmodel), [GetName()](/api/Global/Creature/SlimeCreature#getname), [SoundMake(string, Vector3, float)](/api/Global/Creature/SlimeCreature#soundmake-string-vector3-float), [SoundMake(string, float)](/api/Global/Creature/SlimeCreature#soundmake-string-float), [SoundMakeLoop(string, float)](/api/Global/Creature/SlimeCreature#soundmakeloop-string-float), [MotionDelayTime](/api/Global/Creature/SlimeCreature#motiondelaytime), [SoundTerm](/api/Global/Creature/SlimeCreature#soundterm), [name](/api/Global/Creature/SlimeCreature#name), [isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnStageStart()](/api/Global/Creature/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Creature/CreatureBase#onreturn), [Escape()](/api/Global/Creature/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Creature/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [ParamInit()](/api/Global/Creature/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimePawn()

```csharp
public SlimePawn()
```

## Fields

### _animScript

```csharp
private SlimePawnAnim _animScript
```
#INC


#### Field Value

**Type:** Global.SlimePawnAnim

### _atkDmgMax

```csharp
private const int _atkDmgMax = 12
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

### _atkDmgType

```csharp
private const RwbpType _atkDmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _max_hp_max

```csharp
private const int _max_hp_max = 200
```
#INC


#### Field Value

**Type:** System.Int32

### _max_hp_min

```csharp
private const int _max_hp_min = 200
```
#INC


#### Field Value

**Type:** System.Int32

### _speed_max

```csharp
private const float _speed_max = 2.1
```
#INC


#### Field Value

**Type:** System.Single

### _speed_min

```csharp
private const float _speed_min = 1.9
```
#INC


#### Field Value

**Type:** System.Single

### ATK_DMG_RANGE

```csharp
private const float ATK_DMG_RANGE = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### ATTACK_RANGE

```csharp
private const float ATTACK_RANGE = 1
```
#INC


#### Field Value

**Type:** System.Single

### CODE_ID

```csharp
private const string CODE_ID = "D-01-106-2"
```
#INC


#### Field Value

**Type:** System.String

### DEFENSE_ID

```csharp
private const string DEFENSE_ID = "1"
```
#INC


#### Field Value

**Type:** System.String

### RECOGNIZE_RANGE

```csharp
private const float RECOGNIZE_RANGE = 8
```
#INC


#### Field Value

**Type:** System.Single

### RISK_LEVEL

```csharp
private const string RISK_LEVEL = "HE"
```
#INC


#### Field Value

**Type:** System.String

### script

```csharp
private SlimeGirl script
```
#INC


#### Field Value

**Type:** Global.SlimeGirl

## Properties

### animScript

```csharp
public SlimePawnAnim animScript { get; }
```

#### Property Value

**Type:** Global.SlimePawnAnim

### AttackDmg

```csharp
private static DamageInfo AttackDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### MAX_HP

```csharp
private static int MAX_HP { get; }
```

#### Property Value

**Type:** System.Int32

### Model

```csharp
private ChildCreatureModel Model { get; }
```

#### Property Value

**Type:** Global.ChildCreatureModel

### SPEED

```csharp
private static float SPEED { get; }
```

#### Property Value

**Type:** System.Single

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
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### CheckIfSacrifice()

```csharp
private bool CheckIfSacrifice()
```
#INC


#### Returns

**Type:** System.Boolean

### GetRiskLevel()

```csharp
public override string GetRiskLevel()
```
#INC


#### Returns

**Type:** System.String

### GetSoundSrc(string)

```csharp
public override string GetSoundSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### HaveToMove()

```csharp
private bool HaveToMove()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAttacking()

```csharp
private bool IsAttacking()
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
public override void OnAttackDamageTimeCalled()
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


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### Sacrifice()

```csharp
public void Sacrifice()
```
#INC


### StopMovement()

```csharp
protected override void StopMovement()
```
#INC


### Suppressed()

```csharp
public void Suppressed()
```
#INC


### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC

