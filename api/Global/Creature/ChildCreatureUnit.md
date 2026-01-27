---
uid: Global.ChildCreatureUnit
canonical_path: /api/Global/Creature/ChildCreatureUnit
---

# Class ChildCreatureUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureUnit : CreatureUnit, IMouseOnSelectListener, IMouseCommandTarget
```

A child creature, as it appears in-game.

See also [ChildCreatureModel](/api/Global/Creature/ChildCreatureModel).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [CreatureUnit](/api/Global/Unit/CreatureUnit) → ChildCreatureUnit

## Implements
[IMouseOnSelectListener](/api/Global/Misc/IMouseOnSelectListener), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget)

## Inherited Members
[model](/api/Global/Unit/CreatureUnit#model), [room](/api/Global/Unit/CreatureUnit#room), [returnSpriteRenderer](/api/Global/Unit/CreatureUnit#returnspriterenderer), [returnObject](/api/Global/Unit/CreatureUnit#returnobject), [currentCreatureCanvas](/api/Global/Unit/CreatureUnit#currentcreaturecanvas), [castingSlider](/api/Global/Unit/CreatureUnit#castingslider), [cameraSensingArea](/api/Global/Unit/CreatureUnit#camerasensingarea), [animTarget](/api/Global/Unit/CreatureUnit#animtarget), [defaultMouseTarget](/api/Global/Unit/CreatureUnit#defaultmousetarget), [_unitMouseEventTarget](/api/Global/Unit/CreatureUnit#unitmouseeventtarget), [speech](/api/Global/Unit/CreatureUnit#speech), [directionScaleFactor](/api/Global/Unit/CreatureUnit#directionscalefactor), [scaleFactor](/api/Global/Unit/CreatureUnit#scalefactor), [oldScale](/api/Global/Unit/CreatureUnit#oldscale), [viewPosition](/api/Global/Unit/CreatureUnit#viewposition), [visible](/api/Global/Unit/CreatureUnit#visible), [scaleSetting](/api/Global/Unit/CreatureUnit#scalesetting), [debugText](/api/Global/Unit/CreatureUnit#debugtext), [escapeUIRoot](/api/Global/Unit/CreatureUnit#escapeuiroot), [hpSlider](/api/Global/Unit/CreatureUnit#hpslider), [hpBg](/api/Global/Unit/CreatureUnit#hpbg), [hpFill](/api/Global/Unit/CreatureUnit#hpfill), [escapeRisk](/api/Global/Unit/CreatureUnit#escaperisk), [escapeCreatureName](/api/Global/Unit/CreatureUnit#escapecreaturename), [defHp](/api/Global/Unit/CreatureUnit#defhp), [casting](/api/Global/Unit/CreatureUnit#casting), [currentSliderColor](/api/Global/Unit/CreatureUnit#currentslidercolor), [oldState](/api/Global/Unit/CreatureUnit#oldstate), [SetSliderColor(SliderColorSet)](/api/Global/Unit/CreatureUnit#setslidercolor-slidercolorset), [TempUpdateViewPos()](/api/Global/Unit/CreatureUnit#tempupdateviewpos), [GetScaleFactor()](/api/Global/Unit/CreatureUnit#getscalefactor), [SetScaleFactor(float, float, float)](/api/Global/Unit/CreatureUnit#setscalefactor-float-float-float), [PlaySoundMono(string)](/api/Global/Unit/CreatureUnit#playsoundmono-string), [PlaySound(string)](/api/Global/Unit/CreatureUnit#playsound-string), [PlaySound(string, float)](/api/Global/Unit/CreatureUnit#playsound-string-float), [PlaySound(string, AudioRolloffMode)](/api/Global/Unit/CreatureUnit#playsound-string-audiorolloffmode), [PlaySoundLoop(string)](/api/Global/Unit/CreatureUnit#playsoundloop-string), [PlaySoundLoop(string, float)](/api/Global/Unit/CreatureUnit#playsoundloop-string-float), [OnClickCollectionFunc()](/api/Global/Unit/CreatureUnit#onclickcollectionfunc), [OnClicked()](/api/Global/Unit/CreatureUnit#onclicked), [GetCommandTargetModel()](/api/Global/Unit/CreatureUnit#getcommandtargetmodel), [OnClickByRoom(PointerEventData)](/api/Global/Unit/CreatureUnit#onclickbyroom-pointereventdata), [IsSelectable()](/api/Global/Unit/CreatureUnit#isselectable), [OnSelect()](/api/Global/Unit/CreatureUnit#onselect), [OnUnselect()](/api/Global/Unit/CreatureUnit#onunselect), [ResetAnimatorTransform()](/api/Global/Unit/CreatureUnit#resetanimatortransform), [SetRoomFog(float)](/api/Global/Unit/CreatureUnit#setroomfog-float), [SetRoomFog(float, float)](/api/Global/Unit/CreatureUnit#setroomfog-float-float), [ReleaseFog()](/api/Global/Unit/CreatureUnit#releasefog), [SpecialSkill()](/api/Global/Unit/CreatureUnit#specialskill), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


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
#INC
#code-generated


### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### Init()

```csharp
public void Init()
```
#INC


### LateUpdate()

```csharp
public override void LateUpdate()
```
#INC


### OnChangeState()

```csharp
public override void OnChangeState()
```
#INC


### OnClick()

```csharp
public void OnClick()
```
#INC


### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### Start()

```csharp
public override void Start()
```
#INC


### Update()

```csharp
public override void Update()
```
#INC


### UpdateDirection()

```csharp
protected override void UpdateDirection()
```
#INC


### UpdateScale()

```csharp
protected override void UpdateScale()
```
#INC


### UpdateViewPosition()

```csharp
protected override void UpdateViewPosition()
```
#INC

