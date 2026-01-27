---
uid: WhiteNightSpace.DeathAngelPlaySpeedBlockUI
canonical_path: /api/WhiteNightSpace/DeathAngelPlaySpeedBlockUI
---

# Class DeathAngelPlaySpeedBlockUI

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelPlaySpeedBlockUI : PlaySpeedSettingBlockedUI
```

UI for [WhiteNight](/api/Legacy/DeathAngel) stopping you from pausing and escaping to menu and opening the manual...


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [PlaySpeedSettingBlockedUI](/api/GameStatusUI/PlaySpeedSettingBlockedUI) → DeathAngelPlaySpeedBlockUI

## Inherited Members
[blockFunction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#blockfunction), [closeAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#closeaction), [timeStopTryAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timestoptryaction), [timeMultiplyingAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timemultiplyingaction), [actionLibrary](/api/GameStatusUI/PlaySpeedSettingBlockedUI#actionlibrary), [Timer](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timer), [Duration](/api/GameStatusUI/PlaySpeedSettingBlockedUI#duration), [_isDisplaying](/api/GameStatusUI/PlaySpeedSettingBlockedUI#isdisplaying), [SetCloseAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#setcloseaction-voidaction), [CloseActionExecute()](/api/GameStatusUI/PlaySpeedSettingBlockedUI#closeactionexecute), [OnClose()](/api/GameStatusUI/PlaySpeedSettingBlockedUI#onclose), [AddAction(PlaySpeedSettingBlockFunction, voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#addaction-playspeedsettingblockfunction-voidaction), [SetTimeStopAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#settimestopaction-voidaction), [SetTimeMultiplyingAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#settimemultiplyingaction-voidaction), [OnTryFunction(PlaySpeedSettingBlockFunction, bool)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#ontryfunction-playspeedsettingblockfunction-bool), [OnTryDisplay(PlaySpeedSettingBlockFunction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#ontrydisplay-playspeedsettingblockfunction), [IsDisplaying](/api/GameStatusUI/PlaySpeedSettingBlockedUI#isdisplaying), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngelPlaySpeedBlockUI()

```csharp
public DeathAngelPlaySpeedBlockUI()
```

## Fields

### _deathAngel

```csharp
private DeathAngel _deathAngel
```
#INC


#### Field Value

**Type:** WhiteNightSpace.DeathAngel

### clip

```csharp
public AudioClip clip
```
#INC


#### Field Value

**Type:** UnityEngine.AudioClip

### curve

```csharp
public AnimationCurve curve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### group

```csharp
public CanvasGroup group
```
#INC


#### Field Value

**Type:** UnityEngine.CanvasGroup

### manualTexts

```csharp
private List<string> manualTexts
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### multiplyTexts

```csharp
private List<string> multiplyTexts
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### pauseTexts

```csharp
private List<string> pauseTexts
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### textDisplayed

```csharp
public Text textDisplayed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### IsFunctionEnabled(PlaySpeedSettingBlockFunction)

```csharp
public override bool IsFunctionEnabled(PlaySpeedSettingBlockFunction function)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

#### Returns

**Type:** System.Boolean

### MakeSound(string)

```csharp
public void MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### OnShow()

```csharp
public override void OnShow()
```
#INC


### OnTryEscape()

```csharp
public void OnTryEscape()
```
#INC


### OnTryOpenManual()

```csharp
public void OnTryOpenManual()
```
#INC


### OnTryPause()

```csharp
public void OnTryPause()
```
#INC


### OnTryTimeMultiplier()

```csharp
public void OnTryTimeMultiplier()
```
#INC


### SetAngel(DeathAngel)

```csharp
public void SetAngel(DeathAngel angel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angel` | `WhiteNightSpace.DeathAngel` |  |

### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC

