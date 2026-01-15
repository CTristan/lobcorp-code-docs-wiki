---
uid: Credit.CreditController
canonical_path: /api/Credit/CreditController
---

# Class CreditController

**Namespace:** [Credit](/api/Credit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreditController : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreditController

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreditController()

```csharp
public CreditController()
```

## Fields

### _closeTimer

```csharp
private Timer _closeTimer
```

#### Field Value

**Type:** Global.Timer

### _currentMainSection

```csharp
private CreditSection _currentMainSection
```

#### Field Value

**Type:** Credit.CreditSection

### _currentSection

```csharp
private CreditSection _currentSection
```

#### Field Value

**Type:** Credit.CreditSection

### _endTimer

```csharp
private Timer _endTimer
```

#### Field Value

**Type:** Global.Timer

### _initialRevelDelayTimer

```csharp
private Timer _initialRevelDelayTimer
```

#### Field Value

**Type:** Global.Timer

### _isMovedScene

```csharp
private bool _isMovedScene
```

#### Field Value

**Type:** System.Boolean

### _items

```csharp
private Queue<CreditItem> _items
```

#### Field Value

**Type:** System.Collections.Generic.Queue{Credit.CreditItem}

### _lastTextDelayTimer

```csharp
private Timer _lastTextDelayTimer
```

#### Field Value

**Type:** Global.Timer

### _mainItems

```csharp
private Queue<CreditItem> _mainItems
```

#### Field Value

**Type:** System.Collections.Generic.Queue{Credit.CreditItem}

### _mainRevealTimer

```csharp
private Timer _mainRevealTimer
```

#### Field Value

**Type:** Global.Timer

### _mainSections

```csharp
private Queue<CreditSection> _mainSections
```

#### Field Value

**Type:** System.Collections.Generic.Queue{Credit.CreditSection}

### _makeSectionName

```csharp
private bool _makeSectionName
```

#### Field Value

**Type:** System.Boolean

### _poolWaitTime

```csharp
private static float _poolWaitTime
```

#### Field Value

**Type:** System.Single

### _readyForEnd

```csharp
private bool _readyForEnd
```

#### Field Value

**Type:** System.Boolean

### _revealTimer

```csharp
private Timer _revealTimer
```

#### Field Value

**Type:** Global.Timer

### _sections

```csharp
private Queue<CreditSection> _sections
```

#### Field Value

**Type:** System.Collections.Generic.Queue{Credit.CreditSection}

### _startImageHalfMoved

```csharp
private bool _startImageHalfMoved
```

#### Field Value

**Type:** System.Boolean

### _startImageMoved

```csharp
private bool _startImageMoved
```

#### Field Value

**Type:** System.Boolean

### _waitTimer

```csharp
private Timer _waitTimer
```

#### Field Value

**Type:** Global.Timer

### CloseBlackImage

```csharp
public Image CloseBlackImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CloseTime

```csharp
public float CloseTime
```

#### Field Value

**Type:** System.Single

### CreditParticleUnit

```csharp
public GameObject CreditParticleUnit
```

#### Field Value

**Type:** UnityEngine.GameObject

### CreditTextLayer

```csharp
public RectTransform CreditTextLayer
```

#### Field Value

**Type:** UnityEngine.RectTransform

### CreditTextUnit

```csharp
[Header("Prefab")]
public GameObject CreditTextUnit
```

#### Field Value

**Type:** UnityEngine.GameObject

### CurrentRegionDisplay

```csharp
public Text CurrentRegionDisplay
```

#### Field Value

**Type:** UnityEngine.UI.Text

### EndingDelay

```csharp
public float EndingDelay
```

#### Field Value

**Type:** System.Single

### InitialDelay

```csharp
public float InitialDelay
```

#### Field Value

**Type:** System.Single

### LastTextDelay

```csharp
public float LastTextDelay
```

#### Field Value

**Type:** System.Single

### lastTextUnit

```csharp
private CreditTextUnit lastTextUnit
```

#### Field Value

**Type:** Credit.CreditTextUnit

### Logo

```csharp
public Image Logo
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LogoMoveFactor

```csharp
public float LogoMoveFactor
```

#### Field Value

**Type:** System.Single

### MainAscendSpeed

```csharp
public float MainAscendSpeed
```

#### Field Value

**Type:** System.Single

### MainExecutionDelay

```csharp
public float MainExecutionDelay
```

#### Field Value

**Type:** System.Single

### MainRevelFreq

```csharp
public float MainRevelFreq
```

#### Field Value

**Type:** System.Single

### MainStartDelay

```csharp
public float MainStartDelay
```

#### Field Value

**Type:** System.Single

### MainTypeVerticalAppearRange

```csharp
public MinMax MainTypeVerticalAppearRange
```

#### Field Value

**Type:** Global.MinMax

### pool

```csharp
private List<CreditTextUnit> pool
```

#### Field Value

**Type:** System.Collections.Generic.List{Credit.CreditTextUnit}

### RegionAlphaCurve

```csharp
[Header("Curves")]
public AnimationCurve RegionAlphaCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### TextLifeTime

```csharp
public MinMax TextLifeTime
```

#### Field Value

**Type:** Global.MinMax

### TextRevealFreq

```csharp
[Header("RandomValue")]
public MinMax TextRevealFreq
```

#### Field Value

**Type:** Global.MinMax

### TextSpeed

```csharp
public MinMax TextSpeed
```

#### Field Value

**Type:** Global.MinMax

### TextUnitPoolCount

```csharp
public int TextUnitPoolCount
```

#### Field Value

**Type:** System.Int32

### textUnits

```csharp
private List<CreditTextUnit> textUnits
```

#### Field Value

**Type:** System.Collections.Generic.List{Credit.CreditTextUnit}

### TextVerticalAppearList

```csharp
public List<MinMax> TextVerticalAppearList
```

#### Field Value

**Type:** System.Collections.Generic.List{MinMax}

## Properties

### Controller

```csharp
public static CreditController Controller { get; private set; }
```

#### Property Value

**Type:** Credit.CreditController

## Methods

### Awake()

```csharp
private void Awake()
```

### EndCredit()

```csharp
private void EndCredit()
```

### ExecuteItem()

```csharp
private void ExecuteItem()
```

### ExecuteMainItem()

```csharp
private void ExecuteMainItem()
```

### ExecuteMainSection()

```csharp
private void ExecuteMainSection()
```

### ExecuteSection()

```csharp
private void ExecuteSection()
```

### FailureAction(int)

```csharp
private void FailureAction(int type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

### FixedUpdate()

```csharp
private void FixedUpdate()
```

### GetPool()

```csharp
public CreditTextUnit GetPool()
```

#### Returns

**Type:** Credit.CreditTextUnit

### GetVerticalAppearPosition()

```csharp
public float GetVerticalAppearPosition()
```

#### Returns

**Type:** System.Single

### MakeAscendText(string, float, int, float)

```csharp
private CreditTextUnit MakeAscendText(string text, float nextTime, int font = 40, float height = 100)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `nextTime` | `System.Single` |  |
| `font` | `System.Int32` |  |
| `height` | `System.Single` |  |

#### Returns

**Type:** Credit.CreditTextUnit

### MakeLastText()

```csharp
private void MakeLastText()
```

### ReturnPooledObject(CreditTextUnit)

```csharp
public void ReturnPooledObject(CreditTextUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Credit.CreditTextUnit` |  |

### SetBlackFadeAlpha(float)

```csharp
private void SetBlackFadeAlpha(float a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Single` |  |

### Start()

```csharp
private void Start()
```

### Update()

```csharp
private void Update()
```

### Wait()

```csharp
private void Wait()
```
