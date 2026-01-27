---
uid: Global.Helper
canonical_path: /api/Global/Misc/Helper
---

# Class Helper

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Helper : CreatureBase
```

All-Around Helper.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → Helper

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Creature/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnViewInit(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinit-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Creature/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Creature/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Creature/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Creature/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Creature/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Creature/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Creature/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Creature/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Creature/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Creature/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Creature/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Creature/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Creature/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Helper()

```csharp
public Helper()
```

## Fields

### _animScript

```csharp
private HelperAnim _animScript
```
[All-Around Helper's animator](/api/Global/Creature/HelperAnim). If null, sets to the creature unit's animation target.


#### Field Value

**Type:** Global.HelperAnim

### _isRight

```csharp
private bool _isRight
```
#INC


#### Field Value

**Type:** System.Boolean

### _spinAttack

```csharp
private bool _spinAttack
```
#INC


#### Field Value

**Type:** System.Boolean

### attackCoolTime

```csharp
private Timer attackCoolTime
```
Timer which counts down to the end of Helper's shutdown after attacking.


#### Field Value

**Type:** Global.Timer

### attackCoolTimeVal

```csharp
private const float attackCoolTimeVal = 4
```
#INC


#### Field Value

**Type:** System.Single

### attackedUnits

```csharp
private List<UnitModel> attackedUnits
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### attackSpace

```csharp
private const float attackSpace = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### currentAttackEnd

```csharp
private MapNode currentAttackEnd
```
Location of the node to end up at during the spin attack.


#### Field Value

**Type:** Global.MapNode

### currentMoveTarget

```csharp
private MapNode currentMoveTarget
```
Current movement target. Assigned, but not really used.


#### Field Value

**Type:** Global.MapNode

### dmgMax

```csharp
private const int dmgMax = 30
```
#INC


#### Field Value

**Type:** System.Int32

### dmgMin

```csharp
private const int dmgMin = 20
```
#INC


#### Field Value

**Type:** System.Int32

### dmgType

```csharp
private RwbpType dmgType
```
The damage type Helper deals.


#### Field Value

**Type:** Global.RwbpType

### formerMovementTarget

```csharp
private int formerMovementTarget
```
Stores the index of the last targeted room in the current department.


#### Field Value

**Type:** System.Int32

### initialSpeed

```csharp
private float initialSpeed
```
Stores Helper's current speed.


#### Field Value

**Type:** System.Single

### interrupt

```csharp
private bool interrupt
```
Stores whether Helper is 'interrupted', which happens when the spin attack ends until woken up. #verify


#### Field Value

**Type:** System.Boolean

### isAttacking

```csharp
private bool isAttacking
```
Stores whether Helper is doing a spin attack.


#### Field Value

**Type:** System.Boolean

### prepareAttack

```csharp
private bool prepareAttack
```
Stores whether Helper is charging up its attack. #verify


#### Field Value

**Type:** System.Boolean

### speedMult

```csharp
private const float speedMult = 6
```
#INC


#### Field Value

**Type:** System.Single

### spinMaxSound

```csharp
private SoundEffectPlayer spinMaxSound
```
Plays the sound effect for ending the spin attack or being suppressed. #verify


#### Field Value

**Type:** Global.SoundEffectPlayer

### spinMaxTime

```csharp
private const float spinMaxTime = 3
```
#INC


#### Field Value

**Type:** System.Single

### spinSound

```csharp
private SoundEffectPlayer spinSound
```
Plays the sound during the spin attack.


#### Field Value

**Type:** Global.SoundEffectPlayer

### spinTimer

```csharp
private Timer spinTimer
```
Timer which counts down to the end of Helper's charging-up at the start of its attack.


#### Field Value

**Type:** Global.Timer

### throwItemSrc

```csharp
private const string throwItemSrc = "Effect/ThrowedItem"
```




#### Field Value

**Type:** System.String

### waking

```csharp
private bool waking
```
Stores whether Helper is waking up from shutdown.


#### Field Value

**Type:** System.Boolean

## Properties

### animScript

```csharp
public HelperAnim animScript { get; }
```

#### Property Value

**Type:** Global.HelperAnim

### currentSefira

```csharp
private Sefira currentSefira { get; set; }
```

#### Property Value

**Type:** Global.Sefira

### GetDmg

```csharp
private static int GetDmg { get; }
```

#### Property Value

**Type:** System.Int32

### isRight

```csharp
private bool isRight { get; set; }
```

#### Property Value

**Type:** System.Boolean

### spinAttack

```csharp
private bool spinAttack { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```
Calls base and breaches.


### AfterDown()

```csharp
public void AfterDown()
```
Stops being interrupted and starts a 4 second cooldown before the next attack.


### CheckPassageTarget()

```csharp
private bool CheckPassageTarget()
```
Returns true if there is another movable thing in the same room, and false otherwise.


#### Returns

**Type:** System.Boolean

### CheckTargetExist()

```csharp
private bool CheckTargetExist()
```
Return true if there are valid attack targets, and false otherwise.


#### Returns

**Type:** System.Boolean

### EndAttack()

```csharp
private void EndAttack()
```
Stops playing attack sounds, resets speed, plays a shutdown sound effect, and runs the shutdown animation. Sets flags for interrupted and recharging.


### Escape()

```csharp
public override void Escape()
```
Plays an escape animation, breaches the abnormality, and sets its current direction to right.


### GetTargetList(MovableObjectNode[])

```csharp
public MovableObjectNode[] GetTargetList(MovableObjectNode[] passageTarget)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passageTarget` | `Global.MovableObjectNode[]` |  |

#### Returns

**Type:** Global.MovableObjectNode[]

### MakeExplodeEffect(UnitDirection, WorkerModel, float)

```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```
Makes a gut explosion effect on a killed worker, and makes the worker vanish.
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### MakeMovement()

```csharp
private void MakeMovement()
```
Moves All-Around Helper while breaching.
###### more details
If there are no living workers in the current department, chooses a random department to target; otherwise, uses the current department.

Then, makes 5 attempts to choose a room different than the previous movement target; on failure, chooses the main rooms in the department instead. Then, chooses a random node within the selected room(s) and begins moving to it.

Note: I'm pretty sure this has a bug which prevents the last room in the list from ever being chosen. #bug


### MakeSparkSound()

```csharp
public void MakeSparkSound()
```
Plays a spark sound.


### OnReturn()

```csharp
public override void OnReturn()
```
Calls base and resets the Qliphoth counter.


### OnStageRelease()

```csharp
public override void OnStageRelease()
```
Calls ParamInit to reset variables.


### OnStageStart()

```csharp
public override void OnStageStart()
```
Sets the animation script (to this), resets Helper's speed, and calls ParamInit to reset variables.


### OnSuppressed()

```csharp
public override void OnSuppressed()
```
When suppressed, immediately ends attack, stops any sound playing, calls ParamInit to reset variables, and removes the current behaviour.


### OnWakeUpEnded()

```csharp
public void OnWakeUpEnded()
```
Sets flags to indicate it is no longer recharging or attacking.


### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```
When the work cooldown ends, randomly decreases the Qliphoth counter based on work result. Reduces by 1 at a 70% chance for bad results, and 50% for normal results.

If the Qliphoth counter is above 0, also sets the form back to normal if needed.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### ParamInit()

```csharp
public override void ParamInit()
```
Resetter for attacks, animations, and sound variables.


### PrevEscape()

```csharp
private void PrevEscape()
```
Changes the form of the abnormality to its breaching form when breaching.


### SetAttackNode(MovableObjectNode)

```csharp
private void SetAttackNode(MovableObjectNode target)
```
Finds the left-most and right-most points in the room, then sets the target node to the direction of the provided attack target. (i.e., if the target is left, spin left, and vice versa.) If at the right-most point, always attacks left.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.MovableObjectNode` |  |

### SetCastingSlider(Slider)

```csharp
public override bool SetCastingSlider(Slider castingSlider)
```
Updates a slider during the spin attack, called when that slider exists... which I don't think it ever does. #verify


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetSpinMultiplier(float)

```csharp
private void SetSpinMultiplier(float elapsed)
```
Sets the spinning animation speed to 0.3 times the time elapsed, for charging up the spin attack.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elapsed` | `System.Single` |  |

### Shoot()

```csharp
private void Shoot()
```
Plays a sound and moves at 6x speed to one side of the room, for when the spin attack is done charging up.


### SpinAttack()

```csharp
private void SpinAttack()
```
All-Around Helper's spinning attack.

For each living unit in the same room within 1.5 units of Helper which hasn't already been hit, deals damage. The first time something takes damage, also plays a hit sound.


### StartAttack()

```csharp
private void StartAttack()
```
Sets some flags to start attacking, and tells the animator to do the warm-up for the spin attack.


### StopMovement()

```csharp
private void StopMovement()
```
Clears the current command, tells the movable node to stop moving, and tells the animator Helper has stopped moving.


### TakeSpinDamage(UnitModel)

```csharp
private void TakeSpinDamage(UnitModel unit)
```
Deals damage to a unit for the spin attack and marks them as already hit.
###### more details
Skips dead units (redundantly), as well as invincible workers. Living workers take damage and display a damage particle effect, and explode if killed. If the target is a [creature](/api/Global/Model/CreatureModel), and isn't suppressed or returning, takes damage and displays a damage particle effect.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### TransformState(int)

```csharp
private void TransformState(int val)
```
Changes form.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Int32` |  |

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
Handles attacking and moving during breach.
###### more details
Does nothing during the transformation or during elevator transitions. If the spin attack is active, calls SpinAttack; otherwise, skips if interrupted.

If not attacking, chooses a random target in the room and attacks them. If there are no targets, Helper isn't doing anything, and Helper is not recharging, then starts moving.

When attacking, if an attack hasn't started, prepares to attack and plays a sound.

Then, either waits while on cool-down, spins around, or if not doing anything else, ends the current attack. Also, checks for agents to give encounter damage.[^1]

[^1]: Shouldn't this be an event, though? When an agent enters a room, check if they need to take fear damage? Why check this every frame?

