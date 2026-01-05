# Class OfficerModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerModel : WorkerModel, IObserver, IMouseCommandTargetModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/UnitModel) → [WorkerModel](/api/WorkerModel) → OfficerModel

## Inherited Members
[commandQueue](/api/WorkerModel#commandqueue), [workerClass](/api/WorkerModel#workerclass), [isRealWorker](/api/WorkerModel#isrealworker), [name](/api/WorkerModel#name), [gender](/api/WorkerModel#gender), [currentSefiraEnum](/api/WorkerModel#currentsefiraenum), [_revivalHp](/api/WorkerModel#revivalhp), [_revivalMental](/api/WorkerModel#revivalmental), [_revivaledHp](/api/WorkerModel#revivaledhp), [_revivaledMental](/api/WorkerModel#revivaledmental), [movementMul](/api/WorkerModel#movementmul), [panicValue](/api/WorkerModel#panicvalue), [invincible](/api/WorkerModel#invincible), [blockRecover](/api/WorkerModel#blockrecover), [stunTime](/api/WorkerModel#stuntime), [haltUpdate](/api/WorkerModel#haltupdate), [returnPanic](/api/WorkerModel#returnpanic), [willDead](/api/WorkerModel#willdead), [_isDead](/api/WorkerModel#isdead), [speechTable](/api/WorkerModel#speechtable), [target](/api/WorkerModel#target), [targetWorker](/api/WorkerModel#targetworker), [targetObject](/api/WorkerModel#targetobject), [unconAction](/api/WorkerModel#unconaction), [animationMessageRecevied](/api/WorkerModel#animationmessagerecevied), [visible](/api/WorkerModel#visible), [waitTimer](/api/WorkerModel#waittimer), [OnWorkEndFlag](/api/WorkerModel#onworkendflag), [puppetChanged](/api/WorkerModel#puppetchanged), [lastestMoveTarget](/api/WorkerModel#lastestmovetarget), [deadSceneName](/api/WorkerModel#deadscenename), [seperator](/api/WorkerModel#seperator), [hasUniqueFace](/api/WorkerModel#hasuniqueface), [hairSprite](/api/WorkerModel#hairsprite), [faceSprite](/api/WorkerModel#facesprite), [stunEffect](/api/WorkerModel#stuneffect), [spriteData](/api/WorkerModel#spritedata), [_panicData](/api/WorkerModel#panicdata), [isChangeableAnimator](/api/WorkerModel#ischangeableanimator), [OnStageStart()](/api/WorkerModel#onstagestart), [GetSaveData()](/api/WorkerModel#getsavedata), [TryGetValue<T>(Dictionary<string, object>, string, ref T)](Global.WorkerModel.html#WorkerModel_TryGetValue__1_System_Collections_Generic_Dictionary_System_String_System_Object__System_String___0__), [LoadData(Dictionary<string, object>)](/api/WorkerModel#loaddata-dictionary-string-object), [HaltUpdate()](/api/WorkerModel#haltupdate), [ReleaseUpdate()](/api/WorkerModel#releaseupdate), [ResetSprite()](/api/WorkerModel#resetsprite), [GetCurrentNode()](/api/WorkerModel#getcurrentnode), [SetCurrentNode(MapNode)](/api/WorkerModel#setcurrentnode-mapnode), [GetCurrentEdge()](/api/WorkerModel#getcurrentedge), [GetEdgeDirection()](/api/WorkerModel#getedgedirection), [GetCurrentCommand()](/api/WorkerModel#getcurrentcommand), [MoveToNode(MapNode)](/api/WorkerModel#movetonode-mapnode), [MoveToNode(MapNode, bool)](/api/WorkerModel#movetonode-mapnode-bool), [MoveToMovable(MovableObjectNode)](/api/WorkerModel#movetomovable-movableobjectnode), [MoveFromNullPassage()](/api/WorkerModel#movefromnullpassage), [MoveToMovable(MovableObjectNode, bool)](/api/WorkerModel#movetomovable-movableobjectnode-bool), [MoveToNode(string)](/api/WorkerModel#movetonode-string), [FollowMovable(MovableObjectNode)](/api/WorkerModel#followmovable-movableobjectnode), [IsDead()](/api/WorkerModel#isdead), [GetConnectedNode()](/api/WorkerModel#getconnectednode), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/WorkerModel#takedamagewithouteffect-unitmodel-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/WorkerModel#takedamage-unitmodel-damageinfo), [CreatePhysicalDamagedEffect(float)](/api/WorkerModel#createphysicaldamagedeffect-float), [CreateMentalDamagedEffect(float)](/api/WorkerModel#creatementaldamagedeffect-float), [IsAttackTargetable()](/api/WorkerModel#isattacktargetable), [IsHostile(UnitModel)](/api/WorkerModel#ishostile-unitmodel), [RecentlyAttackedCreature(CreatureModel)](/api/WorkerModel#recentlyattackedcreature-creaturemodel), [TakeMentalDamage(float, MentalDamageOption)](/api/WorkerModel#takementaldamage-float-mentaldamageoption), [TakeMentalDamage(float)](/api/WorkerModel#takementaldamage-float), [MakeSpatteredBlood()](/api/WorkerModel#makespatteredblood), [RecoverHP(float)](/api/WorkerModel#recoverhp-float), [SetInvincible(bool)](/api/WorkerModel#setinvincible-bool), [Stun(float)](/api/WorkerModel#stun-float), [StopStun()](/api/WorkerModel#stopstun), [OnAttackWorker(WorkerModel)](/api/WorkerModel#onattackworker-workermodel), [IsSuppable()](/api/WorkerModel#issuppable), [SetCustsomCommand(WorkerCommand)](/api/WorkerModel#setcustsomcommand-workercommand), [Die()](/api/WorkerModel#die), [AfterDeadAnim()](/api/WorkerModel#afterdeadanim), [InteractWithDoor(DoorObjectModel)](/api/WorkerModel#interactwithdoor-doorobjectmodel), [CompareByName(WorkerModel, WorkerModel)](/api/WorkerModel#comparebyname-workermodel-workermodel), [IsInSefira()](/api/WorkerModel#isinsefira), [OnNotice(string, params object[])](/api/WorkerModel#onnotice-string-params-object), [SetSpecialDeadScene(string)](/api/WorkerModel#setspecialdeadscene-string), [SetSpecialDeadScene(string, bool)](/api/WorkerModel#setspecialdeadscene-string-bool), [SetSpecialDeadScene(string, bool, bool)](/api/WorkerModel#setspecialdeadscene-string-bool-bool), [ResetSpecialDeadScene()](/api/WorkerModel#resetspecialdeadscene), [CompareByID(WorkerModel, WorkerModel)](/api/WorkerModel#comparebyid-workermodel-workermodel), [CompareBySefira(WorkerModel, WorkerModel)](/api/WorkerModel#comparebysefira-workermodel-workermodel), [ShowUnconSpeech(string)](/api/WorkerModel#showunconspeech-string), [MakeCreatureEffect(CreatureModel)](/api/WorkerModel#makecreatureeffect-creaturemodel), [SetWorkerFaceType(WorkerFaceType)](/api/WorkerModel#setworkerfacetype-workerfacetype), [PlayAttackAnimation(string)](/api/WorkerModel#playattackanimation-string), [ShowSpeech(string)](/api/WorkerModel#showspeech-string), [ChangePuppet(string)](/api/WorkerModel#changepuppet-string), [SetAgentCommand(WorkerCommand)](/api/WorkerModel#setagentcommand-workercommand), [SetDeadType(DeadType)](/api/WorkerModel#setdeadtype-deadtype), [SetPanicAnim(bool)](/api/WorkerModel#setpanicanim-bool), [OnStun(float)](/api/WorkerModel#onstun-float), [OnStunEffectDestroied()](/api/WorkerModel#onstuneffectdestroied), [OnSetArmor()](/api/WorkerModel#onsetarmor), [CheckEGOGift()](/api/WorkerModel#checkegogift), [GetWeaponSprite()](/api/WorkerModel#getweaponsprite), [SpecialAttackDamage(TrackEntry, Event)](/api/WorkerModel#specialattackdamage-trackentry-event), [SpecialAttackEnd(TrackEntry)](/api/WorkerModel#specialattackend-trackentry), [fortitudeLevel](/api/WorkerModel#fortitudelevel), [prudenceLevel](/api/WorkerModel#prudencelevel), [temperanceLevel](/api/WorkerModel#temperancelevel), [justiceLevel](/api/WorkerModel#justicelevel), [currentSefira](/api/WorkerModel#currentsefira), [CurrentPanicAction](/api/WorkerModel#currentpanicaction), [recentlyAttacked](/api/WorkerModel#recentlyattacked), [attackTargetWorker](/api/WorkerModel#attacktargetworker), [specialDeadScene](/api/WorkerModel#specialdeadscene), [workerAnimator](/api/WorkerModel#workeranimator), [panicData](/api/WorkerModel#panicdata), [DeadType](/api/WorkerModel#deadtype), [stunCriteria](/api/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/UnitModel#defaultstuneffectsrc), [instanceId](/api/UnitModel#instanceid), [movableNode](/api/UnitModel#movablenode), [shield](/api/UnitModel#shield), [_equipment](/api/UnitModel#equipment), [tempAnim](/api/UnitModel#tempanim), [factionTypeInfo](/api/UnitModel#factiontypeinfo), [stunTimer](/api/UnitModel#stuntimer), [hp](/api/UnitModel#hp), [mental](/api/UnitModel#mental), [baseMaxHp](/api/UnitModel#basemaxhp), [baseMaxMental](/api/UnitModel#basemaxmental), [baseMovement](/api/UnitModel#basemovement), [baseRegeneration](/api/UnitModel#baseregeneration), [baseRegenerationDelay](/api/UnitModel#baseregenerationdelay), [additionalDef](/api/UnitModel#additionaldef), [superArmorMax](/api/UnitModel#superarmormax), [superArmor](/api/UnitModel#superarmor), [superArmorDefense](/api/UnitModel#superarmordefense), [remainMoveDelay](/api/UnitModel#remainmovedelay), [remainAttackDelay](/api/UnitModel#remainattackdelay), [isStun](/api/UnitModel#isstun), [damageTransform](/api/UnitModel#damagetransform), [basePhysicalDefense](/api/UnitModel#basephysicaldefense), [baseMentalDefense](/api/UnitModel#basementaldefense), [encounteredWorker](/api/UnitModel#encounteredworker), [_bufList](/api/UnitModel#buflist), [_statBufList](/api/UnitModel#statbuflist), [_barrierBufList](/api/UnitModel#barrierbuflist), [CanOpenDoor()](/api/UnitModel#canopendoor), [OnStopMovableByShield(AgentModel)](/api/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/UnitModel#releasekitcreature-bool), [OnReleaseWeapon()](/api/UnitModel#onreleaseweapon), [OnReleaseArmor()](/api/UnitModel#onreleasearmor), [OnChangeGift()](/api/UnitModel#onchangegift), [OnSetKitCreature()](/api/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/UnitModel#getweaponspritesrc), [Attack(UnitModel)](/api/UnitModel#attack-unitmodel), [IsAttackState()](/api/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/UnitModel#endattackanimation), [GetEGObonus()](/api/UnitModel#getegobonus), [HasEquipment(int)](/api/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/UnitModel#checknearworkerencounting), [IsStunned()](/api/UnitModel#isstunned), [OnSuperArmorBreak()](/api/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/UnitModel#setattackdelay-float), [UpdateBufState()](/api/UnitModel#updatebufstate), [GetRiskLevel()](/api/UnitModel#getrisklevel), [GetAttackLevel()](/api/UnitModel#getattacklevel), [GetDefenseLevel()](/api/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/UnitModel#setfaction-string), [GetFaction()](/api/UnitModel#getfaction), [SetFactionForcely(string)](/api/UnitModel#setfactionforcely-string), [OnStunEnd()](/api/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/UnitModel#getunitbuflist), [Equipment](/api/UnitModel#equipment), [radius](/api/UnitModel#radius), [maxHp](/api/UnitModel#maxhp), [maxMental](/api/UnitModel#maxmental), [movement](/api/UnitModel#movement), [regeneration](/api/UnitModel#regeneration), [regenerationDelay](/api/UnitModel#regenerationdelay), [attackSpeed](/api/UnitModel#attackspeed), [damage](/api/UnitModel#damage), [physicalDefense](/api/UnitModel#physicaldefense), [mentalDefense](/api/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OfficerModel(long, string)

```csharp
public OfficerModel(long id, string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `area` | `System.String` |  |

## Fields

### isDebugger

```csharp
public bool isDebugger
```

#### Field Value

**Type:** System.Boolean

### lookingDir

```csharp
public LOOKINGDIR lookingDir
```

#### Field Value

**Type:** Global.LOOKINGDIR

### mentalReturn

```csharp
public int mentalReturn
```

#### Field Value

**Type:** System.Int32

### recoveryRate

```csharp
public int recoveryRate
```

#### Field Value

**Type:** System.Int32

### startSpecialAction

```csharp
public bool startSpecialAction
```

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

### CannotControll()

```csharp
public override bool CannotControll()
```

#### Returns

**Type:** System.Boolean

### ChangeHairSprite(SpriteInfo)

```csharp
public override void ChangeHairSprite(SpriteInfo spriteInfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteInfo` | `Global.SpriteInfo` |  |

### ChangePuppetAnimToDie(string)

```csharp
public override WorkerDeadScript ChangePuppetAnimToDie(string src)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### ClearEffect()

```csharp
public override void ClearEffect()
```

### ClearUnconCommand()

```csharp
public override void ClearUnconCommand()
```

### EncounterCreature(UnitModel)

```csharp
public override void EncounterCreature(UnitModel encounteredCreature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encounteredCreature` | `Global.UnitModel` |  |

### EncounterStandingItem(StandingItemModel)

```csharp
public override void EncounterStandingItem(StandingItemModel standing)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### EndSpecialAction()

```csharp
public void EndSpecialAction()
```

### GetControl()

```csharp
public override void GetControl()
```

### GetCurrentSefira()

```csharp
public override Sefira GetCurrentSefira()
```

#### Returns

**Type:** Global.Sefira

### GetState()

```csharp
public OfficerAIState GetState()
```

#### Returns

**Type:** Global.OfficerAIState

### GetUnit()

```csharp
public OfficerUnit GetUnit()
```

#### Returns

**Type:** Global.OfficerUnit

### GetUnitName()

```csharp
public override string GetUnitName()
```

#### Returns

**Type:** System.String

### GetWorkerUnit()

```csharp
public override WorkerUnit GetWorkerUnit()
```

#### Returns

**Type:** Global.WorkerUnit

### HaltSpecialAction()

```csharp
public void HaltSpecialAction()
```

### InitialEncounteredCreature(RiskLevel)

```csharp
public override void InitialEncounteredCreature(RiskLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### InitialEncounteredCreature(UnitModel)

```csharp
public override void InitialEncounteredCreature(UnitModel encountered)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encountered` | `Global.UnitModel` |  |

### IsCrazy()

```csharp
public override bool IsCrazy()
```

#### Returns

**Type:** System.Boolean

### IsPanic()

```csharp
public override bool IsPanic()
```

#### Returns

**Type:** System.Boolean

### LoseControl()

```csharp
public override void LoseControl()
```

### MakeCreatureEffect(long)

```csharp
public override GameObject MakeCreatureEffect(long id)
```

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

### OnDie()

```csharp
public override void OnDie()
```

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnMemoEnd()

```csharp
public void OnMemoEnd()
```

### OnResurrect()

```csharp
public override void OnResurrect()
```

### OnSetWeapon()

```csharp
protected override void OnSetWeapon()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### Panic()

```csharp
public override void Panic()
```

### PanicOfficer(bool)

```csharp
public void PanicOfficer(bool force)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `force` | `System.Boolean` |  |

### PanicReadyComplete()

```csharp
public override void PanicReadyComplete()
```

### PrepareToSuicide()

```csharp
public void PrepareToSuicide()
```

### PrepareWeapon()

```csharp
public override void PrepareWeapon()
```

### ProcessAction()

```csharp
public override void ProcessAction()
```

### PursueUnconAgent(UnitModel)

```csharp
public override void PursueUnconAgent(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecoverMental(float)

```csharp
public override void RecoverMental(float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### ResetAnimator()

```csharp
public override void ResetAnimator()
```

### ReturnSpecialAction()

```csharp
public void ReturnSpecialAction()
```

### ReturnToSefira()

```csharp
public override void ReturnToSefira()
```

### ReturnToSefiraFromWork()

```csharp
public void ReturnToSefiraFromWork()
```

### SetUncontrollableAction(UncontrollableAction)

```csharp
public override void SetUncontrollableAction(UncontrollableAction uncon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uncon` | `Global.UncontrollableAction` |  |

### SetUnit(OfficerUnit)

```csharp
public void SetUnit(OfficerUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.OfficerUnit` |  |

### ShowCreatureActionSpeech(long, string)

```csharp
public override void ShowCreatureActionSpeech(long creatureID, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureID` | `System.Int64` |  |
| `key` | `System.String` |  |

### SpecialAction(OfficerSpecialAction)

```csharp
public void SpecialAction(OfficerSpecialAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `Global.OfficerSpecialAction` |  |

### SpecialActionReturn()

```csharp
public void SpecialActionReturn()
```

### SpecialActionUpdate()

```csharp
public void SpecialActionUpdate()
```

### StartAction()

```csharp
public IEnumerator<WaitForSeconds> StartAction()
```

#### Returns

**Type:** System.Collections.Generic.IEnumerator{UnityEngine.WaitForSeconds}

### StopAction()

```csharp
public override void StopAction()
```

### StopPanic()

```csharp
public override void StopPanic()
```

### StopPanicWithoutStun()

```csharp
public override void StopPanicWithoutStun()
```
