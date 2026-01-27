---
uid: Global.ProjectileModel
canonical_path: /api/Global/Model/ProjectileModel
---

# Class ProjectileModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ProjectileModel : UnitModel
```

Parent class for certain projectiles:
- [An Arbiter](/api/Global/Script/BinahCoreScript)'s [wave](/api/Global/Misc/BinahWave) in Binah's core suppression
- [Knight of Despair](/api/Global/Misc/KnightOfDespair)'s swords
- [Laetitia](/api/Global/Misc/LittleWitch)'s heart gift

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → ProjectileModel

## Inherited Members
[stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetUnitName()](/api/Global/Model/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Model/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Model/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Model/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Model/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [PlayAttackAnimation(string)](/api/Global/Model/UnitModel#playattackanimation-string), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamage-unitmodel-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Model/UnitModel#onsuperarmorbreak), [IsAttackTargetable()](/api/Global/Model/UnitModel#isattacktargetable), [IsHostile(UnitModel)](/api/Global/Model/UnitModel#ishostile-unitmodel), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Model/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Model/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Model/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Model/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/UnitModel#setfaction-string), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Model/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [radius](/api/Global/Model/UnitModel#radius), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [defense](/api/Global/Model/UnitModel#defense), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ProjectileModel(UnitModel)

```csharp
public ProjectileModel(UnitModel owner)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |

### ProjectileModel(UnitModel, float)

```csharp
public ProjectileModel(UnitModel owner, float speed)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `speed` | `System.Single` |  |

## Fields

### damaged

```csharp
private List<UnitModel> damaged
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### destMovable

```csharp
private MovableObjectNode destMovable
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### destNode

```csharp
private MapNode destNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### dups

```csharp
private List<ProjectileModel.DuplicateDamage> dups
```

#### Field Value

**Type:** System.Collections.Generic.List{ProjectileModel.DuplicateDamage}

### fixedUpdateCmd

```csharp
private ProjectileModel.FixedUpdateCommand fixedUpdateCmd
```

#### Field Value

**Type:** Global.ProjectileModel.FixedUpdateCommand

### isMoveEnd

```csharp
private bool isMoveEnd
```
#INC


#### Field Value

**Type:** System.Boolean

### moveCompeleteCmd

```csharp
private ProjectileModel.MoveCompeleteCommand moveCompeleteCmd
```

#### Field Value

**Type:** Global.ProjectileModel.MoveCompeleteCommand

### owner

```csharp
public UnitModel owner
```
#INC


#### Field Value

**Type:** Global.UnitModel

### speed

```csharp
private float speed
```
#INC


#### Field Value

**Type:** System.Single

### unit

```csharp
public ProjectileUnit unit
```
#INC


#### Field Value

**Type:** Global.ProjectileUnit

## Properties

### duplicateFreq

```csharp
public float duplicateFreq { get; set; }
```

#### Property Value

**Type:** System.Single

### isDuplicatable

```csharp
public bool isDuplicatable { get; set; }
```

#### Property Value

**Type:** System.Boolean

### range

```csharp
public float range { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### CheckRange(UnitModel)

```csharp
public bool CheckRange(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CommonGenerator()

```csharp
private void CommonGenerator()
```
#INC


### DestroyUnit()

```csharp
public void DestroyUnit()
```
#INC


### GiveDamage(UnitModel, float)

```csharp
public void GiveDamage(UnitModel actor, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### MoveToMovable(MovableObjectNode)

```csharp
public void MoveToMovable(MovableObjectNode movable)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode mapNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnMoveCompelete()

```csharp
public void OnMoveCompelete()
```
#INC


### SetFixedUpdateCommand(FixedUpdateCommand)

```csharp
public void SetFixedUpdateCommand(ProjectileModel.FixedUpdateCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.ProjectileModel.FixedUpdateCommand` |  |

### SetMoveCompeleteCommand(MoveCompeleteCommand)

```csharp
public void SetMoveCompeleteCommand(ProjectileModel.MoveCompeleteCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.ProjectileModel.MoveCompeleteCommand` |  |

### SetPosToOwner(UnitModel)

```csharp
private void SetPosToOwner(UnitModel owner)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |

### SetUnit(ProjectileUnit)

```csharp
public void SetUnit(ProjectileUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.ProjectileUnit` |  |
