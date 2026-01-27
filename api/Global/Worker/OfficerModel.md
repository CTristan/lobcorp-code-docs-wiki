---
uid: Global.OfficerModel
canonical_path: /api/Global/Worker/OfficerModel
---

# Class OfficerModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerModel : WorkerModel, IObserver, IMouseCommandTargetModel
```

A clerk, abstractly.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → [WorkerModel](/api/Global/Model/WorkerModel) → OfficerModel

## Implements
[IObserver](/api/Global/Misc/IObserver), [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[commandQueue](/api/Global/Model/WorkerModel#commandqueue), [workerClass](/api/Global/Model/WorkerModel#workerclass), [isRealWorker](/api/Global/Model/WorkerModel#isrealworker), [name](/api/Global/Model/WorkerModel#name), [gender](/api/Global/Model/WorkerModel#gender), [_currentSefira](/api/Global/Model/WorkerModel#currentsefira), [currentSefiraEnum](/api/Global/Model/WorkerModel#currentsefiraenum), [_revivalHp](/api/Global/Model/WorkerModel#revivalhp), [_revivalMental](/api/Global/Model/WorkerModel#revivalmental), [_revivaledHp](/api/Global/Model/WorkerModel#revivaledhp), [_revivaledMental](/api/Global/Model/WorkerModel#revivaledmental), [revivalProb](/api/Global/Model/WorkerModel#revivalprob), [movementMul](/api/Global/Model/WorkerModel#movementmul), [panicValue](/api/Global/Model/WorkerModel#panicvalue), [invincible](/api/Global/Model/WorkerModel#invincible), [blockRecover](/api/Global/Model/WorkerModel#blockrecover), [stunTime](/api/Global/Model/WorkerModel#stuntime), [haltUpdate](/api/Global/Model/WorkerModel#haltupdate), [returnPanic](/api/Global/Model/WorkerModel#returnpanic), [willDead](/api/Global/Model/WorkerModel#willdead), [_isDead](/api/Global/Model/WorkerModel#isdead), [speechTable](/api/Global/Model/WorkerModel#speechtable), [target](/api/Global/Model/WorkerModel#target), [targetWorker](/api/Global/Model/WorkerModel#targetworker), [targetObject](/api/Global/Model/WorkerModel#targetobject), [currentPanicAction](/api/Global/Model/WorkerModel#currentpanicaction), [unconAction](/api/Global/Model/WorkerModel#unconaction), [_recentlyAttacked](/api/Global/Model/WorkerModel#recentlyattacked), [animationMessageRecevied](/api/Global/Model/WorkerModel#animationmessagerecevied), [visible](/api/Global/Model/WorkerModel#visible), [waitTimer](/api/Global/Model/WorkerModel#waittimer), [OnWorkEndFlag](/api/Global/Model/WorkerModel#onworkendflag), [puppetChanged](/api/Global/Model/WorkerModel#puppetchanged), [lastestMoveTarget](/api/Global/Model/WorkerModel#lastestmovetarget), [_attackTargetWorker](/api/Global/Model/WorkerModel#attacktargetworker), [_specialDeadScene](/api/Global/Model/WorkerModel#specialdeadscene), [deadSceneName](/api/Global/Model/WorkerModel#deadscenename), [seperator](/api/Global/Model/WorkerModel#seperator), [hasUniqueFace](/api/Global/Model/WorkerModel#hasuniqueface), [hairSprite](/api/Global/Model/WorkerModel#hairsprite), [faceSprite](/api/Global/Model/WorkerModel#facesprite), [stunEffect](/api/Global/Model/WorkerModel#stuneffect), [spriteData](/api/Global/Model/WorkerModel#spritedata), [_panicData](/api/Global/Model/WorkerModel#panicdata), [isChangeableAnimator](/api/Global/Model/WorkerModel#ischangeableanimator), [_deadType](/api/Global/Model/WorkerModel#deadtype), [OnStageStart()](/api/Global/Model/WorkerModel#onstagestart), [GetSaveData()](/api/Global/Model/WorkerModel#getsavedata), [TryGetValue<T>(Dictionary<string, object>, string, ref T)](Global.WorkerModel.html#WorkerModel_TryGetValue__1_System_Collections_Generic_Dictionary_System_String_System_Object__System_String___0__), [LoadData(Dictionary<string, object>)](/api/Global/Model/WorkerModel#loaddata-dictionary-string-object), [HaltUpdate()](/api/Global/Model/WorkerModel#haltupdate), [ReleaseUpdate()](/api/Global/Model/WorkerModel#releaseupdate), [ResetSprite()](/api/Global/Model/WorkerModel#resetsprite), [GetCurrentNode()](/api/Global/Model/WorkerModel#getcurrentnode), [SetCurrentNode(MapNode)](/api/Global/Model/WorkerModel#setcurrentnode-mapnode), [GetCurrentEdge()](/api/Global/Model/WorkerModel#getcurrentedge), [GetEdgeDirection()](/api/Global/Model/WorkerModel#getedgedirection), [GetCurrentCommand()](/api/Global/Model/WorkerModel#getcurrentcommand), [MoveToNode(MapNode)](/api/Global/Model/WorkerModel#movetonode-mapnode), [MoveToNode(MapNode, bool)](/api/Global/Model/WorkerModel#movetonode-mapnode-bool), [MoveToMovable(MovableObjectNode)](/api/Global/Model/WorkerModel#movetomovable-movableobjectnode), [MoveFromNullPassage()](/api/Global/Model/WorkerModel#movefromnullpassage), [MoveToMovable(MovableObjectNode, bool)](/api/Global/Model/WorkerModel#movetomovable-movableobjectnode-bool), [MoveToNode(string)](/api/Global/Model/WorkerModel#movetonode-string), [FollowMovable(MovableObjectNode)](/api/Global/Model/WorkerModel#followmovable-movableobjectnode), [IsDead()](/api/Global/Model/WorkerModel#isdead), [GetConnectedNode()](/api/Global/Model/WorkerModel#getconnectednode), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Model/WorkerModel#takedamagewithouteffect-unitmodel-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Model/WorkerModel#takedamage-unitmodel-damageinfo), [CreatePhysicalDamagedEffect(float)](/api/Global/Model/WorkerModel#createphysicaldamagedeffect-float), [CreateMentalDamagedEffect(float)](/api/Global/Model/WorkerModel#creatementaldamagedeffect-float), [IsAttackTargetable()](/api/Global/Model/WorkerModel#isattacktargetable), [IsHostile(UnitModel)](/api/Global/Model/WorkerModel#ishostile-unitmodel), [RecentlyAttackedCreature(CreatureModel)](/api/Global/Model/WorkerModel#recentlyattackedcreature-creaturemodel), [TakeMentalDamage(float, MentalDamageOption)](/api/Global/Model/WorkerModel#takementaldamage-float-mentaldamageoption), [TakeMentalDamage(float)](/api/Global/Model/WorkerModel#takementaldamage-float), [MakeSpatteredBlood()](/api/Global/Model/WorkerModel#makespatteredblood), [RecoverHP(float)](/api/Global/Model/WorkerModel#recoverhp-float), [SetInvincible(bool)](/api/Global/Model/WorkerModel#setinvincible-bool), [Stun(float)](/api/Global/Model/WorkerModel#stun-float), [StopStun()](/api/Global/Model/WorkerModel#stopstun), [OnAttackWorker(WorkerModel)](/api/Global/Model/WorkerModel#onattackworker-workermodel), [IsSuppable()](/api/Global/Model/WorkerModel#issuppable), [SetCustsomCommand(WorkerCommand)](/api/Global/Model/WorkerModel#setcustsomcommand-workercommand), [Die()](/api/Global/Model/WorkerModel#die), [AfterDeadAnim()](/api/Global/Model/WorkerModel#afterdeadanim), [InteractWithDoor(DoorObjectModel)](/api/Global/Model/WorkerModel#interactwithdoor-doorobjectmodel), [CompareByName(WorkerModel, WorkerModel)](/api/Global/Model/WorkerModel#comparebyname-workermodel-workermodel), [IsInSefira()](/api/Global/Model/WorkerModel#isinsefira), [OnNotice(string, params object[])](/api/Global/Model/WorkerModel#onnotice-string-params-object), [SetSpecialDeadScene(string)](/api/Global/Model/WorkerModel#setspecialdeadscene-string), [SetSpecialDeadScene(string, bool)](/api/Global/Model/WorkerModel#setspecialdeadscene-string-bool), [SetSpecialDeadScene(string, bool, bool)](/api/Global/Model/WorkerModel#setspecialdeadscene-string-bool-bool), [ResetSpecialDeadScene()](/api/Global/Model/WorkerModel#resetspecialdeadscene), [CompareByID(WorkerModel, WorkerModel)](/api/Global/Model/WorkerModel#comparebyid-workermodel-workermodel), [CompareBySefira(WorkerModel, WorkerModel)](/api/Global/Model/WorkerModel#comparebysefira-workermodel-workermodel), [ShowUnconSpeech(string)](/api/Global/Model/WorkerModel#showunconspeech-string), [MakeCreatureEffect(CreatureModel)](/api/Global/Model/WorkerModel#makecreatureeffect-creaturemodel), [SetWorkerFaceType(WorkerFaceType)](/api/Global/Model/WorkerModel#setworkerfacetype-workerfacetype), [PlayAttackAnimation(string)](/api/Global/Model/WorkerModel#playattackanimation-string), [ShowSpeech(string)](/api/Global/Model/WorkerModel#showspeech-string), [ChangePuppet(string)](/api/Global/Model/WorkerModel#changepuppet-string), [SetAgentCommand(WorkerCommand)](/api/Global/Model/WorkerModel#setagentcommand-workercommand), [SetDeadType(DeadType)](/api/Global/Model/WorkerModel#setdeadtype-deadtype), [SetPanicAnim(bool)](/api/Global/Model/WorkerModel#setpanicanim-bool), [OnStun(float)](/api/Global/Model/WorkerModel#onstun-float), [OnStunEffectDestroied()](/api/Global/Model/WorkerModel#onstuneffectdestroied), [OnSetArmor()](/api/Global/Model/WorkerModel#onsetarmor), [CheckEGOGift()](/api/Global/Model/WorkerModel#checkegogift), [GetWeaponSprite()](/api/Global/Model/WorkerModel#getweaponsprite), [SpecialAttackDamage(TrackEntry, Event)](/api/Global/Model/WorkerModel#specialattackdamage-trackentry-event), [SpecialAttackEnd(TrackEntry)](/api/Global/Model/WorkerModel#specialattackend-trackentry), [fortitudeLevel](/api/Global/Model/WorkerModel#fortitudelevel), [prudenceLevel](/api/Global/Model/WorkerModel#prudencelevel), [temperanceLevel](/api/Global/Model/WorkerModel#temperancelevel), [justiceLevel](/api/Global/Model/WorkerModel#justicelevel), [currentSefira](/api/Global/Model/WorkerModel#currentsefira), [CurrentPanicAction](/api/Global/Model/WorkerModel#currentpanicaction), [recentlyAttacked](/api/Global/Model/WorkerModel#recentlyattacked), [attackTargetWorker](/api/Global/Model/WorkerModel#attacktargetworker), [specialDeadScene](/api/Global/Model/WorkerModel#specialdeadscene), [workerAnimator](/api/Global/Model/WorkerModel#workeranimator), [panicData](/api/Global/Model/WorkerModel#panicdata), [DeadType](/api/Global/Model/WorkerModel#deadtype), [stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [OnStopMovableByShield(AgentModel)](/api/Global/Model/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Model/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Model/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Model/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Model/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Model/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/UnitModel#setfaction-string), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [radius](/api/Global/Model/UnitModel#radius), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OfficerModel(long, string)

```csharp
public OfficerModel(long id, string area)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `area` | `System.String` |  |

## Fields

### _panicImmuneTimer

```csharp
private Timer _panicImmuneTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _readyToSuicide

```csharp
private bool _readyToSuicide
```
#INC


#### Field Value

**Type:** System.Boolean

### _state

```csharp
private OfficerAIState _state
```
#INC


#### Field Value

**Type:** Global.OfficerAIState

### _unit

```csharp
private OfficerUnit _unit
```
#INC


#### Field Value

**Type:** Global.OfficerUnit

### currentSpecialAction

```csharp
private OfficerSpecialAction currentSpecialAction
```
#INC


#### Field Value

**Type:** Global.OfficerSpecialAction

### deadInit

```csharp
private bool deadInit
```
#INC


#### Field Value

**Type:** System.Boolean

### elapsedTime

```csharp
private float elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### isDebugger

```csharp
public bool isDebugger
```
#INC


#### Field Value

**Type:** System.Boolean

### isMoving

```csharp
private bool isMoving
```
#INC


#### Field Value

**Type:** System.Boolean

### lookingDir

```csharp
public LOOKINGDIR lookingDir
```
#INC


#### Field Value

**Type:** Global.LOOKINGDIR

### mentalReturn

```csharp
public int mentalReturn
```
#INC


#### Field Value

**Type:** System.Int32

### recoverElapsed

```csharp
private float recoverElapsed
```
#INC


#### Field Value

**Type:** System.Single

### recoveryRate

```csharp
public int recoveryRate
```
#INC


#### Field Value

**Type:** System.Int32

### screamElapsed

```csharp
private float screamElapsed
```
#INC


#### Field Value

**Type:** System.Single

### screamMax

```csharp
private float screamMax
```
#INC


#### Field Value

**Type:** System.Single

### shouldPanic

```csharp
private bool shouldPanic
```
#INC


#### Field Value

**Type:** System.Boolean

### startSpecialAction

```csharp
public bool startSpecialAction
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### defense

```csharp
public override DefenseInfo defense { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

### deptNum

```csharp
public int deptNum { get; set; }
```
#INC


#### Property Value

**Type:** System.Int32

### state

```csharp
public OfficerAIState state { get; set; }
```

#### Property Value

**Type:** Global.OfficerAIState

## Methods

### CancelWeapon()

```csharp
public override void CancelWeapon()
```
#INC


### CannotControll()

```csharp
public override bool CannotControll()
```
#INC


#### Returns

**Type:** System.Boolean

### ChangeHairSprite(SpriteInfo)

```csharp
public override void ChangeHairSprite(SpriteInfo spriteInfo)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteInfo` | `Global.SpriteInfo` |  |

### ChangePuppetAnimToDie(string)

```csharp
public override WorkerDeadScript ChangePuppetAnimToDie(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.WorkerDeadScript

### ChangePuppetAnimToUncon(string)

```csharp
public override void ChangePuppetAnimToUncon(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### ClearEffect()

```csharp
public override void ClearEffect()
```
#INC


### ClearUnconCommand()

```csharp
public override void ClearUnconCommand()
```
#INC


### EncounterCreature(UnitModel)

```csharp
public override void EncounterCreature(UnitModel encounteredCreature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encounteredCreature` | `Global.UnitModel` |  |

### EncounterStandingItem(StandingItemModel)

```csharp
public override void EncounterStandingItem(StandingItemModel standing)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### EndSpecialAction()

```csharp
public void EndSpecialAction()
```
#INC


### GetControl()

```csharp
public override void GetControl()
```
#INC


### GetCurrentSefira()

```csharp
public override Sefira GetCurrentSefira()
```
#INC


#### Returns

**Type:** Global.Sefira

### GetState()

```csharp
public OfficerAIState GetState()
```
#INC


#### Returns

**Type:** Global.OfficerAIState

### GetUnit()

```csharp
public OfficerUnit GetUnit()
```
#INC


#### Returns

**Type:** Global.OfficerUnit

### GetUnitName()

```csharp
public override string GetUnitName()
```
#INC


#### Returns

**Type:** System.String

### GetWorkerUnit()

```csharp
public override WorkerUnit GetWorkerUnit()
```
#INC


#### Returns

**Type:** Global.WorkerUnit

### HaltSpecialAction()

```csharp
public void HaltSpecialAction()
```
#INC


### InitialEncounteredCreature(RiskLevel)

```csharp
public override void InitialEncounteredCreature(RiskLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### InitialEncounteredCreature(UnitModel)

```csharp
public override void InitialEncounteredCreature(UnitModel encountered)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encountered` | `Global.UnitModel` |  |

### IsCrazy()

```csharp
public override bool IsCrazy()
```
#INC


#### Returns

**Type:** System.Boolean

### IsPanic()

```csharp
public override bool IsPanic()
```
#INC


#### Returns

**Type:** System.Boolean

### LoseControl()

```csharp
public override void LoseControl()
```
#INC


### MakeCreatureEffect(long)

```csharp
public override GameObject MakeCreatureEffect(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel)

```csharp
public override GameObject MakeCreatureEffectHead(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel, bool)

```csharp
public override GameObject MakeCreatureEffectHead(CreatureModel model, bool addlist)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `addlist` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### OnClick()

```csharp
public void OnClick()
```
#INC


### OnDie()

```csharp
public override void OnDie()
```
#INC


### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


### OnMemoEnd()

```csharp
public void OnMemoEnd()
```
#INC


### OnResurrect()

```csharp
public override void OnResurrect()
```
#INC


### OnSetWeapon()

```csharp
protected override void OnSetWeapon()
```
#INC


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


### Panic()

```csharp
public override void Panic()
```
#INC


### PanicOfficer(bool)

```csharp
public void PanicOfficer(bool force)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `force` | `System.Boolean` |  |

### PanicReadyComplete()

```csharp
public override void PanicReadyComplete()
```
#INC


### PrepareToSuicide()

```csharp
public void PrepareToSuicide()
```
#INC


### PrepareWeapon()

```csharp
public override void PrepareWeapon()
```
#INC


### ProcessAction()

```csharp
public override void ProcessAction()
```
#INC


### ProcessActionNormalOfficer()

```csharp
private void ProcessActionNormalOfficer()
```
#INC


### PursueUnconAgent(UnitModel)

```csharp
public override void PursueUnconAgent(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecoverMental(float)

```csharp
public override void RecoverMental(float amount)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### ResetAnimator()

```csharp
public override void ResetAnimator()
```
#INC


### ReturnSpecialAction()

```csharp
public void ReturnSpecialAction()
```
#INC


### ReturnToSefira()

```csharp
public override void ReturnToSefira()
```
#INC


### ReturnToSefiraFromWork()

```csharp
public void ReturnToSefiraFromWork()
```
#INC


### SetUncontrollableAction(UncontrollableAction)

```csharp
public override void SetUncontrollableAction(UncontrollableAction uncon)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uncon` | `Global.UncontrollableAction` |  |

### SetUnit(OfficerUnit)

```csharp
public void SetUnit(OfficerUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.OfficerUnit` |  |

### ShowCreatureActionSpeech(long, string)

```csharp
public override void ShowCreatureActionSpeech(long creatureID, string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureID` | `System.Int64` |  |
| `key` | `System.String` |  |

### SpecialAction(OfficerSpecialAction)

```csharp
public void SpecialAction(OfficerSpecialAction action)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `Global.OfficerSpecialAction` |  |

### SpecialActionReturn()

```csharp
public void SpecialActionReturn()
```
#INC


### SpecialActionUpdate()

```csharp
public void SpecialActionUpdate()
```
#INC


### StartAction()

```csharp
public IEnumerator<WaitForSeconds> StartAction()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IEnumerator{UnityEngine.WaitForSeconds}

### StopAction()

```csharp
public override void StopAction()
```
#INC


### StopPanic()

```csharp
public override void StopPanic()
```
#INC


### StopPanicWithoutStun()

```csharp
public override void StopPanicWithoutStun()
```
#INC


### Suicide()

```csharp
private void Suicide()
```
#INC

