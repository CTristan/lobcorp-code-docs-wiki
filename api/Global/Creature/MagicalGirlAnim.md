---
uid: Global.MagicalGirlAnim
canonical_path: /api/Global/Creature/MagicalGirlAnim
---

# Class MagicalGirlAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MagicalGirlAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → MagicalGirlAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [FixedUpdate()](/api/Global/Script/AnimScript#fixedupdate), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MagicalGirlAnim()

```csharp
public MagicalGirlAnim()
```

## Fields

### _bangHeroSrc

```csharp
private const string _bangHeroSrc = "Effect/Creature/MagicalGirl/MagicalGirlGun_Hero"
```

#### Field Value

**Type:** System.String

### _dmgEffectSrc

```csharp
private const string _dmgEffectSrc = "Effect/Creature/MagicalGirl/MagicalGirlDamageEffect"
```

#### Field Value

**Type:** System.String

### _laserHeroSrc_1st

```csharp
private const string _laserHeroSrc_1st = "Effect/Creature/MagicalGirl/MagicalGirlLaser_Hero_1st"
```

#### Field Value

**Type:** System.String

### _laserHeroSrc_2nd

```csharp
private const string _laserHeroSrc_2nd = "Effect/Creature/MagicalGirl/MagicalGirlLaser_Hero_2nd"
```

#### Field Value

**Type:** System.String

### _laserVillainSrc_1st

```csharp
private const string _laserVillainSrc_1st = "Effect/Creature/MagicalGirl/MagicalGirlLaser_Villain_1st"
```

#### Field Value

**Type:** System.String

### _laserVillainSrc_2nd

```csharp
private const string _laserVillainSrc_2nd = "Effect/Creature/MagicalGirl/MagicalGirlLaser_Villain_2nd"
```

#### Field Value

**Type:** System.String

### _laserVillainSrc_3rd

```csharp
private const string _laserVillainSrc_3rd = "Effect/Creature/MagicalGirl/MagicalGirlLaser_Villain_3rd"
```

#### Field Value

**Type:** System.String

### _module1

```csharp
private SpineOptimizerModule _module1
```

#### Field Value

**Type:** Global.SpineOptimizerModule

### _module2

```csharp
private SpineOptimizerModule _module2
```

#### Field Value

**Type:** Global.SpineOptimizerModule

### _normalAttackHeroSrc

```csharp
private const string _normalAttackHeroSrc = "Effect/Creature/MagicalGirl/MagicalGirlNormalAttack_Hero"
```

#### Field Value

**Type:** System.String

### _sound_hero_atk

```csharp
private const string _sound_hero_atk = "hero_atk"
```

#### Field Value

**Type:** System.String

### _sound_hero_delay1

```csharp
private const string _sound_hero_delay1 = "hero_delay1"
```

#### Field Value

**Type:** System.String

### _sound_hero_delay2

```csharp
private const string _sound_hero_delay2 = "hero_delay2"
```

#### Field Value

**Type:** System.String

### _sound_hero_delay_loop1

```csharp
private const string _sound_hero_delay_loop1 = "hero_delay_loop1"
```

#### Field Value

**Type:** System.String

### _sound_hero_delay_loop2

```csharp
private const string _sound_hero_delay_loop2 = "hero_delay_loop2"
```

#### Field Value

**Type:** System.String

### _sound_hero_gun_shot

```csharp
private const string _sound_hero_gun_shot = "hero_gun_shot"
```

#### Field Value

**Type:** System.String

### _sound_hero_gun_start

```csharp
private const string _sound_hero_gun_start = "gun_start"
```

#### Field Value

**Type:** System.String

### _sound_hero_kiss1

```csharp
private const string _sound_hero_kiss1 = "hero_kiss1"
```

#### Field Value

**Type:** System.String

### _sound_hero_kiss2

```csharp
private const string _sound_hero_kiss2 = "hero_kiss2"
```

#### Field Value

**Type:** System.String

### _sound_hero_panic_down

```csharp
private const string _sound_hero_panic_down = "hero_panic_down"
```

#### Field Value

**Type:** System.String

### _sound_hero_panic_loop

```csharp
private const string _sound_hero_panic_loop = "hero_panic_loop"
```

#### Field Value

**Type:** System.String

### _sound_hero_portal

```csharp
private const string _sound_hero_portal = "hero_portal"
```

#### Field Value

**Type:** System.String

### _sound_hero_skill_castend

```csharp
private const string _sound_hero_skill_castend = "hero_skill_castend"
```

#### Field Value

**Type:** System.String

### _sound_hero_skill_loop

```csharp
private const string _sound_hero_skill_loop = "hero_skill_loop"
```

#### Field Value

**Type:** System.String

### _sound_hero_skill_portal1

```csharp
private const string _sound_hero_skill_portal1 = "hero_skill_portal1"
```

#### Field Value

**Type:** System.String

### _sound_hero_skill_portal2

```csharp
private const string _sound_hero_skill_portal2 = "hero_skill_portal2"
```

#### Field Value

**Type:** System.String

### _sound_hero_skill_start

```csharp
private const string _sound_hero_skill_start = "hero_skill_start"
```

#### Field Value

**Type:** System.String

### _sound_hero_smile

```csharp
private const string _sound_hero_smile = "hero_smile"
```

#### Field Value

**Type:** System.String

### _sound_hero_transform1

```csharp
private const string _sound_hero_transform1 = "hero_transform1"
```

#### Field Value

**Type:** System.String

### _sound_hero_transform2

```csharp
private const string _sound_hero_transform2 = "hero_transform2"
```

#### Field Value

**Type:** System.String

### _sound_hero_transform3

```csharp
private const string _sound_hero_transform3 = "hero_transform3"
```

#### Field Value

**Type:** System.String

### _sound_hero_transform4

```csharp
private const string _sound_hero_transform4 = "hero_transform4"
```

#### Field Value

**Type:** System.String

### _sound_teleport

```csharp
private const string _sound_teleport = "teleport"
```

#### Field Value

**Type:** System.String

### _sound_villain_cast1

```csharp
private const string _sound_villain_cast1 = "villain_cast1"
```

#### Field Value

**Type:** System.String

### _sound_villain_cast2

```csharp
private const string _sound_villain_cast2 = "villain_cast2"
```

#### Field Value

**Type:** System.String

### _sound_villain_cast_loop

```csharp
private const string _sound_villain_cast_loop = "villain_cast_loop"
```

#### Field Value

**Type:** System.String

### _sound_villain_cast_start

```csharp
private const string _sound_villain_cast_start = "villain_cast_start"
```

#### Field Value

**Type:** System.String

### _sound_villain_dead1

```csharp
private const string _sound_villain_dead1 = "villain_dead1"
```

#### Field Value

**Type:** System.String

### _sound_villain_dead2

```csharp
private const string _sound_villain_dead2 = "villain_dead2"
```

#### Field Value

**Type:** System.String

### _sound_villain_dead_boom

```csharp
private const string _sound_villain_dead_boom = "villain_dead_boom"
```

#### Field Value

**Type:** System.String

### _sound_villain_dead_end

```csharp
private const string _sound_villain_dead_end = "villain_dead_end"
```

#### Field Value

**Type:** System.String

### _sound_villain_delay

```csharp
private const string _sound_villain_delay = "villain_delay"
```

#### Field Value

**Type:** System.String

### _sound_villain_down

```csharp
private const string _sound_villain_down = "villain_down"
```

#### Field Value

**Type:** System.String

### _teleportSrc

```csharp
private const string _teleportSrc = "Effect/Creature/MagicalGirl/MagicalGirlTeleport"
```

#### Field Value

**Type:** System.String

### circle

```csharp
public GameObject circle
```

#### Field Value

**Type:** UnityEngine.GameObject

### gun

```csharp
public GameObject gun
```

#### Field Value

**Type:** UnityEngine.GameObject

### hero

```csharp
public GameObject hero
```

#### Field Value

**Type:** UnityEngine.GameObject

### laser_Hero

```csharp
private MagicalGirlSkillEffect_Hero laser_Hero
```

#### Field Value

**Type:** Global.MagicalGirlSkillEffect_Hero

### laser_Villain

```csharp
private MagicalGirlLaser_Villain laser_Villain
```

#### Field Value

**Type:** Global.MagicalGirlLaser_Villain

### loopSound

```csharp
private SoundEffectPlayer loopSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### mouth

```csharp
public GameObject mouth
```

#### Field Value

**Type:** UnityEngine.GameObject

### script

```csharp
private MagicalGirl script
```

#### Field Value

**Type:** Global.MagicalGirl

### villain

```csharp
public GameObject villain
```

#### Field Value

**Type:** UnityEngine.GameObject

### weapon

```csharp
public GameObject weapon
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### animator_Hero

```csharp
private Animator animator_Hero { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### animator_Villain

```csharp
private Animator animator_Villain { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### AfterDeadScene()

```csharp
private void AfterDeadScene()
```

### AttackEnd()

```csharp
private void AttackEnd()
```

### Bang()

```csharp
private void Bang()
```

### ChangeDefaultType()

```csharp
public void ChangeDefaultType()
```

### ChuEnd()

```csharp
private void ChuEnd()
```

### ChuStart()

```csharp
public void ChuStart()
```

### CurrentAttackType()

```csharp
public int CurrentAttackType()
```

#### Returns

**Type:** System.Int32

### EndTransformToVillain()

```csharp
private void EndTransformToVillain()
```

### FinishGroggy()

```csharp
public void FinishGroggy()
```

### GetSoundSrc(string)

```csharp
private string GetSoundSrc(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public void Init()
```

### InitAnimator(Animator)

```csharp
private void InitAnimator(Animator anim)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `UnityEngine.Animator` |  |

### IsAttacking()

```csharp
public bool IsAttacking()
```

#### Returns

**Type:** System.Boolean

### IsInGroggy()

```csharp
public bool IsInGroggy()
```

#### Returns

**Type:** System.Boolean

### IsInSkill()

```csharp
public bool IsInSkill()
```

#### Returns

**Type:** System.Boolean

### MakeSound(string)

```csharp
private SoundEffectPlayer MakeSound(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, Vector3)

```csharp
private SoundEffectPlayer MakeSound(string src, Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `position` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string)

```csharp
private SoundEffectPlayer MakeSoundLoop(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### NormalAttack_Hero()

```csharp
public void NormalAttack_Hero()
```

### OnAttackStart(int)

```csharp
public void OnAttackStart(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnBeingAHero()

```csharp
public void OnBeingAHero()
```

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCastingEnd()

```csharp
public void OnCastingEnd()
```

### OnGroggyEnd()

```csharp
private void OnGroggyEnd()
```

### OnGroggyStart()

```csharp
public void OnGroggyStart()
```

### OnMakeDamageEffect(Camp, Vector3)

```csharp
public void OnMakeDamageEffect(MagicalGirl.Camp camp, Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `camp` | `Global.MagicalGirl.Camp` |  |
| `position` | `UnityEngine.Vector3` |  |

### OnMove()

```csharp
public void OnMove()
```

### OnSkillStart(int)

```csharp
public void OnSkillStart(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnStop()

```csharp
public void OnStop()
```

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### RemoveLoopSound()

```csharp
private void RemoveLoopSound()
```

### SetScript(MagicalGirl)

```csharp
public void SetScript(MagicalGirl script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.MagicalGirl` |  |

### ShootingEnd()

```csharp
public void ShootingEnd()
```

### ShootLaser_Hero(int)

```csharp
public void ShootLaser_Hero(int phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `System.Int32` |  |

### ShootLaser_Villain(int)

```csharp
public void ShootLaser_Villain(int phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `System.Int32` |  |

### SkillEnd(int)

```csharp
private void SkillEnd(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### StartHysteric()

```csharp
private void StartHysteric()
```

### TeleportEffect(Camp, Vector3, bool)

```csharp
public void TeleportEffect(MagicalGirl.Camp camp, Vector3 position, bool isAppear)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `camp` | `Global.MagicalGirl.Camp` |  |
| `position` | `UnityEngine.Vector3` |  |
| `isAppear` | `System.Boolean` |  |

### TransformToHero()

```csharp
public void TransformToHero()
```

### TransformToHysteric()

```csharp
public void TransformToHysteric()
```

### TransformToVillain()

```csharp
public void TransformToVillain()
```

### Update()

```csharp
private void Update()
```
