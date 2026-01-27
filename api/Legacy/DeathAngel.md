---
uid: Legacy.DeathAngel
canonical_path: /api/Legacy/DeathAngel
---

# Class DeathAngel

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngel : CreatureBase
```

WhiteNight <3


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Creature/CreatureBase) → DeathAngel

## Inherited Members
[isolateSpriteSrc](/api/Global/Creature/CreatureBase#isolatespritesrc), [model](/api/Global/Creature/CreatureBase#model), [skill](/api/Global/Creature/CreatureBase#skill), [kitEvent](/api/Global/Creature/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Creature/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Creature/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [damage](/api/Global/Creature/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Creature/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Creature/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Creature/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Creature/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Creature/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Creature/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Creature/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Creature/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Creature/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Creature/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Creature/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Creature/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Creature/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Creature/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/Global/Creature/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Creature/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetDebugText()](/api/Global/Creature/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Creature/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Creature/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Creature/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Creature/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Creature/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Creature/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Creature/CreatureBase#autofeelingdown), [MakingEffect(string, float, string, Transform, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Creature/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Creature/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Creature/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Creature/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Creature/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Creature/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Creature/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Creature/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Creature/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Creature/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Creature/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Creature/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Creature/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Creature/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Creature/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Creature/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Creature/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Creature/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Creature/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Creature/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Creature/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Creature/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Creature/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Creature/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Creature/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Creature/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Creature/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Creature/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Creature/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Creature/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Creature/CreatureBase#isattacktargetable), [LoadScriptData()](/api/Global/Creature/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Creature/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Creature/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Creature/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Creature/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Creature/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Creature/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Creature/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Creature/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Creature/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Creature/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Creature/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Creature/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Creature/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Creature/CreatureBase#isworkable), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Creature/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Creature/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Creature/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Creature/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Creature/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Creature/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Creature/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Creature/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Creature/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Creature/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/Global/Creature/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Creature/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Creature/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Creature/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Creature/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Creature/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Creature/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Creature/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Creature/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Creature/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Creature/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Creature/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Creature/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Creature/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Creature/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Creature/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Creature/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Creature/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Creature/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Creature/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Creature/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Creature/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Creature/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Creature/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Creature/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Creature/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Creature/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Creature/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Creature/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Creature/CreatureBase#getrisklevel), [GetName()](/api/Global/Creature/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Creature/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Creature/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Creature/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Creature/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Creature/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Creature/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Creature/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Creature/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Creature/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Creature/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Creature/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Creature/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Creature/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Creature/CreatureBase#skilltriggercheck), [Unit](/api/Global/Creature/CreatureBase#unit), [GetSaveSrc](/api/Global/Creature/CreatureBase#getsavesrc), [movable](/api/Global/Creature/CreatureBase#movable), [currentPassage](/api/Global/Creature/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngel()

```csharp
public DeathAngel()
```

## Fields

### _isEscaped

```csharp
private bool _isEscaped
```

#### Field Value

**Type:** System.Boolean

### _left

```csharp
private MapNode _left
```

#### Field Value

**Type:** Global.MapNode

### _right

```csharp
private MapNode _right
```

#### Field Value

**Type:** Global.MapNode

### _sefiraPassage

```csharp
private PassageObject _sefiraPassage
```

#### Field Value

**Type:** Global.PassageObject

### _skillInterval

```csharp
private int _skillInterval
```

#### Field Value

**Type:** System.Int32

### agentEffect

```csharp
public const string agentEffect = "Effect/Creature/DeathAngel/AgentExplode"
```

#### Field Value

**Type:** System.String

### apostleCount

```csharp
private const int apostleCount = 12
```
#INC


#### Field Value

**Type:** System.Int32

### apostleEffect

```csharp
public const string apostleEffect = "Effect/Creature/DeathAngel/ApostleExplode"
```

#### Field Value

**Type:** System.String

### apostleList

```csharp
public List<DeathAngelApostle> apostleList
```

#### Field Value

**Type:** System.Collections.Generic.List{Legacy.DeathAngelApostle}

### apostles

```csharp
private DeathAngel.Apostle[] apostles
```

#### Field Value

**Type:** Legacy.DeathAngel.Apostle[]

### badState

```csharp
private Sprite badState
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### badworkSound

```csharp
private const string badworkSound = "creature/deathangel/Choir1"
```

#### Field Value

**Type:** System.String

### betrayDead

```csharp
private const string betrayDead = "creature/deathangel/revive0"
```

#### Field Value

**Type:** System.String

### confessEffect

```csharp
public const string confessEffect = "Effect/Creature/DeathAngel/AngelFall"
```

#### Field Value

**Type:** System.String

### confessTimer

```csharp
private Timer confessTimer
```

#### Field Value

**Type:** Global.Timer

### currentEffect

```csharp
private GameObject currentEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### currentExtinct

```csharp
private bool currentExtinct
```

#### Field Value

**Type:** System.Boolean

### currentSkill

```csharp
private UseSkill currentSkill
```

#### Field Value

**Type:** Global.UseSkill

### deadOrAliveProb

```csharp
private const int deadOrAliveProb = 50
```

#### Field Value

**Type:** System.Int32

### deathangelEffect

```csharp
public const string deathangelEffect = "Effect/Creature/DeathAngel/LuciferExplode"
```

#### Field Value

**Type:** System.String

### docAdventCall

```csharp
private bool docAdventCall
```

#### Field Value

**Type:** System.Boolean

### doctor

```csharp
private PlagueDoctor doctor
```

#### Field Value

**Type:** Legacy.PlagueDoctor

### explodeSounds

```csharp
private static string[] explodeSounds
```

#### Field Value

**Type:** System.String[]

### extinctEffect

```csharp
public const string extinctEffect = "Effect/Creature/DeathAngel/AdventLight"
```

#### Field Value

**Type:** System.String

### factionId

```csharp
public const string factionId = "11"
```

#### Field Value

**Type:** System.String

### goodState

```csharp
private Sprite goodState
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### goodworkSound

```csharp
private const string goodworkSound = "creature/onebad_good/oneBad_special_sry"
```

#### Field Value

**Type:** System.String

### isAdvented

```csharp
private bool isAdvented
```

#### Field Value

**Type:** System.Boolean

### isConfess

```csharp
private bool isConfess
```

#### Field Value

**Type:** System.Boolean

### iudasDelay

```csharp
private const float iudasDelay = 5
```

#### Field Value

**Type:** System.Single

### normalState

```csharp
private Sprite normalState
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### observedId

```csharp
private List<int> observedId
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### recoverEffect

```csharp
public const string recoverEffect = "Effect/Creature/DeathAngel/Ray"
```

#### Field Value

**Type:** System.String

### resurrectSound

```csharp
private const string resurrectSound = "creature/deathangel/Lucifer_Advent"
```

#### Field Value

**Type:** System.String

### resurrectTime

```csharp
private const float resurrectTime = 90
```

#### Field Value

**Type:** System.Single

### resurrectTimer

```csharp
private Timer resurrectTimer
```

#### Field Value

**Type:** Global.Timer

### skillIntervalTime

```csharp
private const float skillIntervalTime = 30
```

#### Field Value

**Type:** System.Single

### skillIntervalTimer

```csharp
private Timer skillIntervalTimer
```

#### Field Value

**Type:** Global.Timer

### soundSrc

```csharp
private const string soundSrc = "Sounds/creature/deathangel/Lucifer_Advent1"
```

#### Field Value

**Type:** System.String

### specialSkillId

```csharp
private const long specialSkillId = 100015
```

#### Field Value

**Type:** System.Int64

### teleportTarget

```csharp
private MapNode teleportTarget
```

#### Field Value

**Type:** Global.MapNode

## Properties

### animScript

```csharp
public DeathAngelAnim animScript { get; }
```

#### Property Value

**Type:** Legacy.DeathAngelAnim

### isEscaped

```csharp
private bool isEscaped { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Left

```csharp
public MapNode Left { get; set; }
```

#### Property Value

**Type:** Global.MapNode

### Right

```csharp
public MapNode Right { get; set; }
```

#### Property Value

**Type:** Global.MapNode

### sefiraPassage

```csharp
private PassageObject sefiraPassage { get; }
```

#### Property Value

**Type:** Global.PassageObject

### skillInterval

```csharp
private int skillInterval { get; set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddDeletedPermanetly(AgentModel)

```csharp
public static void AddDeletedPermanetly(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Advent(bool)

```csharp
public void Advent(bool isBet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isBet` | `System.Boolean` |  |

### AfterTeleport()

```csharp
public void AfterTeleport()
```

### AgentAnimCalled(int, WorkerModel)

```csharp
public override void AgentAnimCalled(int i, WorkerModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `actor` | `Global.WorkerModel` |  |

### BlockUI(int)

```csharp
public void BlockUI(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### DeletePermanetly(AgentModel)

```csharp
public static void DeletePermanetly(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### DoctorAdvent()

```csharp
public void DoctorAdvent()
```

### Escape()

```csharp
public override void Escape()
```
#INC


### Extinction(AgentModel)

```csharp
private void Extinction(AgentModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |

### GetApostle(int)

```csharp
public DeathAngelApostle GetApostle(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Legacy.DeathAngelApostle

### GetApostleData(int)

```csharp
public CreatureStaticData.ParameterData GetApostleData(int targetindex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetindex` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetApostleDataRefined(int)

```csharp
public string GetApostleDataRefined(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetApostleObject(int)

```csharp
public DeathAngel.Apostle GetApostleObject(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Legacy.DeathAngel.Apostle

### GetBlockData(int)

```csharp
public CreatureStaticData.ParameterData GetBlockData(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetCurrentNode()

```csharp
public MapNode GetCurrentNode()
```

#### Returns

**Type:** Global.MapNode

### GetCurrentPassage()

```csharp
public PassageObjectModel GetCurrentPassage()
```

#### Returns

**Type:** Global.PassageObjectModel

### GetIudas()

```csharp
public DeathAngel.Apostle GetIudas()
```

#### Returns

**Type:** Legacy.DeathAngel.Apostle

### GetRealTargets()

```csharp
public override UnitModel[] GetRealTargets()
```

#### Returns

**Type:** Global.UnitModel[]

### GetSaveData()

```csharp
public override Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpecialSkill()

```csharp
public override SkillTypeInfo GetSpecialSkill()
```

#### Returns

**Type:** Global.SkillTypeInfo

### HasScriptSaveData()

```csharp
public override bool HasScriptSaveData()
```

#### Returns

**Type:** System.Boolean

### HasUniqueFaction()

```csharp
public override bool HasUniqueFaction()
```

#### Returns

**Type:** System.Boolean

### HasUniqueMaxObservationFinish()

```csharp
public override bool HasUniqueMaxObservationFinish()
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

### OnAdventEventEnd()

```csharp
public void OnAdventEventEnd()
```

### OnConfess()

```csharp
public void OnConfess()
```

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
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

### OnHaltEffect()

```csharp
public void OnHaltEffect()
```

### OnHaltKill()

```csharp
public void OnHaltKill()
```

### OnInit()

```csharp
public override void OnInit()
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

### Recover(AgentModel)

```csharp
private void Recover(AgentModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |

### ResurrectApostles()

```csharp
public void ResurrectApostles()
```

### RoomSpriteInit()

```csharp
public override void RoomSpriteInit()
```
#INC


### SetApostleList(List<DeathAngelApostle>)

```csharp
public void SetApostleList(List<DeathAngelApostle> apostle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `apostle` | `System.Collections.Generic.List{Legacy.DeathAngelApostle}` |  |

### SetPlagueDoctorScript(PlagueDoctor)

```csharp
public void SetPlagueDoctorScript(PlagueDoctor doc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `doc` | `Legacy.PlagueDoctor` |  |

### SkillEffect(AgentModel, bool)

```csharp
public void SkillEffect(AgentModel target, bool extinct)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |
| `extinct` | `System.Boolean` |  |

### SkillExecute(AgentModel)

```csharp
public void SkillExecute(AgentModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### SpecialWorkProcess(UseSkill)

```csharp
private void SpecialWorkProcess(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### Teleport()

```csharp
private void Teleport()
```

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
#INC


### UniqueMaxObservationFinish(Desc)

```csharp
public override bool UniqueMaxObservationFinish(CreatureMaxObserve.Desc desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `Global.CreatureMaxObserve.Desc` |  |

#### Returns

**Type:** System.Boolean
