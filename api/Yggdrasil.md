# Class Yggdrasil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Yggdrasil : CreatureBase, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → Yggdrasil

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/CreatureBase#onreleasework-useskill), [OnReturn()](/api/CreatureBase#onreturn), [UniqueEscape()](/api/CreatureBase#uniqueescape), [Escape()](/api/CreatureBase#escape), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnStageEnd()](/api/CreatureBase#onstageend), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/CreatureBase#makesound-string), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [GetName()](/api/CreatureBase#getname), [UniqueMoveControl()](/api/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Yggdrasil()

```csharp
public Yggdrasil()
```

## Properties

### animScript

```csharp
public YggdrasilAnim animScript { get; }
```

#### Property Value

**Type:** Global.YggdrasilAnim

### PassageDmg

```csharp
public static DamageInfo PassageDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
```

### AddBlessedList(WorkerModel)

```csharp
public void AddBlessedList(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### CancelAttract(WorkerModel)

```csharp
public void CancelAttract(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### GetTargets(PassageObjectModel)

```csharp
public UnitModel[] GetTargets(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.UnitModel[]

### HasRoomCounter()

```csharp
public override bool HasRoomCounter()
```

#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public override bool IsWorkable()
```

#### Returns

**Type:** System.Boolean

### MakeChildCreature(UnitModel)

```csharp
public override ChildCreatureModel MakeChildCreature(UnitModel origin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.ChildCreatureModel

### MakeSound(string, Vector3, float)

```csharp
public SoundEffectPlayer MakeSound(string src, Vector3 pos, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string, Transform, float)

```csharp
public SoundEffectPlayer MakeSoundLoop(string src, Transform trans, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `trans` | `UnityEngine.Transform` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnArrive(WorkerModel)

```csharp
public void OnArrive(WorkerModel arrived)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `arrived` | `Global.WorkerModel` |  |

### OnChildSuppressed(ChildCreatureModel)

```csharp
public override void OnChildSuppressed(ChildCreatureModel child)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.ChildCreatureModel` |  |

### OnEnterRoom(UseSkill)

```csharp
public override void OnEnterRoom(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFinishWork(UseSkill)

```csharp
public override void OnFinishWork(UseSkill skill)
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

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnOpenWorkWindow()

```csharp
public override bool OnOpenWorkWindow()
```

#### Returns

**Type:** System.Boolean

### OnSkillGoalComplete(UseSkill)

```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### OnWorkerAnimCalled(int)

```csharp
public void OnWorkerAnimCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### ParamInit()

```csharp
public override void ParamInit()
```

### RemoveBlessedWorker(WorkerModel)

```csharp
public void RemoveBlessedWorker(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
