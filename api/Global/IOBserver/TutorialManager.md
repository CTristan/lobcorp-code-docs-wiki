---
uid: Global.TutorialManager
canonical_path: /api/Global/IOBserver/TutorialManager
---

# Class TutorialManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialManager : MonoBehaviour, IObserver
```

Manages the current tutorial and queues the next one maybe probably.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → TutorialManager

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TutorialManager()

```csharp
public TutorialManager()
```

## Fields

### _instance

```csharp
private static TutorialManager _instance
```
#INC


#### Field Value

**Type:** Global.TutorialManager

### ArrowManager

```csharp
public ArrowManager ArrowManager
```
#INC


#### Field Value

**Type:** Global.ArrowManager

### blackScreen

```csharp
public GameObject blackScreen
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### clickBlockCanvas

```csharp
public Canvas clickBlockCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### currentTutorial

```csharp
private Tutorial currentTutorial
```
#INC


#### Field Value

**Type:** Global.Tutorial

### DragCameraTutorialImage

```csharp
public GameObject DragCameraTutorialImage
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### DragObjectTutorialImage

```csharp
public GameObject DragObjectTutorialImage
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### escape

```csharp
public GameObject escape
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### popUp

```csharp
public GameObject popUp
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### ScrollTutorialImage

```csharp
public GameObject ScrollTutorialImage
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### tutorialObjs

```csharp
public GameObject[] tutorialObjs
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### tutorials

```csharp
private List<Tutorial> tutorials
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Tutorial}

## Properties

### CurrentOrder

```csharp
public int CurrentOrder { get; }
```

#### Property Value

**Type:** System.Int32

### CurrentTutorial

```csharp
public Tutorial CurrentTutorial { get; }
```

#### Property Value

**Type:** Global.Tutorial

### instance

```csharp
public static TutorialManager instance { get; }
```

#### Property Value

**Type:** Global.TutorialManager

## Methods

### AddTutorial(Tutorial)

```csharp
public void AddTutorial(Tutorial tutorial)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tutorial` | `Global.Tutorial` |  |

### CompletedAllTutorials()

```csharp
public void CompletedAllTutorials()
```
#INC


### CompleteTutoiral()

```csharp
public void CompleteTutoiral()
```
#INC


### GetTutorialByOrder(int)

```csharp
public Tutorial GetTutorialByOrder(int order)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `order` | `System.Int32` |  |

#### Returns

**Type:** Global.Tutorial

### HasNextTutotiralScene()

```csharp
private bool HasNextTutotiralScene()
```
#INC


#### Returns

**Type:** System.Boolean

### NextTutorialScene()

```csharp
private void NextTutorialScene()
```
#INC


### OnClickNo_Escape()

```csharp
public void OnClickNo_Escape()
```
#INC


### OnClickNo_PopUp()

```csharp
public void OnClickNo_PopUp()
```
#INC


### OnClickYes_Escape()

```csharp
public void OnClickYes_Escape()
```
#INC


### OnClickYes_PopUp()

```csharp
public void OnClickYes_PopUp()
```
#INC


### OnDisable()

```csharp
private void OnDisable()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### ReturnToMenu()

```csharp
private void ReturnToMenu()
```
#INC


### SetEscape(bool)

```csharp
private void SetEscape(bool isActive)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isActive` | `System.Boolean` |  |

### SetNextTutorial(int)

```csharp
public void SetNextTutorial(int currentOrder)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentOrder` | `System.Int32` |  |

### SetPopUp(bool)

```csharp
private void SetPopUp(bool isActive)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isActive` | `System.Boolean` |  |

### TutorialImagesOff()

```csharp
private void TutorialImagesOff()
```
#INC


### TutorialStart()

```csharp
private void TutorialStart()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

