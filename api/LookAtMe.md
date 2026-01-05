# Class LookAtMe

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LookAtMe : CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/CreatureBase) → LookAtMe

## Inherited Members
[isolateSpriteSrc](/api/CreatureBase#isolatespritesrc), [model](/api/CreatureBase#model), [skill](/api/CreatureBase#skill), [kitEvent](/api/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/CreatureBase#isworkallocated), [damage](/api/CreatureBase#damage), [OnReleaseSpecialTip](/api/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/CreatureBase#specialskilltipparamlist), [SetModel(CreatureModel)](/api/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/CreatureBase#oninit), [OnStageStart()](/api/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/CreatureBase#onfixedupdate-creaturemodel), [OnSkillFailWorkTick(UseSkill)](/api/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/CreatureBase#getdamagemultiplierinwork-useskill), [OnEnterRoom(UseSkill)](/api/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/CreatureBase#getspecialskill), [GetDebugText()](/api/CreatureBase#getdebugtext), [OnTimerEnd()](/api/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/CreatureBase#onsuppressed), [OnStageRelease()](/api/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/CreatureBase#isattacktargetable), [GetRealTargets()](/api/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/CreatureBase#loadscriptdata), [SaveScriptData()](/api/CreatureBase#savescriptdata), [ExistSaveData()](/api/CreatureBase#existsavedata), [RemoveSaveData()](/api/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/CreatureBase#onviewdestroy), [IsWorkable()](/api/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/CreatureBase#hasescapeui), [HasRoomCounter()](/api/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/CreatureBase#getradius), [OnElevatorStuck()](/api/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/CreatureBase#getrisklevel), [GetName()](/api/CreatureBase#getname), [UniqueMoveControl()](/api/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/CreatureBase#canenterroom), [AllocatedAgent](/api/CreatureBase#allocatedagent), [skillTriggerCheck](/api/CreatureBase#skilltriggercheck), [Unit](/api/CreatureBase#unit), [GetSaveSrc](/api/CreatureBase#getsavesrc), [movable](/api/CreatureBase#movable), [currentPassage](/api/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### LookAtMe()

```csharp
public LookAtMe()
```

## Fields

### sound_Attack

```csharp
public const string sound_Attack = "Attack"
```

#### Field Value

**Type:** System.String

### sound_Blood

```csharp
public const string sound_Blood = "Blood"
```

#### Field Value

**Type:** System.String

### sound_Dead1

```csharp
public const string sound_Dead1 = "Dead1"
```

#### Field Value

**Type:** System.String

### sound_Dead2

```csharp
public const string sound_Dead2 = "Attack"
```

#### Field Value

**Type:** System.String

### sound_Skill

```csharp
public const string sound_Skill = "Skill"
```

#### Field Value

**Type:** System.String

### sound_SkillEnd

```csharp
public const string sound_SkillEnd = "SkillEnd"
```

#### Field Value

**Type:** System.String

### sound_SkillStart

```csharp
public const string sound_SkillStart = "SkillStart"
```

#### Field Value

**Type:** System.String

### sound_Transform

```csharp
public const string sound_Transform = "Transform"
```

#### Field Value

**Type:** System.String

## Properties

### animScript

```csharp
public LookAtMeAnim animScript { get; }
```

#### Property Value

**Type:** Global.LookAtMeAnim

## Methods

### ActivateQliphothCounter()

```csharp
public override void ActivateQliphothCounter()
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

### Escape()

```csharp
public override void Escape()
```

### GetSoundSrc(string)

```csharp
public string GetSoundSrc(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GiveAttackDamage()

```csharp
public void GiveAttackDamage()
```

### GiveSkillDamage()

```csharp
public void GiveSkillDamage()
```

### IsInCamera()

```csharp
public bool IsInCamera()
```

#### Returns

**Type:** System.Boolean

### MakeSound(string)

```csharp
public override SoundEffectPlayer MakeSound(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string)

```csharp
public override SoundEffectPlayer MakeSoundLoop(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnAfterSuppressed()

```csharp
public override bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnEndAttack()

```csharp
public void OnEndAttack()
```

### OnEndSkill()

```csharp
public void OnEndSkill()
```

### OnFixedUpdateInSkill(UseSkill)

```csharp
public override void OnFixedUpdateInSkill(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### OnStageEnd()

```csharp
public override void OnStageEnd()
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

### SetUtilInspector(CreatureCameraUtil_Inspector, CreatureCameraUtil_Inspector)

```csharp
public void SetUtilInspector(CreatureCameraUtil_Inspector nonEscaped, CreatureCameraUtil_Inspector escaped)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nonEscaped` | `CreatureCameraUtil.CreatureCameraUtil_Inspector` |  |
| `escaped` | `CreatureCameraUtil.CreatureCameraUtil_Inspector` |  |

### TranformWorkProb(float)

```csharp
public override float TranformWorkProb(float originWorkProb)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `originWorkProb` | `System.Single` |  |

#### Returns

**Type:** System.Single

### UniqueEscape()

```csharp
public override void UniqueEscape()
```
