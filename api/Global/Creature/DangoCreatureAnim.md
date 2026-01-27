---
uid: Global.DangoCreatureAnim
canonical_path: /api/Global/Creature/DangoCreatureAnim
---

# Class DangoCreatureAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DangoCreatureAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [Mountain of Smiling Bodies](/api/Global/IOBserver/DangoCreature).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → DangoCreatureAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [OnCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#oncalled-int), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DangoCreatureAnim()

```csharp
public DangoCreatureAnim()
```

## Fields

### _attackState

```csharp
private bool _attackState
```
#INC


#### Field Value

**Type:** System.Boolean

### _module

```csharp
private SpineOptimizerModule _module
```
#INC


#### Field Value

**Type:** Global.SpineOptimizerModule

### CurrentPivot

```csharp
private Transform CurrentPivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### eventHandler

```csharp
[Header("EventHandler")]
public DangoCreatureEventHandler eventHandler
```

#### Field Value

**Type:** Global.DangoCreatureEventHandler

### GutEffectPivot

```csharp
[Header("Effect")]
public Transform GutEffectPivot
```

#### Field Value

**Type:** UnityEngine.Transform

### GutEffectSrc

```csharp
public const string GutEffectSrc = "Effect/Creature/DangoCreature/DangoLv3"
```
#INC


#### Field Value

**Type:** System.String

### LeftPivot

```csharp
public Transform LeftPivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### Level1Pivot

```csharp
public Transform Level1Pivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### Level2Pivot

```csharp
public Transform Level2Pivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### Level3Pivot

```csharp
public Transform Level3Pivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### PivotChangeTime

```csharp
public const float PivotChangeTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### PivotChangeTimer

```csharp
private Timer PivotChangeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### RightPivot

```csharp
public Transform RightPivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### script

```csharp
private DangoCreature script
```
#INC


#### Field Value

**Type:** Global.DangoCreature

### Shadow_lv2

```csharp
[Header("Shadow")]
public GameObject Shadow_lv2
```

#### Field Value

**Type:** UnityEngine.GameObject

### Shadow_lv3

```csharp
public GameObject Shadow_lv3
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### StartPivot

```csharp
private Transform StartPivot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### zeroFix

```csharp
public const float zeroFix = 0.5
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### DangoTr

```csharp
public Transform DangoTr { get; }
```

#### Property Value

**Type:** UnityEngine.Transform

## Methods

### AttackEnd()

```csharp
public void AttackEnd()
```
#INC


### DamageInvoke()

```csharp
public void DamageInvoke()
```
#INC


### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC
#code-generated


### GetLeft()

```csharp
public Transform GetLeft()
```
#INC


#### Returns

**Type:** UnityEngine.Transform

### GetRight()

```csharp
public Transform GetRight()
```
#INC


#### Returns

**Type:** UnityEngine.Transform

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

### MakeGutEffect()

```csharp
public void MakeGutEffect()
```
#INC


### PivotChangeUpdate()

```csharp
private void PivotChangeUpdate()
```
#INC


### PivotDataUpdate()

```csharp
private void PivotDataUpdate()
```
#INC


### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```
#INC


### ResetAnim()

```csharp
public void ResetAnim()
```
#INC


### ResetPivot()

```csharp
public void ResetPivot()
```
#INC


### SetLevel(string, int)

```csharp
public void SetLevel(string paramName, int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `paramName` | `System.String` |  |
| `level` | `System.Int32` |  |

### SetScript(DangoCreature)

```csharp
public void SetScript(DangoCreature dangoCreature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dangoCreature` | `Global.DangoCreature` |  |

### StartAttack(int)

```csharp
public void StartAttack(int type = 0)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

### Update()

```csharp
private void Update()
```
#INC

