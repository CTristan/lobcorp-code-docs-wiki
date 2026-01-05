# Class DeathAngel

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngel : CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → DeathAngel

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnStageEnd()](/api/CreatureBase#onstageend), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/CreatureBase#makesound-string), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [IsWorkable()](/api/CreatureBase#isworkable), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [HasRoomCounter()](/api/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [GetName()](/api/CreatureBase#getname), [UniqueMoveControl()](/api/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeathAngel()

```csharp
public DeathAngel()
```

## Fields

### agentEffect

```csharp
public const string agentEffect = "Effect/Creature/DeathAngel/AgentExplode"
```

#### Field Value

**Type:** System.String

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

### confessEffect

```csharp
public const string confessEffect = "Effect/Creature/DeathAngel/AngelFall"
```

#### Field Value

**Type:** System.String

### deathangelEffect

```csharp
public const string deathangelEffect = "Effect/Creature/DeathAngel/LuciferExplode"
```

#### Field Value

**Type:** System.String

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

### recoverEffect

```csharp
public const string recoverEffect = "Effect/Creature/DeathAngel/Ray"
```

#### Field Value

**Type:** System.String

## Properties

### animScript

```csharp
public DeathAngelAnim animScript { get; }
```

#### Property Value

**Type:** Legacy.DeathAngelAnim

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

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

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnSuppressed()

```csharp
public override void OnSuppressed()
```

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### ParamInit()

```csharp
public override void ParamInit()
```

### ResurrectApostles()

```csharp
public void ResurrectApostles()
```

### RoomSpriteInit()

```csharp
public override void RoomSpriteInit()
```

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

### UniqueEscape()

```csharp
public override void UniqueEscape()
```

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
