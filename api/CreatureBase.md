# Class CreatureBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureBase()

```csharp
public CreatureBase()
```

## Fields

### damage

```csharp
public int damage
```

#### Field Value

**Type:** System.Int32

### hasUniqueEscapeLogic

```csharp
public bool hasUniqueEscapeLogic
```

#### Field Value

**Type:** System.Boolean

### isolateSpriteSrc

```csharp
public const string isolateSpriteSrc = "Sprites/CreatureSprite/Isolate/"
```

#### Field Value

**Type:** System.String

### isWorkAllocated

```csharp
public bool isWorkAllocated
```

#### Field Value

**Type:** System.Boolean

### kitEvent

```csharp
public CreatureBase.KitEquipEventListener kitEvent
```

#### Field Value

**Type:** Global.CreatureBase.KitEquipEventListener

### model

```csharp
public CreatureModel model
```

#### Field Value

**Type:** Global.CreatureModel

### OnReleaseSpecialTip

```csharp
public List<string> OnReleaseSpecialTip
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### skill

```csharp
public CreatureSpecialSkill skill
```

#### Field Value

**Type:** Global.CreatureSpecialSkill

### specialSkillTipParamList

```csharp
public List<CreatureBase.SpecialSkillTipParameter> specialSkillTipParamList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureBase.SpecialSkillTipParameter}

## Properties

### AllocatedAgent

```csharp
public AgentModel AllocatedAgent { get; }
```

#### Property Value

**Type:** Global.AgentModel

### currentPassage

```csharp
public virtual PassageObjectModel currentPassage { get; }
```

#### Property Value

**Type:** Global.PassageObjectModel

### GetSaveSrc

```csharp
public string GetSaveSrc { get; }
```

#### Property Value

**Type:** System.String

### movable

```csharp
public virtual MovableObjectNode movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

### skillTriggerCheck

```csharp
public SkillTriggerCheck skillTriggerCheck { get; }
```

#### Property Value

**Type:** Global.SkillTriggerCheck

### Unit

```csharp
public CreatureUnit Unit { get; }
```

#### Property Value

**Type:** Global.CreatureUnit

## Methods

### ActivateQliphothCounter()

```csharp
public virtual void ActivateQliphothCounter()
```

### AddedQliphothCounter()

```csharp
public virtual void AddedQliphothCounter()
```

### AgentAnimCalled(int, WorkerModel)

```csharp
public virtual void AgentAnimCalled(int i, WorkerModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `actor` | `Global.WorkerModel` |  |

### AttackProcess(UnitModel)

```csharp
public virtual bool AttackProcess(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### AutoFeelingDown()

```csharp
public virtual bool AutoFeelingDown()
```

#### Returns

**Type:** System.Boolean

### CanEnterRoom()

```csharp
public virtual bool CanEnterRoom()
```

#### Returns

**Type:** System.Boolean

### CanObservedByAgent(AgentModel)

```csharp
public virtual bool CanObservedByAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### CanTakeDamage(UnitModel, DamageInfo)

```csharp
public virtual bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### DelayAttackMotion(float)

```csharp
public virtual void DelayAttackMotion(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### Escape()

```csharp
public virtual void Escape()
```

### ExistSaveData()

```csharp
public bool ExistSaveData()
```

#### Returns

**Type:** System.Boolean

### ForcelyFail(UseSkill)

```csharp
public virtual bool ForcelyFail(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### ForcelySuccess(UseSkill)

```csharp
public virtual bool ForcelySuccess(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Boolean

### GenPursueCommandAlter(WorkerModel)

```csharp
public virtual bool GenPursueCommandAlter(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### GetDamageFactor(UnitModel, DamageInfo)

```csharp
public virtual float GetDamageFactor(UnitModel target, DamageInfo damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### GetDamageMultiplierInWork(UseSkill)

```csharp
public virtual float GetDamageMultiplierInWork(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.Single

### GetDebugText()

```csharp
public virtual string GetDebugText()
```

#### Returns

**Type:** System.String

### GetKitCreatureProcessTime()

```csharp
public virtual float GetKitCreatureProcessTime()
```

#### Returns

**Type:** System.Single

### GetMaxWorkCountView()

```csharp
public virtual int GetMaxWorkCountView()
```

#### Returns

**Type:** System.Int32

### GetMentalDamage(out float)

```csharp
public virtual bool GetMentalDamage(out float dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetName()

```csharp
public virtual string GetName()
```

#### Returns

**Type:** System.String

### GetPhysicalDamage(out float)

```csharp
public virtual bool GetPhysicalDamage(out float dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetQliphothCounterMax()

```csharp
public virtual int GetQliphothCounterMax()
```

#### Returns

**Type:** System.Int32

### GetRadius()

```csharp
public virtual float GetRadius()
```

#### Returns

**Type:** System.Single

### GetRealTargets()

```csharp
public virtual UnitModel[] GetRealTargets()
```

#### Returns

**Type:** Global.UnitModel[]

### GetRiskLevel()

```csharp
public virtual string GetRiskLevel()
```

#### Returns

**Type:** System.String

### GetSaveData()

```csharp
public virtual Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpecialSkill()

```csharp
public virtual SkillTypeInfo GetSpecialSkill()
```

#### Returns

**Type:** Global.SkillTypeInfo

### HasEscapeUI()

```csharp
public virtual bool HasEscapeUI()
```

#### Returns

**Type:** System.Boolean

### HasRoomCounter()

```csharp
public virtual bool HasRoomCounter()
```

#### Returns

**Type:** System.Boolean

### HasScriptSaveData()

```csharp
public virtual bool HasScriptSaveData()
```

#### Returns

**Type:** System.Boolean

### HasUniqueAttackDealy()

```csharp
public virtual bool HasUniqueAttackDealy()
```

#### Returns

**Type:** System.Boolean

### HasUniqueCollectionCost(string, out string)

```csharp
public virtual bool HasUniqueCollectionCost(string areaName, out string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `areaName` | `System.String` |  |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### HasUniqueCommandAction(int)

```csharp
public virtual bool HasUniqueCommandAction(int workType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### hasUniqueDeadScene()

```csharp
public virtual bool hasUniqueDeadScene()
```

#### Returns

**Type:** System.Boolean

### HasUniqueFaction()

```csharp
public virtual bool HasUniqueFaction()
```

#### Returns

**Type:** System.Boolean

### HasUniqueMaxObservationFinish()

```csharp
public virtual bool HasUniqueMaxObservationFinish()
```

#### Returns

**Type:** System.Boolean

### HasUniqueName()

```csharp
public virtual bool HasUniqueName()
```

#### Returns

**Type:** System.Boolean

### HasUniqueProcessWorkNarration()

```csharp
public virtual bool HasUniqueProcessWorkNarration()
```

#### Returns

**Type:** System.Boolean

### HasUniqueWorkSelect(int)

```csharp
public virtual int HasUniqueWorkSelect(int workId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workId` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### IsActivatedWorkDesc()

```csharp
public virtual bool IsActivatedWorkDesc()
```

#### Returns

**Type:** System.Boolean

### isAttackInWorkProcess()

```csharp
public virtual bool isAttackInWorkProcess()
```

#### Returns

**Type:** System.Boolean

### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsAutoSuppressable()

```csharp
public virtual bool IsAutoSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsIndirectSuppressable()

```csharp
public virtual bool IsIndirectSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsSensoredInPassage()

```csharp
public virtual bool IsSensoredInPassage()
```

#### Returns

**Type:** System.Boolean

### IsSuppressable()

```csharp
public virtual bool IsSuppressable()
```

#### Returns

**Type:** System.Boolean

### IsSuppressableByRoom()

```csharp
public virtual bool IsSuppressableByRoom()
```

#### Returns

**Type:** System.Boolean

### IsWorkable()

```csharp
public virtual bool IsWorkable()
```

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public virtual void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadScriptData()

```csharp
public virtual void LoadScriptData()
```

### MakeChildCreature(UnitModel)

```csharp
public virtual ChildCreatureModel MakeChildCreature(UnitModel origin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.ChildCreatureModel

### MakeEffect(IsolateRoom, int)

```csharp
public virtual void MakeEffect(IsolateRoom room, int currentSkillResult)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `room` | `Global.IsolateRoom` |  |
| `currentSkillResult` | `System.Int32` |  |

### MakeEffectAlter(IsolateRoom, int)

```csharp
public void MakeEffectAlter(IsolateRoom room, int result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `room` | `Global.IsolateRoom` |  |
| `result` | `System.Int32` |  |

### MakeEffectAttachedToHead(string)

```csharp
public virtual GameObject MakeEffectAttachedToHead(string effectSrc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effectSrc` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectGlobalPos(string, Vector3)

```csharp
public virtual GameObject MakeEffectGlobalPos(string src, Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffectGlobalPosNonTrans(string, Vector3)

```csharp
public virtual GameObject MakeEffectGlobalPosNonTrans(string src, Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeSound(string)

```csharp
public virtual SoundEffectPlayer MakeSound(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, AudioRolloffMode)

```csharp
public virtual SoundEffectPlayer MakeSound(string src, AudioRolloffMode mode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `mode` | `UnityEngine.AudioRolloffMode` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, float)

```csharp
public virtual SoundEffectPlayer MakeSound(string src, float pitch)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pitch` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string)

```csharp
public virtual SoundEffectPlayer MakeSoundLoop(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundQueue(params string[])

```csharp
public virtual SoundEffectPlayer MakeSoundQueue(params string[] fileName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fileName` | `System.String[]` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakingEffect(string, float)

```csharp
public virtual void MakingEffect(string effect, float effectLength)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |

### MakingEffect(string, float, string, Transform, int)

```csharp
public virtual void MakingEffect(string effect, float effectLength, string sound, Transform parent, int recoil)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |
| `sound` | `System.String` |  |
| `parent` | `UnityEngine.Transform` |  |
| `recoil` | `System.Int32` |  |

### MakingEffect(string, float, string, Vector3, int)

```csharp
public virtual void MakingEffect(string effect, float effectLength, string sound, Vector3 pos, int recoil)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `effect` | `System.String` |  |
| `effectLength` | `System.Single` |  |
| `sound` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `recoil` | `System.Int32` |  |

### ObserveLevelChangeForSpecialSkillTip()

```csharp
public void ObserveLevelChangeForSpecialSkillTip()
```

### OnAfterSuppressed()

```csharp
public virtual bool OnAfterSuppressed()
```

#### Returns

**Type:** System.Boolean

### OnAgentAllocateWork(AgentModel)

```csharp
public virtual void OnAgentAllocateWork(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnAgentAnimatorReseted()

```csharp
public virtual void OnAgentAnimatorReseted()
```

### OnAgentWorkEndAnimationPlayed(UseSkill)

```csharp
public virtual void OnAgentWorkEndAnimationPlayed(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnAllocatedWork(AgentModel)

```csharp
public virtual void OnAllocatedWork(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### OnAttackInWorkProcess(UseSkill)

```csharp
public virtual void OnAttackInWorkProcess(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnBonusWorkProb()

```csharp
public virtual int OnBonusWorkProb()
```

#### Returns

**Type:** System.Int32

### OnChildSuppressed(ChildCreatureModel)

```csharp
public virtual void OnChildSuppressed(ChildCreatureModel child)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.ChildCreatureModel` |  |

### OnElevatorStuck()

```csharp
public virtual void OnElevatorStuck()
```

### OnEnterRoom(UseSkill)

```csharp
public virtual void OnEnterRoom(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFeverTimeOver()

```csharp
public virtual void OnFeverTimeOver()
```

### OnFinishWork(UseSkill)

```csharp
public virtual void OnFinishWork(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdate(CreatureModel)

```csharp
public virtual void OnFixedUpdate(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnFixedUpdateInSkill(UseSkill)

```csharp
public virtual void OnFixedUpdateInSkill(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnForceSpecialSkillTipReveal(string, params object[])

```csharp
public virtual void OnForceSpecialSkillTipReveal(string key, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnGamemanagerInit()

```csharp
public virtual void OnGamemanagerInit()
```

### OnInit()

```csharp
public virtual void OnInit()
```

### OnInitialBuild()

```csharp
public virtual void OnInitialBuild()
```

### OnKillWorker(WorkerModel)

```csharp
public virtual bool OnKillWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### OnLoadCreatureName(ref string)

```csharp
public virtual bool OnLoadCreatureName(ref string nameOut)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nameOut` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### OnObserveLevelChanged()

```csharp
public virtual void OnObserveLevelChanged()
```

### OnOpenCollectionWindow()

```csharp
public virtual bool OnOpenCollectionWindow()
```

#### Returns

**Type:** System.Boolean

### OnOpenCommandWindow(Button[])

```csharp
public virtual void OnOpenCommandWindow(Button[] buttons)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenObserveWindow()

```csharp
public virtual bool OnOpenObserveWindow()
```

#### Returns

**Type:** System.Boolean

### OnOpenWorkWindow()

```csharp
public virtual bool OnOpenWorkWindow()
```

#### Returns

**Type:** System.Boolean

### OnOverlayIsolateObserve()

```csharp
public virtual bool OnOverlayIsolateObserve()
```

#### Returns

**Type:** System.Boolean

### OnOverlayIsolateWork()

```csharp
public virtual bool OnOverlayIsolateWork()
```

#### Returns

**Type:** System.Boolean

### OnReleaseWork(UseSkill)

```csharp
public virtual void OnReleaseWork(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReleaseWorkAllocated()

```csharp
public virtual void OnReleaseWorkAllocated()
```

### OnReturn()

```csharp
public virtual void OnReturn()
```

### OnSelectMaxObservation(int)

```csharp
public virtual void OnSelectMaxObservation(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSkillFailWorkTick(UseSkill)

```csharp
public virtual void OnSkillFailWorkTick(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillGoalComplete(UseSkill)

```csharp
public virtual void OnSkillGoalComplete(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillSuccessWorkTick(UseSkill)

```csharp
public virtual void OnSkillSuccessWorkTick(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnSkillTickUpdate(UseSkill)

```csharp
public virtual void OnSkillTickUpdate(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```

### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```

### OnStageStart()

```csharp
public virtual void OnStageStart()
```

### OnSuperArmorBreak()

```csharp
public virtual void OnSuperArmorBreak()
```

### OnSuppressed()

```csharp
public virtual void OnSuppressed()
```

### OnTakeDamage(UnitModel, DamageInfo, float)

```csharp
public virtual void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
| `value` | `System.Single` |  |

### OnTakePhysicalDamage(UnitModel, float)

```csharp
public virtual void OnTakePhysicalDamage(UnitModel attacker, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### OnTimerEnd()

```csharp
public virtual void OnTimerEnd()
```

### OnViewDestroy()

```csharp
public virtual void OnViewDestroy()
```

### OnViewInit(CreatureUnit)

```csharp
public virtual void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnViewInitPrev(CreatureUnit)

```csharp
public void OnViewInitPrev(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkAllocated(SkillTypeInfo, AgentModel)

```csharp
public virtual void OnWorkAllocated(SkillTypeInfo skill, AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.SkillTypeInfo` |  |
| `agent` | `Global.AgentModel` |  |

### OnWorkClosed(UseSkill, int)

```csharp
public virtual void OnWorkClosed(UseSkill skill, int successCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |
| `successCount` | `System.Int32` |  |

### OnWorkCoolTimeEnd(CreatureFeelingState)

```csharp
public virtual void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### OnWorkerPanic(WorkerModel)

```csharp
public virtual bool OnWorkerPanic(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### OnWorkReleaseSpeicalSkillTipReveal(string)

```csharp
public virtual void OnWorkReleaseSpeicalSkillTipReveal(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### OnWorkReleaseTipUpdate(params object[])

```csharp
public virtual void OnWorkReleaseTipUpdate(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

### OnWorkWindowSkillClicked(long)

```csharp
public virtual void OnWorkWindowSkillClicked(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### ParamInit()

```csharp
public virtual void ParamInit()
```

### PermitCancelCurrentWork()

```csharp
public virtual bool PermitCancelCurrentWork()
```

#### Returns

**Type:** System.Boolean

### Prob(int)

```csharp
public virtual bool Prob(int probability)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `probability` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### ReducedQliphothCounter()

```csharp
public virtual void ReducedQliphothCounter()
```

### RemoveSaveData()

```csharp
public void RemoveSaveData()
```

### ReplaceCommand(CreatureModel)

```csharp
public void ReplaceCommand(CreatureModel replaced)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `replaced` | `Global.CreatureModel` |  |

### ResetQliphothCounter()

```csharp
public virtual void ResetQliphothCounter()
```

### RoomCounterInit()

```csharp
public virtual void RoomCounterInit()
```

### RoomEscapeSpriteOff()

```csharp
public virtual void RoomEscapeSpriteOff()
```

### RoomEscapeSpriteOn()

```csharp
public virtual void RoomEscapeSpriteOn()
```

### RoomSkillSpriteOff()

```csharp
public virtual void RoomSkillSpriteOff()
```

### RoomSkillSpriteOn()

```csharp
public virtual void RoomSkillSpriteOn()
```

### RoomSpriteInit()

```csharp
public virtual void RoomSpriteInit()
```

### RoomStateSpriteOff()

```csharp
public virtual void RoomStateSpriteOff()
```

### RoomStateSpriteOn()

```csharp
public virtual void RoomStateSpriteOn()
```

### SaveScriptData()

```csharp
public virtual void SaveScriptData()
```

### SetCastingSlider(Slider)

```csharp
public virtual bool SetCastingSlider(Slider castingSlider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetHpSlider(Slider)

```csharp
public virtual bool SetHpSlider(Slider slider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### SetModel(CreatureModel)

```csharp
public virtual void SetModel(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SpecialEnergyTick()

```csharp
public virtual float SpecialEnergyTick()
```

#### Returns

**Type:** System.Single

### TranformWorkProb(float)

```csharp
public virtual float TranformWorkProb(float originWorkProb)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `originWorkProb` | `System.Single` |  |

#### Returns

**Type:** System.Single

### TryRabbitTeleport(MapNode)

```csharp
public virtual bool TryRabbitTeleport(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** System.Boolean

### UniqueEscape()

```csharp
public virtual void UniqueEscape()
```

### UniqueMaxObservationFinish(Desc)

```csharp
public virtual bool UniqueMaxObservationFinish(CreatureMaxObserve.Desc desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `Global.CreatureMaxObserve.Desc` |  |

#### Returns

**Type:** System.Boolean

### UniqueMoveControl()

```csharp
public virtual bool UniqueMoveControl()
```

#### Returns

**Type:** System.Boolean

### UniqueProcessWorkNarration(UseSkill)

```csharp
public virtual void UniqueProcessWorkNarration(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### UniqueStunEffect()

```csharp
public virtual bool UniqueStunEffect()
```

#### Returns

**Type:** System.Boolean

### UseDefaultDamageIgnoreMessage(DamageTextEffect)

```csharp
public virtual bool UseDefaultDamageIgnoreMessage(DamageTextEffect damageScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageScript` | `Global.DamageTextEffect` |  |

#### Returns

**Type:** System.Boolean
