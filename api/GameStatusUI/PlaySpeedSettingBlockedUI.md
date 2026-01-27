---
uid: GameStatusUI.PlaySpeedSettingBlockedUI
canonical_path: /api/GameStatusUI/PlaySpeedSettingBlockedUI
---

# Class PlaySpeedSettingBlockedUI

**Namespace:** [GameStatusUI](/api/GameStatusUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlaySpeedSettingBlockedUI : MonoBehaviour
```

extends 

Parent class for things which want to stop you from adjusting the play speed settings, checking the escape menu, or checking the manual.

Extended by:
- [WhiteNight's pause and speed control blocking](/api/WhiteNightSpace/DeathAngelPlaySpeedBlockUI)
- [Hokma's pause blocking](/api/GameStatusUI/ChokhmahPlaySpeedBlockUI)
- [Binah's pause blocking](/api/GameStatusUI/BinahPlaySpeedBlockUI)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → PlaySpeedSettingBlockedUI

## Derived
[BinahPlaySpeedBlockUI](/api/GameStatusUI/BinahPlaySpeedBlockUI), [ChokhmahPlaySpeedBlockUI](/api/GameStatusUI/ChokhmahPlaySpeedBlockUI), [DeathAngelPlaySpeedBlockUI](/api/WhiteNightSpace/DeathAngelPlaySpeedBlockUI)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PlaySpeedSettingBlockedUI()

```csharp
public PlaySpeedSettingBlockedUI()
```

## Fields

### _isDisplaying

```csharp
private bool _isDisplaying
```
#INC


#### Field Value

**Type:** System.Boolean

### actionLibrary

```csharp
public Dictionary<PlaySpeedSettingBlockFunction, PlaySpeedSettingBlockedUI.voidAction> actionLibrary
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{PlaySpeedSettingBlockFunction,GameStatusUI.PlaySpeedSettingBlockedUI.voidAction}

### blockFunction

```csharp
public PlaySpeedSettingBlockFunction blockFunction
```
#INC


#### Field Value

**Type:** Global.PlaySpeedSettingBlockFunction

### closeAction

```csharp
public PlaySpeedSettingBlockedUI.voidAction closeAction
```

#### Field Value

**Type:** GameStatusUI.PlaySpeedSettingBlockedUI.voidAction

### Duration

```csharp
public float Duration
```
#INC


#### Field Value

**Type:** System.Single

### timeMultiplyingAction

```csharp
public PlaySpeedSettingBlockedUI.voidAction timeMultiplyingAction
```

#### Field Value

**Type:** GameStatusUI.PlaySpeedSettingBlockedUI.voidAction

### Timer

```csharp
public UnscaledTimer Timer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### timeStopTryAction

```csharp
public PlaySpeedSettingBlockedUI.voidAction timeStopTryAction
```

#### Field Value

**Type:** GameStatusUI.PlaySpeedSettingBlockedUI.voidAction

## Properties

### IsDisplaying

```csharp
public bool IsDisplaying { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddAction(PlaySpeedSettingBlockFunction, voidAction)

```csharp
public virtual void AddAction(PlaySpeedSettingBlockFunction function, PlaySpeedSettingBlockedUI.voidAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |
| `action` | `GameStatusUI.PlaySpeedSettingBlockedUI.voidAction` |  |

### CloseActionExecute()

```csharp
protected void CloseActionExecute()
```
#INC


### IsFunctionEnabled(PlaySpeedSettingBlockFunction)

```csharp
public virtual bool IsFunctionEnabled(PlaySpeedSettingBlockFunction function)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

#### Returns

**Type:** System.Boolean

### OnClose()

```csharp
public virtual void OnClose()
```
#INC


### OnShow()

```csharp
public virtual void OnShow()
```
#INC


### OnTryDisplay(PlaySpeedSettingBlockFunction)

```csharp
public virtual bool OnTryDisplay(PlaySpeedSettingBlockFunction function)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

#### Returns

**Type:** System.Boolean

### OnTryFunction(PlaySpeedSettingBlockFunction, bool)

```csharp
public virtual void OnTryFunction(PlaySpeedSettingBlockFunction function, bool isOnCheck = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |
| `isOnCheck` | `System.Boolean` |  |

### SetCloseAction(voidAction)

```csharp
public void SetCloseAction(PlaySpeedSettingBlockedUI.voidAction closeAction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `closeAction` | `GameStatusUI.PlaySpeedSettingBlockedUI.voidAction` |  |

### SetTimeMultiplyingAction(voidAction)

```csharp
public virtual void SetTimeMultiplyingAction(PlaySpeedSettingBlockedUI.voidAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GameStatusUI.PlaySpeedSettingBlockedUI.voidAction` |  |

### SetTimeStopAction(voidAction)

```csharp
public virtual void SetTimeStopAction(PlaySpeedSettingBlockedUI.voidAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GameStatusUI.PlaySpeedSettingBlockedUI.voidAction` |  |

### Update()

```csharp
public virtual void Update()
```
#INC

