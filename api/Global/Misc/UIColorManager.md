---
uid: Global.UIColorManager
canonical_path: /api/Global/Misc/UIColorManager
---

# Class UIColorManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UIColorManager : MonoBehaviour
```

Manages the color of UI elements. #verify 

The colors present in the script are part of the UIColorManager game object.

#INC


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → UIColorManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UIColorManager()

```csharp
public UIColorManager()
```

## Fields

### _instance

```csharp
private static UIColorManager _instance
```
#INC


#### Field Value

**Type:** Global.UIColorManager

### Allocate_SefiraGray

```csharp
public Color Allocate_SefiraGray
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### Allocate_SefiraGreen

```csharp
public Color Allocate_SefiraGreen
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### DisabledColor

```csharp
[Header("IsolateRoom Color")]
public Color[] DisabledColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### EscapedColor

```csharp
public Color EscapedColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### isolateRoomUI

```csharp
public CreatureLayer.IsolateRoomUI isolateRoomUI
```
#INC


#### Field Value

**Type:** Global.CreatureLayer.IsolateRoomUI

### orange

```csharp
public Color orange
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### OverloadColor

```csharp
public Color[] OverloadColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### RiskLevelColor

```csharp
public Color[] RiskLevelColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### RWBPTextColor

```csharp
public Color[] RWBPTextColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### RWBPTypeColor

```csharp
public Color[] RWBPTypeColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### sefiraColor

```csharp
public SefiraUIColor[] sefiraColor
```
#INC


#### Field Value

**Type:** Global.SefiraUIColor[]

### sefiraUnlockedColor

```csharp
public Color sefiraUnlockedColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UIBlueColor

```csharp
public Color UIBlueColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UIDisabledColor

```csharp
public Color UIDisabledColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UINormalColor

```csharp
public Color UINormalColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UIRedColor

```csharp
public Color UIRedColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### uiTextDefColor

```csharp
public Color uiTextDefColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

## Properties

### instance

```csharp
public static UIColorManager instance { get; }
```

#### Property Value

**Type:** Global.UIColorManager

### Orange

```csharp
public static Color Orange { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### SefiraUnlockedColor

```csharp
public static Color SefiraUnlockedColor { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### UITextDefColor

```csharp
public static Color UITextDefColor { get; }
```

#### Property Value

**Type:** UnityEngine.Color

## Methods

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### GetDisabledRoomColor(SefiraEnum)

```csharp
public Color GetDisabledRoomColor(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** UnityEngine.Color

### GetOverloadColor(OverloadType)

```csharp
public Color GetOverloadColor(OverloadType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

#### Returns

**Type:** UnityEngine.Color

### GetRiskColor(RiskLevel)

```csharp
public Color GetRiskColor(RiskLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns

**Type:** UnityEngine.Color

### GetRWBPTextColor(RwbpType)

```csharp
public Color GetRWBPTextColor(RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** UnityEngine.Color

### GetRWBPTypeColor(RwbpType)

```csharp
public Color GetRWBPTypeColor(RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** UnityEngine.Color

### GetRWBPTypeColor(RwbpType, out Color, out Color)

```csharp
public void GetRWBPTypeColor(RwbpType type, out Color inner, out Color outter)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `inner` | `UnityEngine.Color` |  |
| `outter` | `UnityEngine.Color` |  |

### GetSefiraColor(Sefira)

```csharp
public SefiraUIColor GetSefiraColor(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** Global.SefiraUIColor

### GetSefiraColor(SefiraEnum)

```csharp
public SefiraUIColor GetSefiraColor(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.SefiraUIColor

### GetSefiraColor(string)

```csharp
public SefiraUIColor GetSefiraColor(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** Global.SefiraUIColor
