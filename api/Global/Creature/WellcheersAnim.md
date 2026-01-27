---
uid: Global.WellcheersAnim
canonical_path: /api/Global/Creature/WellcheersAnim
---

# Class WellcheersAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WellcheersAnim : CreatureAnimScript, IAnimatorEventCalled
```

Animation handler for [Opened Can of Wellcheers](/api/Global/Misc/Wellcheers).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → WellcheersAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [Move()](/api/Global/Script/CreatureAnimScript#move), [Stop()](/api/Global/Script/CreatureAnimScript#stop), [StopMoving()](/api/Global/Script/CreatureAnimScript#stopmoving), [HasDeadMotion()](/api/Global/Script/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/Global/Script/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WellcheersAnim()

```csharp
public WellcheersAnim()
```

## Fields

### machine

```csharp
public Animator machine
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### machineCanListRenderer

```csharp
public SpriteRenderer machineCanListRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### machineCanRenderer

```csharp
public SpriteRenderer machineCanRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### machineTitleRenderer

```csharp
public SpriteRenderer machineTitleRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### moveFoward

```csharp
private bool moveFoward
```
#INC


#### Field Value

**Type:** System.Boolean

### moveTime

```csharp
private const float moveTime = 2
```
#INC


#### Field Value

**Type:** System.Single

### moveTimer

```csharp
private Timer moveTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### purple

```csharp
public WellcheersAnim.MachineColorImages purple
```

#### Field Value

**Type:** Global.WellcheersAnim.MachineColorImages

### red

```csharp
public WellcheersAnim.MachineColorImages red
```

#### Field Value

**Type:** Global.WellcheersAnim.MachineColorImages

### shrimp1

```csharp
public Animator shrimp1
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### shrimp1Pos

```csharp
private Vector3 shrimp1Pos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### shrimp2

```csharp
public Animator shrimp2
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### shrimp2Pos

```csharp
private Vector3 shrimp2Pos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### sky

```csharp
public WellcheersAnim.MachineColorImages sky
```

#### Field Value

**Type:** Global.WellcheersAnim.MachineColorImages

## Methods

### AgentReset()

```csharp
public void AgentReset()
```
#INC


### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```
#INC


### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```
#INC


### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### FinishDance()

```csharp
public void FinishDance()
```
#INC


### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC
#code-generated


### MoveShrimp()

```csharp
private void MoveShrimp()
```
#INC


### OnCalled()

```csharp
public void OnCalled()
```
#INC


### OnCalled(int)

```csharp
public void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### SimpleReset()

```csharp
public void SimpleReset()
```
#INC


### SoundMake(string)

```csharp
public void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### Start()

```csharp
private void Start()
```
#INC


### StartDance()

```csharp
public void StartDance()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

