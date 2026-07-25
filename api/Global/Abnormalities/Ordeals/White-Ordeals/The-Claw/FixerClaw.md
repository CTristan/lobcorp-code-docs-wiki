---
title: FixerClaw
description: 
published: true
date: 2026-07-25T20:02:50.441Z
tags: 
editor: markdown
dateCreated: 2026-07-08T15:20:47.970Z
---

# Class FixerClaw
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerClaw : FixerCreature
```
> This section may have incomplete or incorrect information.
{.is-warning}


The Claw.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Ordeals/White-Ordeals/FixerCreature) → FixerClaw

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


#### Field Value
**Type:** Global.FixerClawAnim

### _atkDmgMax
```csharp
private const int _atkDmgMax = 25
```


#### Field Value
**Type:** System.Int32

### _atkDmgMin
```csharp
private const int _atkDmgMin = 15
```


#### Field Value
**Type:** System.Int32

### _atkDmgRange
```csharp
private const float _atkDmgRange = 3.5
```


#### Field Value
**Type:** System.Single

### _atkDmgType
```csharp
private const RwbpType _atkDmgType = R
```


#### Field Value
**Type:** Global.RwbpType

### _atkRange
```csharp
private const float _atkRange = 3
```


#### Field Value
**Type:** System.Single

### _atkSpecialProb
```csharp
private const float _atkSpecialProb = 0.4
```


#### Field Value
**Type:** System.Single

### _blueAtkMax
```csharp
private const int _blueAtkMax = 8
```


#### Field Value
**Type:** System.Int32

### _blueAttackTimeMax
```csharp
private const float _blueAttackTimeMax = 0.5
```


#### Field Value
**Type:** System.Single

### _blueAttackTimeMin
```csharp
private const float _blueAttackTimeMin = 0.45
```


#### Field Value
**Type:** System.Single

### _blueCapsuleProb
```csharp
private const float _blueCapsuleProb = 0.4
```


#### Field Value
**Type:** System.Single

### _blueDmgMax
```csharp
private const int _blueDmgMax = 35
```


#### Field Value
**Type:** System.Int32

### _blueDmgMin
```csharp
private const int _blueDmgMin = 25
```


#### Field Value
**Type:** System.Int32

### _blueDmgType
```csharp
private const RwbpType _blueDmgType = B
```


#### Field Value
**Type:** Global.RwbpType

### _cancelNeededDmg
```csharp
private const float _cancelNeededDmg = 200
```


#### Field Value
**Type:** System.Single

### _capsuleCoolTimeMax
```csharp
private const float _capsuleCoolTimeMax = 45
```


#### Field Value
**Type:** System.Single

### _capsuleCoolTimeMin
```csharp
private const float _capsuleCoolTimeMin = 40
```


#### Field Value
**Type:** System.Single

### _capsuleInitCoolTimeMax
```csharp
private const float _capsuleInitCoolTimeMax = 30
```


#### Field Value
**Type:** System.Single

### _capsuleInitCoolTimeMin
```csharp
private const float _capsuleInitCoolTimeMin = 30
```


#### Field Value
**Type:** System.Single

### _colliderSrc
```csharp
private const string _colliderSrc = "Effect/Creature/FixerClaw/FixerClawUltimateCollider"
```


#### Field Value
**Type:** System.String

### _greenCapsuleNeededDmg
```csharp
private const float _greenCapsuleNeededDmg = 120
```


#### Field Value
**Type:** System.Single

### _groggyTimeMax
```csharp
private const float _groggyTimeMax = 12
```


#### Field Value
**Type:** System.Single

### _groggyTimeMin
```csharp
private const float _groggyTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _healEffectSrc
```csharp
private const string _healEffectSrc = "Effect/RecoverHP"
```


#### Field Value
**Type:** System.String

### _healTimeMax
```csharp
private const float _healTimeMax = 10
```


#### Field Value
**Type:** System.Single

### _healTimeMin
```csharp
private const float _healTimeMin = 8
```


#### Field Value
**Type:** System.Single

### _healValueMax
```csharp
private const float _healValueMax = 150
```


#### Field Value
**Type:** System.Single

### _healValueMin
```csharp
private const float _healValueMin = 150
```


#### Field Value
**Type:** System.Single

### _motionDelayMax
```csharp
private const float _motionDelayMax = 1
```


#### Field Value
**Type:** System.Single

### _motionDelayMin
```csharp
private const float _motionDelayMin = 0.5
```


#### Field Value
**Type:** System.Single

### _movementScale_Orange
```csharp
private const float _movementScale_Orange = 25
```


#### Field Value
**Type:** System.Single

### _orangeDmgMax
```csharp
private const int _orangeDmgMax = 100
```


#### Field Value
**Type:** System.Int32

### _orangeDmgMin
```csharp
private const int _orangeDmgMin = 100
```


#### Field Value
**Type:** System.Int32

### _orangeDmgRange
```csharp
private const float _orangeDmgRange = 1.5
```


#### Field Value
**Type:** System.Single

### _orangeDmgType
```csharp
private const RwbpType _orangeDmgType = R
```


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


#### Field Value
**Type:** System.Single

### _strFirstDmgMax
```csharp
private const int _strFirstDmgMax = 40
```


#### Field Value
**Type:** System.Int32

### _strFirstDmgMin
```csharp
private const int _strFirstDmgMin = 25
```


#### Field Value
**Type:** System.Int32

### _strFirstDmgType
```csharp
private const RwbpType _strFirstDmgType = R
```


#### Field Value
**Type:** Global.RwbpType

### _strongBloodEffectSrc
```csharp
private const string _strongBloodEffectSrc = "Effect/Creature/FixerClaw/FixerClawStrongBlood"
```


#### Field Value
**Type:** System.String

### _strSecondDmgMax
```csharp
private const int _strSecondDmgMax = 40
```


#### Field Value
**Type:** System.Int32

### _strSecondDmgMin
```csharp
private const int _strSecondDmgMin = 25
```


#### Field Value
**Type:** System.Int32

### _strSecondDmgType
```csharp
private const RwbpType _strSecondDmgType = R
```


#### Field Value
**Type:** Global.RwbpType

### _ultiAtkMax
```csharp
private const int _ultiAtkMax = 6
```


#### Field Value
**Type:** System.Int32

### _ultiAttackTimeMax
```csharp
private const float _ultiAttackTimeMax = 0.5
```


#### Field Value
**Type:** System.Single

### _ultiAttackTimeMin
```csharp
private const float _ultiAttackTimeMin = 0.45
```


#### Field Value
**Type:** System.Single

### _ultiCapsuleCoolTimeMax
```csharp
private const float _ultiCapsuleCoolTimeMax = 85
```


#### Field Value
**Type:** System.Single

### _ultiCapsuleCoolTimeMin
```csharp
private const float _ultiCapsuleCoolTimeMin = 60
```


#### Field Value
**Type:** System.Single

### _ultiCastingTimeMax
```csharp
private const float _ultiCastingTimeMax = 9
```


#### Field Value
**Type:** System.Single

### _ultiCastingTimeMin
```csharp
private const float _ultiCastingTimeMin = 6
```


#### Field Value
**Type:** System.Single

### _ultiCondition_Hp
```csharp
private const float _ultiCondition_Hp = 0.25
```


#### Field Value
**Type:** System.Single

### _ultiDmgMax
```csharp
private const int _ultiDmgMax = 85
```


#### Field Value
**Type:** System.Int32

### _ultiDmgMin
```csharp
private const int _ultiDmgMin = 60
```


#### Field Value
**Type:** System.Int32

### _ultiDmgType
```csharp
private const RwbpType _ultiDmgType = P
```


#### Field Value
**Type:** Global.RwbpType

### _ultiMoveDmgMax
```csharp
private const int _ultiMoveDmgMax = 65
```


#### Field Value
**Type:** System.Int32

### _ultiMoveDmgMin
```csharp
private const int _ultiMoveDmgMin = 60
```


#### Field Value
**Type:** System.Int32

### _ultiMoveDmgType
```csharp
private const RwbpType _ultiMoveDmgType = P
```


#### Field Value
**Type:** Global.RwbpType

### accumulatedDmg_green
```csharp
private float accumulatedDmg_green
```


#### Field Value
**Type:** System.Single

### accumulatedDmg_groggy
```csharp
private float accumulatedDmg_groggy
```


#### Field Value
**Type:** System.Single

### blueAttackTimer
```csharp
private Timer blueAttackTimer
```


#### Field Value
**Type:** Global.Timer

### capsuleCoolTimer
```csharp
private Timer capsuleCoolTimer
```


#### Field Value
**Type:** Global.Timer

### damagedUnits
```csharp
private List<UnitModel> damagedUnits
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### groggyTimer
```csharp
private Timer groggyTimer
```


#### Field Value
**Type:** Global.Timer

### healTimer
```csharp
private Timer healTimer
```


#### Field Value
**Type:** Global.Timer

### motionDelayTimer
```csharp
private Timer motionDelayTimer
```


#### Field Value
**Type:** Global.Timer

### moveTarget
```csharp
private UnitModel moveTarget
```


#### Field Value
**Type:** Global.UnitModel

### orangeTargetNode
```csharp
private MapNode orangeTargetNode
```


#### Field Value
**Type:** Global.MapNode

### skillTargets
```csharp
private List<UnitModel> skillTargets
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### speedUp
```csharp
private bool speedUp
```


#### Field Value
**Type:** System.Boolean

### ultiAttackTimer
```csharp
private Timer ultiAttackTimer
```


#### Field Value
**Type:** Global.Timer

### ultiCapsuleCoolTimer
```csharp
private Timer ultiCapsuleCoolTimer
```


#### Field Value
**Type:** Global.Timer

### ultiCastingTimer
```csharp
private Timer ultiCastingTimer
```


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


### AttackNext()
```csharp
private void AttackNext()
```


### AttackStart()
```csharp
private void AttackStart()
```


### BlueAttackNext()
```csharp
private void BlueAttackNext()
```


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

### CheckPassage(PassageObjectModel)
```csharp
private bool CheckPassage(PassageObjectModel passage)
```


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


#### Returns
**Type:** System.Boolean

### ClearSkillTarget(UnitModel)
```csharp
private void ClearSkillTarget(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ClearSkillTargets()
```csharp
private void ClearSkillTargets()
```


### GetAvailableTargets()
```csharp
private List<UnitModel> GetAvailableTargets()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetHorizontalPassages()
```csharp
private List<PassageObjectModel> GetHorizontalPassages()
```


#### Returns
**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetNextTarget()
```csharp
private UnitModel GetNextTarget()
```


#### Returns
**Type:** Global.UnitModel

### GetOrangeTargetNode()
```csharp
private MapNode GetOrangeTargetNode()
```


#### Returns
**Type:** Global.MapNode

### GetSidePassages(PassageObjectModel)
```csharp
private List<PassageObjectModel> GetSidePassages(PassageObjectModel passage)
```


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


#### Returns
**Type:** Global.MapNode

### GetTargetNodes()
```csharp
private List<MapNode> GetTargetNodes()
```


#### Returns
**Type:** System.Collections.Generic.List{MapNode}

### GiveDamage(UnitModel, DamageInfo)
```csharp
private void GiveDamage(UnitModel target, DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### GroggyTimerEnd()
```csharp
private void GroggyTimerEnd()
```


### HasEscapeUI()
```csharp
public override bool HasEscapeUI()
```


#### Returns
**Type:** System.Boolean

### Heal()
```csharp
private void Heal()
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

### IsInSkill()
```csharp
private bool IsInSkill()
```


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

### MakeClawEffects(string, bool)
```csharp
private void MakeClawEffects(string src, bool setParent = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `setParent` | `System.Boolean` |  |

### MakeEffect(GameObject, string, bool)
```csharp
private GameObject MakeEffect(GameObject position, string src, bool setParent = true)
```


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


### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnAttackDamageTimeCalled()
```csharp
public void OnAttackDamageTimeCalled()
```


### OnAttackEnd()
```csharp
public void OnAttackEnd()
```


### OnBlueAttackEnd()
```csharp
public void OnBlueAttackEnd()
```


### OnBlueAttackStart()
```csharp
public void OnBlueAttackStart()
```


### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnFixedUpdate_Capsule_All()
```csharp
private void OnFixedUpdate_Capsule_All()
```


### OnFixedUpdate_Default()
```csharp
private void OnFixedUpdate_Default()
```


### OnFixedUpdate_Groggy()
```csharp
private void OnFixedUpdate_Groggy()
```


### OnFixedUpdate_Skill_All()
```csharp
private void OnFixedUpdate_Skill_All()
```


### OnFixedUpdate_Skill_Blue()
```csharp
private void OnFixedUpdate_Skill_Blue()
```


### OnFixedUpdate_Skill_Green()
```csharp
private void OnFixedUpdate_Skill_Green()
```


### OnFixedUpdate_Skill_Orange()
```csharp
private void OnFixedUpdate_Skill_Orange()
```


### OnGroggyEnd()
```csharp
public void OnGroggyEnd()
```


### OnOrangeArrive()
```csharp
public void OnOrangeArrive()
```


### OnOrangeRunStart()
```csharp
public void OnOrangeRunStart()
```


### OnSkillEnd()
```csharp
public void OnSkillEnd()
```


### OnStartHealing()
```csharp
public void OnStartHealing()
```


### OnStrongAttack(bool)
```csharp
public void OnStrongAttack(bool isFirst)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isFirst` | `System.Boolean` |  |

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

### OnTakeDamage_Capsule(float)
```csharp
private void OnTakeDamage_Capsule(float value)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### OnUltimateAttackEnd()
```csharp
public void OnUltimateAttackEnd()
```


### OnUltimateAttackStart()
```csharp
public void OnUltimateAttackStart()
```


### OnUltimateCollide(UnitModel)
```csharp
public bool OnUltimateCollide(UnitModel target)
```


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


### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### PrepareAttack(UnitModel)
```csharp
private void PrepareAttack(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### ReadPassage(PassageObjectModel, ref List\<PassageObjectModel>)
```csharp
private void ReadPassage(PassageObjectModel passage, ref List<PassageObjectModel> targets)
```


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


### SpeedUp()
```csharp
private void SpeedUp()
```


### StartGroggy()
```csharp
private void StartGroggy()
```


### StartHeal()
```csharp
private void StartHeal()
```


### StopMovement()
```csharp
private void StopMovement()
```


### TeleportToNode()
```csharp
private void TeleportToNode()
```


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
Indicates if The Claw can be teleported by the Rabbit Protocol portals.

If currently using the orange skill (Serum R), terminates its movement here and returns false. True otherwise.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` | The node of the Rabbit Protocol portal. |

#### Returns
**Type:** System.Boolean

### UltiAttackNext()
```csharp
private void UltiAttackNext()
```


## Inherited Members
[_ordealScript](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnStageStart()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






