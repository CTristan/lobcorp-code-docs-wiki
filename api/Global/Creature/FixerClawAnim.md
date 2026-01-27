---
uid: Global.FixerClawAnim
canonical_path: /api/Global/Creature/FixerClawAnim
---

# Class FixerClawAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerClawAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [The Claw](/api/Global/Misc/FixerClaw).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → FixerClawAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [FixedUpdate()](/api/Global/Script/AnimScript#fixedupdate), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FixerClawAnim()

```csharp
public FixerClawAnim()
```

## Fields

### _module

```csharp
private SpineOptimizerModule _module
```
#INC


#### Field Value

**Type:** Global.SpineOptimizerModule

### claws

```csharp
public GameObject[] claws
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### loopSounds

```csharp
private Dictionary<string, SoundEffectPlayer> loopSounds
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SoundEffectPlayer}

### orangeSparks

```csharp
public ParticleSystem[] orangeSparks
```
#INC


#### Field Value

**Type:** UnityEngine.ParticleSystem[]

### script

```csharp
private FixerClaw script
```
#INC


#### Field Value

**Type:** Global.FixerClaw

### strongSparks

```csharp
public ParticleSystem[] strongSparks
```
#INC


#### Field Value

**Type:** UnityEngine.ParticleSystem[]

### ultimateTrails

```csharp
public GameObject[] ultimateTrails
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

## Methods

### AttackCalled(int)

```csharp
public override void AttackCalled(int i)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public override void AttackDamageTimeCalled()
```
#INC


### AttackEnd()

```csharp
private void AttackEnd()
```
#INC


### BlueAttackEnd()

```csharp
private void BlueAttackEnd()
```
#INC


### BlueAttackStart()

```csharp
private void BlueAttackStart()
```
#INC


### GetSkillType()

```csharp
public FixerClaw.Capsule GetSkillType()
```
#INC


#### Returns

**Type:** Global.FixerClaw.Capsule

### GetSoundSrc(string)

```csharp
private string GetSoundSrc(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GroggyEnd()

```csharp
private void GroggyEnd()
```
#INC


### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAttacking()

```csharp
public bool IsAttacking()
```
#INC


#### Returns

**Type:** System.Boolean

### IsInSkill()

```csharp
public bool IsInSkill()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeNoise(float)

```csharp
public SoundEffectPlayer MakeNoise(float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, float)

```csharp
public SoundEffectPlayer MakeSound(string src, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, Vector3, float)

```csharp
public SoundEffectPlayer MakeSound(string src, Vector3 position, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `position` | `UnityEngine.Vector3` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string, float)

```csharp
public SoundEffectPlayer MakeSoundLoop(string src, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string, Transform, float)

```csharp
public SoundEffectPlayer MakeSoundLoop(string src, Transform transform, float vol = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `transform` | `UnityEngine.Transform` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnAttackLast()

```csharp
public void OnAttackLast()
```
#INC


### OnAttackNext()

```csharp
public void OnAttackNext()
```
#INC


### OnAttackStart(int)

```csharp
public void OnAttackStart(int atkType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atkType` | `System.Int32` |  |

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnGroggyStart()

```csharp
public void OnGroggyStart()
```
#INC


### OnGroggyTimerEnd()

```csharp
public void OnGroggyTimerEnd()
```
#INC


### OnMove()

```csharp
public void OnMove()
```
#INC


### OnSkillStart(Capsule)

```csharp
public void OnSkillStart(FixerClaw.Capsule capsule)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `capsule` | `Global.FixerClaw.Capsule` |  |

### OnStop()

```csharp
public void OnStop()
```
#INC


### OrangeRunEnd()

```csharp
private void OrangeRunEnd()
```
#INC


### OrangeRunStart()

```csharp
private void OrangeRunStart()
```
#INC


### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```
#INC


### RemoveLoopSound()

```csharp
private void RemoveLoopSound()
```
#INC


### RemoveLoopSound(string)

```csharp
private void RemoveLoopSound(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### SetOrangeSparks(bool)

```csharp
private void SetOrangeSparks(bool isActive)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isActive` | `System.Boolean` |  |

### SetScript(FixerClaw)

```csharp
public void SetScript(FixerClaw script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FixerClaw` |  |

### SetStrongEffect(bool)

```csharp
private void SetStrongEffect(bool isActive)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isActive` | `System.Boolean` |  |

### SetUltimateTrail(bool)

```csharp
private void SetUltimateTrail(bool isActive)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isActive` | `System.Boolean` |  |

### SkillEnd()

```csharp
private void SkillEnd()
```
#INC


### StartHealing()

```csharp
private void StartHealing()
```
#INC


### StrongAttack(bool)

```csharp
private void StrongAttack(bool isFirst)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isFirst` | `System.Boolean` |  |

### UltimateAttackEnd()

```csharp
private void UltimateAttackEnd()
```
#INC


### UltimateAttackStart()

```csharp
private void UltimateAttackStart()
```
#INC


### UltimateSkillEnd()

```csharp
private void UltimateSkillEnd()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

