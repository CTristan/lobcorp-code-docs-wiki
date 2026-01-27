---
uid: CreatureInfo.CreatureInfoCaretakingSlot
canonical_path: /api/CreatureInfo/CreatureInfoCaretakingSlot
---

# Class CreatureInfoCaretakingSlot

**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureInfoCaretakingSlot : CreatureInfoController, IScrollMessageReciever
```
Class for a management tip? #inc


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [CreatureInfoController](/api/Global/Creature/CreatureInfoController) → CreatureInfoCaretakingSlot

## Implements
[IScrollMessageReciever](/api/Global/Misc/IScrollMessageReciever)

## Inherited Members
[_currentCreature](/api/Global/Creature/CreatureInfoController#currentcreature), [_isOpened](/api/Global/Creature/CreatureInfoController#isopened), [_areaName](/api/Global/Creature/CreatureInfoController#areaname), [_cost](/api/Global/Creature/CreatureInfoController#cost), [SetArea(string)](/api/Global/Creature/CreatureInfoController#setarea-string), [IsOpened()](/api/Global/Creature/CreatureInfoController#isopened), [AreaName](/api/Global/Creature/CreatureInfoController#areaname), [MetaInfo](/api/Global/Creature/CreatureInfoController#metainfo), [ObserveInfo](/api/Global/Creature/CreatureInfoController#observeinfo), [CurrentModel](/api/Global/Creature/CreatureInfoController#currentmodel), [Cost](/api/Global/Creature/CreatureInfoController#cost), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureInfoCaretakingSlot()

```csharp
public CreatureInfoCaretakingSlot()
```

## Fields

### _arrowActivated

```csharp
private bool _arrowActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### _index

```csharp
private int _index
```
#INC


#### Field Value

**Type:** System.Int32

### Arrow_Down

```csharp
public GameObject Arrow_Down
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Arrow_Up

```csharp
public GameObject Arrow_Up
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### ArrowRoot

```csharp
public GameObject ArrowRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### big

```csharp
private const float big = 827
```
#INC


#### Field Value

**Type:** System.Single

### CaretakingSection

```csharp
public Text CaretakingSection
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### fitterFont

```csharp
private const int fitterFont = 30
```
#INC


#### Field Value

**Type:** System.Int32

### listParent

```csharp
public RectTransform listParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### Open

```csharp
public CreatureInfoOpenArea Open
```
#INC


#### Field Value

**Type:** CreatureInfo.CreatureInfoOpenArea

### PrevSlot

```csharp
public CreatureInfoCaretakingSlot PrevSlot
```
#INC


#### Field Value

**Type:** CreatureInfo.CreatureInfoCaretakingSlot

### scrollExchanger

```csharp
public ScrollExchanger scrollExchanger
```
#INC


#### Field Value

**Type:** Global.ScrollExchanger

### small

```csharp
private const float small = 758
```
#INC


#### Field Value

**Type:** System.Single

### spacing

```csharp
private const float spacing = 10
```
#INC


#### Field Value

**Type:** System.Single

### Title

```csharp
public Text Title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### _isActivated

```csharp
private bool _isActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### fitter

```csharp
public ContentSizeFitter fitter { get; }
```

#### Property Value

**Type:** UnityEngine.UI.ContentSizeFitter

### RectTransform

```csharp
public RectTransform RectTransform { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

### TextParent

```csharp
private RectTransform TextParent { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

### TextRect

```csharp
public RectTransform TextRect { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

## Methods

### Awake()

```csharp
private void Awake()
```
#INC


### Initialize()

```csharp
public override void Initialize()
```
#INC


### Initialize(CreatureModel)

```csharp
public override void Initialize(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### IsOpenable()

```csharp
public override bool IsOpenable()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### OnClick()

```csharp
public override bool OnClick()
```
#INC


#### Returns

**Type:** System.Boolean

### OnPurchase()

```csharp
public override void OnPurchase()
```
#INC


### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnSetText(Text)

```csharp
public void OnSetText(Text text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `UnityEngine.UI.Text` |  |

### SetData(string)

```csharp
public void SetData(string desc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### SetTitleText()

```csharp
public void SetTitleText()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

