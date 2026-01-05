# Class ChildCreatureUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureUnit : CreatureUnit, IMouseOnSelectListener, IMouseCommandTarget
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [CreatureUnit](/api/CreatureUnit) → ChildCreatureUnit

## Inherited Members
[model](/api/CreatureUnit#model), [room](/api/CreatureUnit#room), [returnSpriteRenderer](/api/CreatureUnit#returnspriterenderer), [returnObject](/api/CreatureUnit#returnobject), [currentCreatureCanvas](/api/CreatureUnit#currentcreaturecanvas), [castingSlider](/api/CreatureUnit#castingslider), [cameraSensingArea](/api/CreatureUnit#camerasensingarea), [animTarget](/api/CreatureUnit#animtarget), [defaultMouseTarget](/api/CreatureUnit#defaultmousetarget), [_unitMouseEventTarget](/api/CreatureUnit#unitmouseeventtarget), [speech](/api/CreatureUnit#speech), [directionScaleFactor](/api/CreatureUnit#directionscalefactor), [scaleFactor](/api/CreatureUnit#scalefactor), [viewPosition](/api/CreatureUnit#viewposition), [visible](/api/CreatureUnit#visible), [scaleSetting](/api/CreatureUnit#scalesetting), [debugText](/api/CreatureUnit#debugtext), [escapeUIRoot](/api/CreatureUnit#escapeuiroot), [hpSlider](/api/CreatureUnit#hpslider), [hpBg](/api/CreatureUnit#hpbg), [hpFill](/api/CreatureUnit#hpfill), [escapeRisk](/api/CreatureUnit#escaperisk), [escapeCreatureName](/api/CreatureUnit#escapecreaturename), [defHp](/api/CreatureUnit#defhp), [casting](/api/CreatureUnit#casting), [oldState](/api/CreatureUnit#oldstate), [SetSliderColor(SliderColorSet)](/api/CreatureUnit#setslidercolor-slidercolorset), [TempUpdateViewPos()](/api/CreatureUnit#tempupdateviewpos), [GetScaleFactor()](/api/CreatureUnit#getscalefactor), [SetScaleFactor(float, float, float)](/api/CreatureUnit#setscalefactor-float-float-float), [PlaySoundMono(string)](/api/CreatureUnit#playsoundmono-string), [PlaySound(string)](/api/CreatureUnit#playsound-string), [PlaySound(string, float)](/api/CreatureUnit#playsound-string-float), [PlaySound(string, AudioRolloffMode)](/api/CreatureUnit#playsound-string-audiorolloffmode), [PlaySoundLoop(string)](/api/CreatureUnit#playsoundloop-string), [PlaySoundLoop(string, float)](/api/CreatureUnit#playsoundloop-string-float), [OnClickCollectionFunc()](/api/CreatureUnit#onclickcollectionfunc), [OnClicked()](/api/CreatureUnit#onclicked), [GetCommandTargetModel()](/api/CreatureUnit#getcommandtargetmodel), [OnClickByRoom(PointerEventData)](/api/CreatureUnit#onclickbyroom-pointereventdata), [IsSelectable()](/api/CreatureUnit#isselectable), [OnSelect()](/api/CreatureUnit#onselect), [OnUnselect()](/api/CreatureUnit#onunselect), [ResetAnimatorTransform()](/api/CreatureUnit#resetanimatortransform), [SetRoomFog(float)](/api/CreatureUnit#setroomfog-float), [SetRoomFog(float, float)](/api/CreatureUnit#setroomfog-float-float), [ReleaseFog()](/api/CreatureUnit#releasefog), [SpecialSkill()](/api/CreatureUnit#specialskill), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ChildCreatureUnit()

```csharp
public ChildCreatureUnit()
```

## Fields

### init

```csharp
public bool init
```

#### Field Value

**Type:** System.Boolean

## Properties

### Model

```csharp
public ChildCreatureModel Model { get; }
```

#### Property Value

**Type:** Global.ChildCreatureModel

## Methods

### Awake()

```csharp
public override void Awake()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### Init()

```csharp
public void Init()
```

### LateUpdate()

```csharp
public override void LateUpdate()
```

### OnChangeState()

```csharp
public override void OnChangeState()
```

### OnClick()

```csharp
public void OnClick()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### Start()

```csharp
public override void Start()
```

### Update()

```csharp
public override void Update()
```

### UpdateDirection()

```csharp
protected override void UpdateDirection()
```

### UpdateScale()

```csharp
protected override void UpdateScale()
```

### UpdateViewPosition()

```csharp
protected override void UpdateViewPosition()
```
