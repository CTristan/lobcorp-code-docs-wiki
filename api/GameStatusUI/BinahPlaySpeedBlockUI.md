---
uid: GameStatusUI.BinahPlaySpeedBlockUI
canonical_path: /api/GameStatusUI/BinahPlaySpeedBlockUI
---

# Class BinahPlaySpeedBlockUI

**Namespace:** [GameStatusUI](/api/GameStatusUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahPlaySpeedBlockUI : PlaySpeedSettingBlockedUI
```

For displaying text indicated that you cannot change the play speed during the third phase of Binah's Sephirah meltdown.

See [BinahBossBase](/api/Global/Misc/BinahBossBase)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [PlaySpeedSettingBlockedUI](/api/GameStatusUI/PlaySpeedSettingBlockedUI) → BinahPlaySpeedBlockUI

## Inherited Members
[blockFunction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#blockfunction), [closeAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#closeaction), [timeStopTryAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timestoptryaction), [timeMultiplyingAction](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timemultiplyingaction), [actionLibrary](/api/GameStatusUI/PlaySpeedSettingBlockedUI#actionlibrary), [Timer](/api/GameStatusUI/PlaySpeedSettingBlockedUI#timer), [Duration](/api/GameStatusUI/PlaySpeedSettingBlockedUI#duration), [_isDisplaying](/api/GameStatusUI/PlaySpeedSettingBlockedUI#isdisplaying), [SetCloseAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#setcloseaction-voidaction), [CloseActionExecute()](/api/GameStatusUI/PlaySpeedSettingBlockedUI#closeactionexecute), [OnClose()](/api/GameStatusUI/PlaySpeedSettingBlockedUI#onclose), [AddAction(PlaySpeedSettingBlockFunction, voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#addaction-playspeedsettingblockfunction-voidaction), [SetTimeStopAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#settimestopaction-voidaction), [SetTimeMultiplyingAction(voidAction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#settimemultiplyingaction-voidaction), [OnTryFunction(PlaySpeedSettingBlockFunction, bool)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#ontryfunction-playspeedsettingblockfunction-bool), [OnTryDisplay(PlaySpeedSettingBlockFunction)](/api/GameStatusUI/PlaySpeedSettingBlockedUI#ontrydisplay-playspeedsettingblockfunction), [IsDisplaying](/api/GameStatusUI/PlaySpeedSettingBlockedUI#isdisplaying), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahPlaySpeedBlockUI()

```csharp
public BinahPlaySpeedBlockUI()
```

## Fields

### binah

```csharp
private BinahCoreScript binah
```
#INC


#### Field Value

**Type:** Global.BinahCoreScript

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

### textDisplayed

```csharp
public Text textDisplayed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### textList

```csharp
private List<string> textList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

## Methods

### IsFunctionEnabled(PlaySpeedSettingBlockFunction)

```csharp
public override bool IsFunctionEnabled(PlaySpeedSettingBlockFunction function)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `function` | `Global.PlaySpeedSettingBlockFunction` |  |

#### Returns

**Type:** System.Boolean

### OnShow()

```csharp
public override void OnShow()
```
#INC
#code-generated


### OnTryTimeStop()

```csharp
public void OnTryTimeStop()
```
#INC


### SetBinah(BinahCoreScript)

```csharp
public void SetBinah(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

### SetText(params string[])

```csharp
public void SetText(params string[] texts)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `texts` | `System.String[]` |  |

### Update()

```csharp
public override void Update()
```
#INC

