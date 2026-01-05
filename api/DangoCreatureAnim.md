# Class DangoCreatureAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DangoCreatureAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → DangoCreatureAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [OnCalled()](/api/CreatureAnimEventCalled#oncalled), [OnCalled(int)](/api/CreatureAnimEventCalled#oncalled-int), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DangoCreatureAnim()

```csharp
public DangoCreatureAnim()
```

## Fields

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

#### Field Value

**Type:** System.String

### LeftPivot

```csharp
public Transform LeftPivot
```

#### Field Value

**Type:** UnityEngine.Transform

### Level1Pivot

```csharp
public Transform Level1Pivot
```

#### Field Value

**Type:** UnityEngine.Transform

### Level2Pivot

```csharp
public Transform Level2Pivot
```

#### Field Value

**Type:** UnityEngine.Transform

### Level3Pivot

```csharp
public Transform Level3Pivot
```

#### Field Value

**Type:** UnityEngine.Transform

### PivotChangeTime

```csharp
public const float PivotChangeTime = 1
```

#### Field Value

**Type:** System.Single

### RightPivot

```csharp
public Transform RightPivot
```

#### Field Value

**Type:** UnityEngine.Transform

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

#### Field Value

**Type:** UnityEngine.GameObject

### zeroFix

```csharp
public const float zeroFix = 0.5
```

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

### DamageInvoke()

```csharp
public void DamageInvoke()
```

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```

### GetLeft()

```csharp
public Transform GetLeft()
```

#### Returns

**Type:** UnityEngine.Transform

### GetRight()

```csharp
public Transform GetRight()
```

#### Returns

**Type:** UnityEngine.Transform

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```

#### Returns

**Type:** System.Boolean

### IsAttacking()

```csharp
public bool IsAttacking()
```

#### Returns

**Type:** System.Boolean

### MakeGutEffect()

```csharp
public void MakeGutEffect()
```

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### ResetAnim()

```csharp
public void ResetAnim()
```

### ResetPivot()

```csharp
public void ResetPivot()
```

### SetLevel(string, int)

```csharp
public void SetLevel(string paramName, int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `paramName` | `System.String` |  |
| `level` | `System.Int32` |  |

### SetScript(DangoCreature)

```csharp
public void SetScript(DangoCreature dangoCreature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dangoCreature` | `Global.DangoCreature` |  |

### StartAttack(int)

```csharp
public void StartAttack(int type = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |
