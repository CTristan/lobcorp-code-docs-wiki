---
uid: Global.AnimatorManager
canonical_path: /api/Global/Animator/AnimatorManager
---

# Class AnimatorManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AnimatorManager : MonoBehaviour
```
Loads and stores animations


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AnimatorManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimatorManager()

```csharp
public AnimatorManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static AnimatorManager _instance
```
#INC


#### Field Value

**Type:** Global.AnimatorManager

### creatureLib

```csharp
private List<AnimatorManager.AnimatorComponet> creatureLib
```

#### Field Value

**Type:** System.Collections.Generic.List{AnimatorManager.AnimatorComponet}

### dynamicLib

```csharp
public List<AnimatorManager.AnimatorComponet> dynamicLib
```

#### Field Value

**Type:** System.Collections.Generic.List{AnimatorManager.AnimatorComponet}

### isLoaded

```csharp
private static bool isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### staticLib

```csharp
public List<AnimatorManager.AnimatorComponet> staticLib
```

#### Field Value

**Type:** System.Collections.Generic.List{AnimatorManager.AnimatorComponet}

## Properties

### instance

```csharp
public static AnimatorManager instance { get; }
```

#### Property Value

**Type:** Global.AnimatorManager

## Methods

### Awake()

```csharp
private void Awake()
```
#INC


### ChangeAnimatorByID(long, long, Animator, bool, bool)

```csharp
public void ChangeAnimatorByID(long id, long targetID, Animator animator, bool isStatic, bool isSaved)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `targetID` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |
| `isStatic` | `System.Boolean` |  |
| `isSaved` | `System.Boolean` |  |

### ChangeAnimatorByName(long, string, Animator, bool, bool)

```csharp
public void ChangeAnimatorByName(long id, string targetStr, Animator animator, bool isStatic, bool isSaved)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `targetStr` | `System.String` |  |
| `animator` | `UnityEngine.Animator` |  |
| `isStatic` | `System.Boolean` |  |
| `isSaved` | `System.Boolean` |  |

### ChangeAnimatorWithSave(long, Animator, string)

```csharp
public void ChangeAnimatorWithSave(long id, Animator animator, string target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |
| `target` | `System.String` |  |

### ChangeAnimatorWithSave(long, Animator, string, string)

```csharp
public void ChangeAnimatorWithSave(long id, Animator animator, string target, string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |
| `target` | `System.String` |  |
| `name` | `System.String` |  |

### GetSavedAnimator(long, bool)

```csharp
public AnimatorManager.AnimatorComponet GetSavedAnimator(long id, bool isDeleted)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `isDeleted` | `System.Boolean` |  |

#### Returns

**Type:** Global.AnimatorManager.AnimatorComponet

### GetSavedAnimator(string, bool)

```csharp
public AnimatorManager.AnimatorComponet GetSavedAnimator(string name, bool isDeleted)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `isDeleted` | `System.Boolean` |  |

#### Returns

**Type:** Global.AnimatorManager.AnimatorComponet

### GetStaticAnimator(long)

```csharp
public AnimatorManager.AnimatorComponet GetStaticAnimator(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.AnimatorManager.AnimatorComponet

### GetStaticAnimator(string)

```csharp
public AnimatorManager.AnimatorComponet GetStaticAnimator(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.AnimatorManager.AnimatorComponet

### Init(AnimatorComponet[])

```csharp
public void Init(AnimatorManager.AnimatorComponet[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.AnimatorManager.AnimatorComponet[]` |  |

### IsContainCreature(long)

```csharp
public bool IsContainCreature(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### IsLoaded()

```csharp
public bool IsLoaded()
```
#INC


#### Returns

**Type:** System.Boolean

### LoadAnimatorData()

```csharp
private void LoadAnimatorData()
```
#INC


### ResetAnimatorTransform(long)

```csharp
public void ResetAnimatorTransform(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### ResetCreatureAnimatorTransform(long)

```csharp
public void ResetCreatureAnimatorTransform(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### SaveAnimator(long, Animator)

```csharp
public void SaveAnimator(long id, Animator animator)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |

### SaveAnimator(long, Animator, string)

```csharp
public void SaveAnimator(long id, Animator animator, string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |
| `name` | `System.String` |  |

### SaveCreatureAnimator(long, Animator)

```csharp
public void SaveCreatureAnimator(long id, Animator animator)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `animator` | `UnityEngine.Animator` |  |
