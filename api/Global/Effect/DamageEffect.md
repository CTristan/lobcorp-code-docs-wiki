---
uid: Global.DamageEffect
canonical_path: /api/Global/Effect/DamageEffect
---

# Class DamageEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DamageEffect : EffectInvoker
```

Damage effect (modified) by Yesod's upgrade, displaying damage type and damage.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [EffectInvoker](/api/Global/Effect/EffectInvoker) → DamageEffect

## Inherited Members
[PrefabSrc](/api/Global/Effect/EffectInvoker#prefabsrc), [destroyEvent](/api/Global/Effect/EffectInvoker#destroyevent), [_attached](/api/Global/Effect/EffectInvoker#attached), [_node](/api/Global/Effect/EffectInvoker#node), [Invoker(string, MovableObjectNode, float, bool)](/api/Global/Effect/EffectInvoker#invoker-string-movableobjectnode-float-bool), [Invoker(string, Vector3, float, bool)](/api/Global/Effect/EffectInvoker#invoker-string-vector3-float-bool), [OnDestroy()](/api/Global/Effect/EffectInvoker#ondestroy), [SetMovableSetting(MovableObjectNode)](/api/Global/Effect/EffectInvoker#setmovablesetting-movableobjectnode), [SetDestroyEvent(OnDestroyEvent)](/api/Global/Effect/EffectInvoker#setdestroyevent-ondestroyevent), [Attach()](/api/Global/Effect/EffectInvoker#attach), [Dettach()](/api/Global/Effect/EffectInvoker#dettach), [IsAttached](/api/Global/Effect/EffectInvoker#isattached), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DamageEffect()

```csharp
public DamageEffect()
```

## Fields

### BPos

```csharp
private static Vector2 BPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### DamageContext

```csharp
public Text DamageContext
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DamageCount

```csharp
public Text DamageCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DamageCountOutline

```csharp
public Outline DamageCountOutline
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Outline

### DamageFontTexture

```csharp
public Sprite[] DamageFontTexture
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageIcon

```csharp
public Sprite[] DamageIcon
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageIconOut

```csharp
public Sprite[] DamageIconOut
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageTextImage

```csharp
public Sprite[] DamageTextImage
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### DefaultPos

```csharp
private static Vector2 DefaultPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### DefenseTypeInner

```csharp
public Image DefenseTypeInner
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### DefenseTypeText

```csharp
public Image DefenseTypeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Fill

```csharp
public Image Fill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Frame

```csharp
public Image Frame
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Icon

```csharp
public Image Icon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### IconOut

```csharp
public Image IconOut
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### PPos

```csharp
private static Vector2 PPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### RPos

```csharp
private static Vector2 RPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### Speed

```csharp
public float Speed
```
#INC


#### Field Value

**Type:** System.Single

### WPos

```csharp
private static Vector2 WPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### xMax

```csharp
private const float xMax = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### xMin

```csharp
private const float xMin = -0.5
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### randXPos

```csharp
private float randXPos { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### Invoker(MovableObjectNode)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, float)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, string)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, string context)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `context` | `System.String` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, string, float)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, string context, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `context` | `System.String` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, Type, UnitModel)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, DefenseInfo.Type defense, UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `defense` | `Global.DefenseInfo.Type` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3)

```csharp
public static DamageEffect Invoker(Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3, float)

```csharp
public static DamageEffect Invoker(Vector3 pos, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3, RwbpType, int, Type, UnitModel)

```csharp
public static DamageEffect Invoker(Vector3 pos, RwbpType type, int Damage, DefenseInfo.Type defense, UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `defense` | `Global.DefenseInfo.Type` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageEffect

### PositionSet(RwbpType)

```csharp
private void PositionSet(RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

### SetData(RwbpType, int, string)

```csharp
private void SetData(RwbpType type, int damage, string context)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `damage` | `System.Int32` |  |
| `context` | `System.String` |  |

### SetData(RwbpType, int, Type, UnitModel)

```csharp
private void SetData(RwbpType type, int damage, DefenseInfo.Type defense, UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `damage` | `System.Int32` |  |
| `defense` | `Global.DefenseInfo.Type` |  |
| `unit` | `Global.UnitModel` |  |

### Update()

```csharp
protected override void Update()
```
#INC
#code-generated

