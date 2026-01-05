# Class AgentModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentModel : WorkerModel, IObserver, IMouseCommandTargetModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/UnitModel) → [WorkerModel](/api/WorkerModel) → AgentModel

## Inherited Members
[commandQueue](/api/WorkerModel#commandqueue), [workerClass](/api/WorkerModel#workerclass), [isRealWorker](/api/WorkerModel#isrealworker), [name](/api/WorkerModel#name), [gender](/api/WorkerModel#gender), [currentSefiraEnum](/api/WorkerModel#currentsefiraenum), [_revivalHp](/api/WorkerModel#revivalhp), [_revivalMental](/api/WorkerModel#revivalmental), [_revivaledHp](/api/WorkerModel#revivaledhp), [_revivaledMental](/api/WorkerModel#revivaledmental), [movementMul](/api/WorkerModel#movementmul), [panicValue](/api/WorkerModel#panicvalue), [invincible](/api/WorkerModel#invincible), [blockRecover](/api/WorkerModel#blockrecover), [stunTime](/api/WorkerModel#stuntime), [haltUpdate](/api/WorkerModel#haltupdate), [returnPanic](/api/WorkerModel#returnpanic), [willDead](/api/WorkerModel#willdead), [_isDead](/api/WorkerModel#isdead), [speechTable](/api/WorkerModel#speechtable), [target](/api/WorkerModel#target), [targetWorker](/api/WorkerModel#targetworker), [targetObject](/api/WorkerModel#targetobject), [unconAction](/api/WorkerModel#unconaction), [animationMessageRecevied](/api/WorkerModel#animationmessagerecevied), [visible](/api/WorkerModel#visible), [waitTimer](/api/WorkerModel#waittimer), [OnWorkEndFlag](/api/WorkerModel#onworkendflag), [puppetChanged](/api/WorkerModel#puppetchanged), [lastestMoveTarget](/api/WorkerModel#lastestmovetarget), [deadSceneName](/api/WorkerModel#deadscenename), [seperator](/api/WorkerModel#seperator), [hasUniqueFace](/api/WorkerModel#hasuniqueface), [hairSprite](/api/WorkerModel#hairsprite), [faceSprite](/api/WorkerModel#facesprite), [stunEffect](/api/WorkerModel#stuneffect), [spriteData](/api/WorkerModel#spritedata), [_panicData](/api/WorkerModel#panicdata), [isChangeableAnimator](/api/WorkerModel#ischangeableanimator), [TryGetValue<T>(Dictionary<string, object>, string, ref T)](Global.WorkerModel.html#WorkerModel_TryGetValue__1_System_Collections_Generic_Dictionary_System_String_System_Object__System_String___0__), [HaltUpdate()](/api/WorkerModel#haltupdate), [ReleaseUpdate()](/api/WorkerModel#releaseupdate), [ResetSprite()](/api/WorkerModel#resetsprite), [GetCurrentNode()](/api/WorkerModel#getcurrentnode), [SetCurrentNode(MapNode)](/api/WorkerModel#setcurrentnode-mapnode), [GetCurrentEdge()](/api/WorkerModel#getcurrentedge), [GetEdgeDirection()](/api/WorkerModel#getedgedirection), [GetCurrentCommand()](/api/WorkerModel#getcurrentcommand), [ReturnToSefira()](/api/WorkerModel#returntosefira), [MoveToNode(MapNode)](/api/WorkerModel#movetonode-mapnode), [MoveToNode(MapNode, bool)](/api/WorkerModel#movetonode-mapnode-bool), [MoveToMovable(MovableObjectNode)](/api/WorkerModel#movetomovable-movableobjectnode), [MoveFromNullPassage()](/api/WorkerModel#movefromnullpassage), [MoveToMovable(MovableObjectNode, bool)](/api/WorkerModel#movetomovable-movableobjectnode-bool), [MoveToNode(string)](/api/WorkerModel#movetonode-string), [IsDead()](/api/WorkerModel#isdead), [GetConnectedNode()](/api/WorkerModel#getconnectednode), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/WorkerModel#takedamagewithouteffect-unitmodel-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/WorkerModel#takedamage-unitmodel-damageinfo), [CreatePhysicalDamagedEffect(float)](/api/WorkerModel#createphysicaldamagedeffect-float), [CreateMentalDamagedEffect(float)](/api/WorkerModel#creatementaldamagedeffect-float), [IsHostile(UnitModel)](/api/WorkerModel#ishostile-unitmodel), [TakeMentalDamage(float, MentalDamageOption)](/api/WorkerModel#takementaldamage-float-mentaldamageoption), [TakeMentalDamage(float)](/api/WorkerModel#takementaldamage-float), [MakeSpatteredBlood()](/api/WorkerModel#makespatteredblood), [SetInvincible(bool)](/api/WorkerModel#setinvincible-bool), [Stun(float)](/api/WorkerModel#stun-float), [StopStun()](/api/WorkerModel#stopstun), [OnAttackWorker(WorkerModel)](/api/WorkerModel#onattackworker-workermodel), [IsSuppable()](/api/WorkerModel#issuppable), [SetCustsomCommand(WorkerCommand)](/api/WorkerModel#setcustsomcommand-workercommand), [Die()](/api/WorkerModel#die), [AfterDeadAnim()](/api/WorkerModel#afterdeadanim), [InteractWithDoor(DoorObjectModel)](/api/WorkerModel#interactwithdoor-doorobjectmodel), [CompareByName(WorkerModel, WorkerModel)](/api/WorkerModel#comparebyname-workermodel-workermodel), [IsInSefira()](/api/WorkerModel#isinsefira), [SetSpecialDeadScene(string)](/api/WorkerModel#setspecialdeadscene-string), [SetSpecialDeadScene(string, bool)](/api/WorkerModel#setspecialdeadscene-string-bool), [SetSpecialDeadScene(string, bool, bool)](/api/WorkerModel#setspecialdeadscene-string-bool-bool), [ResetSpecialDeadScene()](/api/WorkerModel#resetspecialdeadscene), [CompareByID(WorkerModel, WorkerModel)](/api/WorkerModel#comparebyid-workermodel-workermodel), [CompareBySefira(WorkerModel, WorkerModel)](/api/WorkerModel#comparebysefira-workermodel-workermodel), [ShowUnconSpeech(string)](/api/WorkerModel#showunconspeech-string), [MakeCreatureEffect(CreatureModel)](/api/WorkerModel#makecreatureeffect-creaturemodel), [SetWorkerFaceType(WorkerFaceType)](/api/WorkerModel#setworkerfacetype-workerfacetype), [PlayAttackAnimation(string)](/api/WorkerModel#playattackanimation-string), [ShowSpeech(string)](/api/WorkerModel#showspeech-string), [ChangePuppet(string)](/api/WorkerModel#changepuppet-string), [SetAgentCommand(WorkerCommand)](/api/WorkerModel#setagentcommand-workercommand), [SetDeadType(DeadType)](/api/WorkerModel#setdeadtype-deadtype), [SetPanicAnim(bool)](/api/WorkerModel#setpanicanim-bool), [OnStun(float)](/api/WorkerModel#onstun-float), [OnStunEffectDestroied()](/api/WorkerModel#onstuneffectdestroied), [CheckEGOGift()](/api/WorkerModel#checkegogift), [GetWeaponSprite()](/api/WorkerModel#getweaponsprite), [SpecialAttackDamage(TrackEntry, Event)](/api/WorkerModel#specialattackdamage-trackentry-event), [SpecialAttackEnd(TrackEntry)](/api/WorkerModel#specialattackend-trackentry), [currentSefira](/api/WorkerModel#currentsefira), [CurrentPanicAction](/api/WorkerModel#currentpanicaction), [recentlyAttacked](/api/WorkerModel#recentlyattacked), [attackTargetWorker](/api/WorkerModel#attacktargetworker), [specialDeadScene](/api/WorkerModel#specialdeadscene), [workerAnimator](/api/WorkerModel#workeranimator), [panicData](/api/WorkerModel#panicdata), [DeadType](/api/WorkerModel#deadtype), [stunCriteria](/api/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/UnitModel#defaultstuneffectsrc), [instanceId](/api/UnitModel#instanceid), [movableNode](/api/UnitModel#movablenode), [shield](/api/UnitModel#shield), [_equipment](/api/UnitModel#equipment), [tempAnim](/api/UnitModel#tempanim), [factionTypeInfo](/api/UnitModel#factiontypeinfo), [stunTimer](/api/UnitModel#stuntimer), [hp](/api/UnitModel#hp), [mental](/api/UnitModel#mental), [baseMaxHp](/api/UnitModel#basemaxhp), [baseMaxMental](/api/UnitModel#basemaxmental), [baseMovement](/api/UnitModel#basemovement), [baseRegeneration](/api/UnitModel#baseregeneration), [baseRegenerationDelay](/api/UnitModel#baseregenerationdelay), [additionalDef](/api/UnitModel#additionaldef), [superArmorMax](/api/UnitModel#superarmormax), [superArmor](/api/UnitModel#superarmor), [superArmorDefense](/api/UnitModel#superarmordefense), [remainMoveDelay](/api/UnitModel#remainmovedelay), [remainAttackDelay](/api/UnitModel#remainattackdelay), [isStun](/api/UnitModel#isstun), [damageTransform](/api/UnitModel#damagetransform), [basePhysicalDefense](/api/UnitModel#basephysicaldefense), [baseMentalDefense](/api/UnitModel#basementaldefense), [encounteredWorker](/api/UnitModel#encounteredworker), [_bufList](/api/UnitModel#buflist), [_statBufList](/api/UnitModel#statbuflist), [_barrierBufList](/api/UnitModel#barrierbuflist), [CanOpenDoor()](/api/UnitModel#canopendoor), [OnStopMovableByShield(AgentModel)](/api/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/UnitModel#releasekitcreature-bool), [GetWeaponSpriteSrc()](/api/UnitModel#getweaponspritesrc), [Attack(UnitModel)](/api/UnitModel#attack-unitmodel), [IsAttackState()](/api/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/UnitModel#getdamagefactorbyequipment), [OnEndAttackCycle()](/api/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/UnitModel#endattackanimation), [GetEGObonus()](/api/UnitModel#getegobonus), [HasEquipment(int)](/api/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/UnitModel#makedamageeffect-rwbptype-float-type), [ClearWorkerEncounting()](/api/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/UnitModel#checknearworkerencounting), [IsStunned()](/api/UnitModel#isstunned), [OnSuperArmorBreak()](/api/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/UnitModel#setattackdelay-float), [UpdateBufState()](/api/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/UnitModel#setfaction-string), [GetFaction()](/api/UnitModel#getfaction), [SetFactionForcely(string)](/api/UnitModel#setfactionforcely-string), [OnStunEnd()](/api/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/UnitModel#getunitbuflist), [Equipment](/api/UnitModel#equipment), [radius](/api/UnitModel#radius), [damage](/api/UnitModel#damage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentModel(long)

```csharp
public AgentModel(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

## Fields

### _agentName

```csharp
public AgentName _agentName
```

#### Field Value

**Type:** Global.AgentName

### activated

```csharp
public bool activated
```

#### Field Value

**Type:** System.Boolean

### cannotBeAttackTargetable

```csharp
public bool cannotBeAttackTargetable
```

#### Field Value

**Type:** System.Boolean

### continuousServiceDay

```csharp
public int continuousServiceDay
```

#### Field Value

**Type:** System.Int32

### counterAttackEnabled

```csharp
public bool counterAttackEnabled
```

#### Field Value

**Type:** System.Boolean

### forcelyPanicType

```csharp
public RwbpType forcelyPanicType
```

#### Field Value

**Type:** Global.RwbpType

### history

```csharp
public AgentHistory history
```

#### Field Value

**Type:** Global.AgentHistory

### isAce

```csharp
public bool isAce
```

#### Field Value

**Type:** System.Boolean

### iscustom

```csharp
public bool iscustom
```

#### Field Value

**Type:** System.Boolean

### isUniqueCredit

```csharp
public bool isUniqueCredit
```

#### Field Value

**Type:** System.Boolean

### lastServiceSefira

```csharp
public string lastServiceSefira
```

#### Field Value

**Type:** System.String

### levelSetting

```csharp
public ValueInfo levelSetting
```

#### Field Value

**Type:** Global.ValueInfo

### MaxLevel

```csharp
public const int MaxLevel = 5
```

#### Field Value

**Type:** System.Int32

### MinLevel

```csharp
public const int MinLevel = 1
```

#### Field Value

**Type:** System.Int32

### primaryStat

```csharp
public WorkerPrimaryStat primaryStat
```

#### Field Value

**Type:** Global.WorkerPrimaryStat

### primaryStatExp

```csharp
public WorkerPrimaryStatExp primaryStatExp
```

#### Field Value

**Type:** Global.WorkerPrimaryStatExp

### randomLevel

```csharp
public string[] randomLevel
```

#### Field Value

**Type:** System.String[]

### randomOverlay

```csharp
public string[] randomOverlay
```

#### Field Value

**Type:** System.String[]

### StatusSprites

```csharp
public Sprite[] StatusSprites
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### tempFaceSpriteInfo

```csharp
public SpriteInfo tempFaceSpriteInfo
```

#### Field Value

**Type:** Global.SpriteInfo

### tempHairSpriteInfo

```csharp
public SpriteInfo tempHairSpriteInfo
```

#### Field Value

**Type:** Global.SpriteInfo

### uiActivated

```csharp
public bool uiActivated
```

#### Field Value

**Type:** System.Boolean

### uniqueScriptIndex

```csharp
public int uniqueScriptIndex
```

#### Field Value

**Type:** System.Int32

### workEndReaction

```csharp
public bool workEndReaction
```

#### Field Value

**Type:** System.Boolean

## Properties

### attackSpeed

```csharp
public override float attackSpeed { get; }
```

#### Property Value

**Type:** System.Single

### bestRwbp

```csharp
public RwbpType bestRwbp { get; }
```

#### Property Value

**Type:** Global.RwbpType

### Bstat

```csharp
public int Bstat { get; }
```

#### Property Value

**Type:** System.Int32

### canCancelCurrentWork

```csharp
public bool canCancelCurrentWork { get; }
```

#### Property Value

**Type:** System.Boolean

### CheckSuppressCommand

```csharp
public AgentModel.CheckCommandState CheckSuppressCommand { get; }
```

#### Property Value

**Type:** Global.AgentModel.CheckCommandState

### CheckWorkCommand

```csharp
public AgentModel.CheckCommandState CheckWorkCommand { get; }
```

#### Property Value

**Type:** Global.AgentModel.CheckCommandState

### currentSkill

```csharp
public UseSkill currentSkill { get; set; }
```

#### Property Value

**Type:** Global.UseSkill

### defense

```csharp
public override DefenseInfo defense { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

### eventHandler

```csharp
public AgentModelEventHandler eventHandler { get; }
```

#### Property Value

**Type:** Global.AgentModelEventHandler

### fortitudeLevel

```csharp
public override int fortitudeLevel { get; }
```

#### Property Value

**Type:** System.Int32

### fortitudeStat

```csharp
public int fortitudeStat { get; }
```

#### Property Value

**Type:** System.Int32

### IsAutoSuppressing

```csharp
public bool IsAutoSuppressing { get; }
```

#### Property Value

**Type:** System.Boolean

### justiceLevel

```csharp
public override int justiceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### justiceStat

```csharp
public int justiceStat { get; }
```

#### Property Value

**Type:** System.Int32

### level

```csharp
public int level { get; }
```

#### Property Value

**Type:** System.Int32

### maxHp

```csharp
public override int maxHp { get; }
```

#### Property Value

**Type:** System.Int32

### maxMental

```csharp
public override int maxMental { get; }
```

#### Property Value

**Type:** System.Int32

### mentalDefense

```csharp
public override int mentalDefense { get; }
```

#### Property Value

**Type:** System.Int32

### movement

```csharp
public override float movement { get; }
```

#### Property Value

**Type:** System.Single

### originFortitudeLevel

```csharp
public int originFortitudeLevel { get; }
```

#### Property Value

**Type:** System.Int32

### originFortitudeStat

```csharp
public int originFortitudeStat { get; }
```

#### Property Value

**Type:** System.Int32

### originJusticeLevel

```csharp
public int originJusticeLevel { get; }
```

#### Property Value

**Type:** System.Int32

### originJusticeStat

```csharp
public int originJusticeStat { get; }
```

#### Property Value

**Type:** System.Int32

### originPrudenceLevel

```csharp
public int originPrudenceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### originPrudenceStat

```csharp
public int originPrudenceStat { get; }
```

#### Property Value

**Type:** System.Int32

### originTemperanceLevel

```csharp
public int originTemperanceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### originTemperanceStat

```csharp
public int originTemperanceStat { get; }
```

#### Property Value

**Type:** System.Int32

### physicalDefense

```csharp
public override int physicalDefense { get; }
```

#### Property Value

**Type:** System.Int32

### prudenceLevel

```csharp
public override int prudenceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### prudenceStat

```csharp
public int prudenceStat { get; }
```

#### Property Value

**Type:** System.Int32

### Pstat

```csharp
public int Pstat { get; }
```

#### Property Value

**Type:** System.Int32

### regeneration

```csharp
public override int regeneration { get; }
```

#### Property Value

**Type:** System.Int32

### regenerationDelay

```csharp
public override float regenerationDelay { get; }
```

#### Property Value

**Type:** System.Single

### regenerationMental

```csharp
public int regenerationMental { get; }
```

#### Property Value

**Type:** System.Int32

### regenerationMentalDelay

```csharp
public float regenerationMentalDelay { get; }
```

#### Property Value

**Type:** System.Single

### Rstat

```csharp
public int Rstat { get; }
```

#### Property Value

**Type:** System.Int32

### temperanceLevel

```csharp
public override int temperanceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### temperanceStat

```csharp
public int temperanceStat { get; }
```

#### Property Value

**Type:** System.Int32

### titleBonus

```csharp
public WorkerPrimaryStatBonus titleBonus { get; }
```

#### Property Value

**Type:** Global.WorkerPrimaryStatBonus

### workProb

```csharp
public int workProb { get; }
```

#### Property Value

**Type:** System.Int32

### workSpeed

```csharp
public int workSpeed { get; }
```

#### Property Value

**Type:** System.Int32

### Wstat

```csharp
public int Wstat { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddSkill(long)

```csharp
public void AddSkill(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### AddSpecialSkill(long)

```csharp
public void AddSpecialSkill(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### AddSpecialSkill(SkillTypeInfo)

```csharp
public void AddSpecialSkill(SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |

### calc(int, int)

```csharp
public int calc(int value, int standard)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |
| `standard` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### CalculateStatLevel(int)

```csharp
public static int CalculateStatLevel(int stat)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stat` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### CalculateStatLevelForCustomizing(int)

```csharp
public static int CalculateStatLevelForCustomizing(int stat)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stat` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

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

### CanObserveCreature(CreatureModel)

```csharp
public bool CanObserveCreature(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

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

### CompareByBattle(AgentModel, AgentModel)

```csharp
public static int CompareByBattle(AgentModel x, AgentModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.AgentModel` |  |
| `y` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Int32

### CompareByID(AgentModel, AgentModel)

```csharp
public static int CompareByID(AgentModel x, AgentModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.AgentModel` |  |
| `y` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Int32

### CompareByLevel(AgentModel, AgentModel)

```csharp
public static int CompareByLevel(AgentModel x, AgentModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.AgentModel` |  |
| `y` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Int32

### CompareBySefira(AgentModel, AgentModel)

```csharp
public static int CompareBySefira(AgentModel x, AgentModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.AgentModel` |  |
| `y` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Int32

### CreatureActionSpeechByAnim(string)

```csharp
public void CreatureActionSpeechByAnim(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### DebugDamage(RwbpType, int)

```csharp
public void DebugDamage(RwbpType type, int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `damage` | `System.Int32` |  |

### DummyCheckCommand()

```csharp
public static bool DummyCheckCommand()
```

#### Returns

**Type:** System.Boolean

### EncounterCreature(CreatureModel, AgentModel)

```csharp
public void EncounterCreature(CreatureModel encounteredCreature, AgentModel infected)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encounteredCreature` | `Global.CreatureModel` |  |
| `infected` | `Global.AgentModel` |  |

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

### FinishManage()

```csharp
public void FinishManage()
```

### FinishObserve()

```csharp
public void FinishObserve()
```

### FinishOpenIolateRoom()

```csharp
public void FinishOpenIolateRoom()
```

### FinishPursueAgent()

```csharp
public void FinishPursueAgent()
```

### FinishReturnCreature()

```csharp
public void FinishReturnCreature()
```

### FinishReturnKitCreature()

```csharp
public void FinishReturnKitCreature()
```

### FinishSuppress()

```csharp
public void FinishSuppress()
```

### FollowMovable(MovableObjectNode)

```csharp
public void FollowMovable(MovableObjectNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MovableObjectNode` |  |

### ForcelyCancelSuppress()

```csharp
public void ForcelyCancelSuppress()
```

### ForcelyCancelWork()

```csharp
public void ForcelyCancelWork()
```

### ForcelyPanic(RwbpType)

```csharp
public void ForcelyPanic(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

### GetAgentSkillSprite(AgentModel)

```csharp
public static Sprite[] GetAgentSkillSprite(AgentModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

#### Returns

**Type:** UnityEngine.Sprite[]

### GetAllGifts()

```csharp
public List<EGOgiftModel> GetAllGifts()
```

#### Returns

**Type:** System.Collections.Generic.List{EGOgiftModel}

### GetAttackLevel()

```csharp
public override int GetAttackLevel()
```

#### Returns

**Type:** System.Int32

### GetAttackSpeedBufBySefiraAbility()

```csharp
public int GetAttackSpeedBufBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetContinuousServiceLevel()

```csharp
public int GetContinuousServiceLevel()
```

#### Returns

**Type:** System.Int32

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

### GetDamageFactorBySefiraAbility()

```csharp
public override float GetDamageFactorBySefiraAbility()
```

#### Returns

**Type:** System.Single

### GetDefaultLevel1Stat()

```csharp
public static int GetDefaultLevel1Stat()
```

#### Returns

**Type:** System.Int32

### GetDefaultStat()

```csharp
public static WorkerPrimaryStat GetDefaultStat()
```

#### Returns

**Type:** Global.WorkerPrimaryStat

### GetDefenseLevel()

```csharp
public override int GetDefenseLevel()
```

#### Returns

**Type:** System.Int32

### GetFortitudeStatBySefiraAbility()

```csharp
public int GetFortitudeStatBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetJusticeStatBySefiraAbility()

```csharp
public int GetJusticeStatBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetLevelGradeText(AgentModel)

```csharp
public static string GetLevelGradeText(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

#### Returns

**Type:** System.String

### GetLevelGradeText(int)

```csharp
public static string GetLevelGradeText(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetLifeStyleEnumToString(PersonalityType)

```csharp
public static string GetLifeStyleEnumToString(PersonalityType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.PersonalityType` |  |

#### Returns

**Type:** System.String

### GetMovementBufBySefiraAbility()

```csharp
public int GetMovementBufBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetMovementValue()

```csharp
public float GetMovementValue()
```

#### Returns

**Type:** System.Single

### GetNormalSKill()

```csharp
public AgentModel.SkillInfo[] GetNormalSKill()
```

#### Returns

**Type:** Global.AgentModel.SkillInfo[]

### GetOldWork()

```csharp
public SkillTypeInfo GetOldWork()
```

#### Returns

**Type:** Global.SkillTypeInfo

### GetPanicIcon()

```csharp
public static Sprite GetPanicIcon()
```

#### Returns

**Type:** UnityEngine.Sprite

### GetPersonalityType(int)

```csharp
public static PersonalityType GetPersonalityType(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.PersonalityType

### GetPrudenceStatBySefiraAbility()

```csharp
public int GetPrudenceStatBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetRecentWork()

```csharp
public SkillTypeInfo GetRecentWork()
```

#### Returns

**Type:** Global.SkillTypeInfo

### GetRecentWorkedCreature()

```csharp
public CreatureModel GetRecentWorkedCreature()
```

#### Returns

**Type:** Global.CreatureModel

### GetRecentWorkIcon()

```csharp
public Sprite GetRecentWorkIcon()
```

#### Returns

**Type:** UnityEngine.Sprite

### GetRiskLevel()

```csharp
public override int GetRiskLevel()
```

#### Returns

**Type:** System.Int32

### GetSaveData()

```csharp
public override Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSkillInfos()

```csharp
public AgentModel.SkillInfo[] GetSkillInfos()
```

#### Returns

**Type:** Global.AgentModel.SkillInfo[]

### GetState()

```csharp
public AgentAIState GetState()
```

#### Returns

**Type:** Global.AgentAIState

### GetTemperanceStatBySefiraAbility()

```csharp
public int GetTemperanceStatBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### GetTitle()

```csharp
public string GetTitle()
```

#### Returns

**Type:** System.String

### GetTitle(out string, out string)

```csharp
public string GetTitle(out string pre, out string post)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pre` | `System.String` |  |
| `post` | `System.String` |  |

#### Returns

**Type:** System.String

### GetUnit()

```csharp
public AgentUnit GetUnit()
```

#### Returns

**Type:** Global.AgentUnit

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

### GetWorkIconId(SkillTypeInfo)

```csharp
public static int GetWorkIconId(SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Int32

### GetWorkProbBufBySefiraAbility()

```csharp
public int GetWorkProbBufBySefiraAbility()
```

#### Returns

**Type:** System.Int32

### HasSkill(long)

```csharp
public bool HasSkill(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### HasSkill(SkillTypeInfo)

```csharp
public bool HasSkill(SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Boolean

### HorrorDamage(UnitModel)

```csharp
public void HorrorDamage(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### HorrorDamageByDead(AgentModel)

```csharp
public void HorrorDamageByDead(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### HorrorDamageByPanic(AgentModel)

```csharp
public void HorrorDamageByPanic(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### IconAllocated()

```csharp
public void IconAllocated()
```

### Init()

```csharp
public void Init()
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

### InitSkills()

```csharp
public void InitSkills()
```

### InitSkills(params SkillTypeInfo[])

```csharp
public void InitSkills(params SkillTypeInfo[] skills)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skills` | `Global.SkillTypeInfo[]` |  |

### InitTitle()

```csharp
public void InitTitle()
```

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsCrazy()

```csharp
public override bool IsCrazy()
```

#### Returns

**Type:** System.Boolean

### IsIdle()

```csharp
public bool IsIdle()
```

#### Returns

**Type:** System.Boolean

### IsPanic()

```csharp
public override bool IsPanic()
```

#### Returns

**Type:** System.Boolean

### IsShieldBlock()

```csharp
public bool IsShieldBlock()
```

#### Returns

**Type:** System.Boolean

### IsSuppressing()

```csharp
public bool IsSuppressing()
```

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public override void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

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
public override GameObject MakeCreatureEffectHead(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

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

### MakeRecoverEffect(bool)

```csharp
public void MakeRecoverEffect(bool isPhyiscal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isPhyiscal` | `System.Boolean` |  |

### ManageCreature(CreatureModel, SkillTypeInfo, Sprite)

```csharp
public void ManageCreature(CreatureModel target, SkillTypeInfo skill, Sprite skillSprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |
| `skillSprite` | `UnityEngine.Sprite` |  |

### ManageKitCreature(CreatureModel)

```csharp
public void ManageKitCreature(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### ObserveCreature(CreatureModel, Sprite)

```csharp
public void ObserveCreature(CreatureModel target, Sprite skillSprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |
| `skillSprite` | `UnityEngine.Sprite` |  |

### OnChangeGift()

```csharp
protected override void OnChangeGift()
```

### OnClick()

```csharp
public void OnClick()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnEnterRoom(UseSkill)

```csharp
public void OnEnterRoom(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnNotice(string, params object[])

```csharp
public override void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnReleaseArmor()

```csharp
protected override void OnReleaseArmor()
```

### OnReleaseKitCreature()

```csharp
protected override void OnReleaseKitCreature()
```

### OnReleaseWeapon()

```csharp
protected override void OnReleaseWeapon()
```

### OnResurrect()

```csharp
public override void OnResurrect()
```

### OnSetArmor()

```csharp
protected override void OnSetArmor()
```

### OnSetKitCreature()

```csharp
protected override void OnSetKitCreature()
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

### OnStageStart()

```csharp
public override void OnStageStart()
```

### Panic()

```csharp
public override void Panic()
```

### PanicByCreature(CreatureModel, SkillTypeInfo)

```csharp
public void PanicByCreature(CreatureModel creature, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

### PanicReadyComplete()

```csharp
public override void PanicReadyComplete()
```

### PanicSuppressed()

```csharp
public void PanicSuppressed()
```

### PrepareWeapon()

```csharp
public override void PrepareWeapon()
```

### ProcessAction()

```csharp
public override void ProcessAction()
```

### PursueAgent(UnitModel)

```csharp
public void PursueAgent(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### PursueUnconAgent(UnitModel)

```csharp
public override void PursueUnconAgent(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecentlyAttackedCreature(CreatureModel)

```csharp
public override void RecentlyAttackedCreature(CreatureModel creatureModel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureModel` | `Global.CreatureModel` |  |

### RecoverHP(float)

```csharp
public override void RecoverHP(float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### RecoverMental(float)

```csharp
public override void RecoverMental(float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### RemoveSkill(long)

```csharp
public void RemoveSkill(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### RemoveSkill(SkillTypeInfo)

```csharp
public void RemoveSkill(SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |

### RemoveSkillAll()

```csharp
public void RemoveSkillAll()
```

### ResetAnimator()

```csharp
public override void ResetAnimator()
```

### ResetWaitingPassage()

```csharp
public void ResetWaitingPassage()
```

### ReturnCancelKitCreature()

```csharp
public void ReturnCancelKitCreature()
```

### ReturnCreature(CreatureModel)

```csharp
public void ReturnCreature(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### ReturnKitCreature()

```csharp
public void ReturnKitCreature()
```

### SetCurrentSefira(string)

```csharp
public void SetCurrentSefira(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### SetPortraitSprite(AgentModel, Image, Image)

```csharp
public static void SetPortraitSprite(AgentModel target, Image face, Image hair)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |
| `face` | `UnityEngine.UI.Image` |  |
| `hair` | `UnityEngine.UI.Image` |  |

### SetSprite()

```csharp
public void SetSprite()
```

### SetSuppressCommandCheckEvent(CheckCommandState)

```csharp
public void SetSuppressCommandCheckEvent(AgentModel.CheckCommandState check)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `check` | `Global.AgentModel.CheckCommandState` |  |

### SetToAce()

```csharp
public void SetToAce()
```

### SetUncontrollableAction(UncontrollableAction)

```csharp
public override void SetUncontrollableAction(UncontrollableAction uncon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uncon` | `Global.UncontrollableAction` |  |

### SetUnit(AgentUnit)

```csharp
public void SetUnit(AgentUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentUnit` |  |

### SetWaitingPassage(PassageObjectModel)

```csharp
public void SetWaitingPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### SetWorkCommandCheckEvnet(CheckCommandState)

```csharp
public void SetWorkCommandCheckEvnet(AgentModel.CheckCommandState check)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `check` | `Global.AgentModel.CheckCommandState` |  |

### ShowCreatureActionSpeech(long, string)

```csharp
public override void ShowCreatureActionSpeech(long creatureId, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureId` | `System.Int64` |  |
| `key` | `System.String` |  |

### StatLevel(RwbpType)

```csharp
public int StatLevel(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Int32

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

### Suppress(UnitModel, bool)

```csharp
public void Suppress(UnitModel target, bool isAuto = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `isAuto` | `System.Boolean` |  |

### SuppressStandingObject(StandingItemModel)

```csharp
public void SuppressStandingObject(StandingItemModel standing)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### UnderAttack(UnitModel)

```csharp
public override void UnderAttack(UnitModel attacker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |

### UpdatePrefixTitle_reset(int)

```csharp
public void UpdatePrefixTitle_reset(int oldLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldLevel` | `System.Int32` |  |

### UpdatePrimaryStat()

```csharp
public WorkerPrimaryStatBonus UpdatePrimaryStat()
```

#### Returns

**Type:** Global.WorkerPrimaryStatBonus

### UpdateSuffixTitle_reset(int)

```csharp
public void UpdateSuffixTitle_reset(int oldLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldLevel` | `System.Int32` |  |

### UpdateTitle(int)

```csharp
public void UpdateTitle(int oldLevel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldLevel` | `System.Int32` |  |

### UpdateWeaponLevel()

```csharp
public void UpdateWeaponLevel()
```

### WorkAnimPlayed()

```csharp
public void WorkAnimPlayed()
```

### WorkEndReaction()

```csharp
public void WorkEndReaction()
```
