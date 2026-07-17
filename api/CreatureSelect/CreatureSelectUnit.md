---
title: CreatureSelectUnit
description: 
published: true
date: 2026-07-17T19:44:45.436Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:38:31.291Z
---

# Class CreatureSelectUnit
**Namespace:** [CreatureSelect](/api/CreatureSelect)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSelectUnit : MonoBehaviour, IAnimatorEventCalled
```
The script for a door on the abnormality extraction screen ([`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI)).

See [Abnormality Extraction](/abnormality-extraction) for more information about the abnormality extraction system.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreatureSelectUnit

## Implements
[IAnimatorEventCalled](/api/Global/Animation/IAnimatorEventCalled)

## Constructors
### CreatureSelectUnit()
```csharp
public CreatureSelectUnit()
```
Default constructor.

## Fields
### \_creatureId
```csharp
private long _creatureId
```
The abnormality contained in this door.

#### Field Value
**Type:** System.Int64

### CreditCreatureFrame
```csharp
public GameObject CreditCreatureFrame
```
The frame for a backer abnormality.


#### Field Value
**Type:** UnityEngine.GameObject

### DoorAnim
```csharp
public Animator DoorAnim
```
Animator that plays the `DoorOpen.anim` animation when the UI is opened, probably.

#### Field Value
**Type:** UnityEngine.Animator

### DullAnimCTRL
```csharp
public Animator DullAnimCTRL
```
Animation controller that controls the doors shaking, probably.

#### Field Value
**Type:** UnityEngine.Animator

### DullTimer
```csharp
private Timer DullTimer
```
Timer which tells the animator how often to shake, probably.

#### Field Value
**Type:** Global.Timer

### EmptyId
```csharp
public const long EmptyId = -1
```
The ID representing no abnormality.

#### Field Value
**Type:** System.Int64

### Frame
```csharp
public Image[] Frame
```
A set of images used for switching between the backer and normal frames, depending on the abnormality.

#### Field Value
**Type:** UnityEngine.UI.Image[]

### IdText
```csharp
public Text IdText
```
The name or ID number of the abnormality, as displayed on the door.

#### Field Value
**Type:** UnityEngine.UI.Text

### isChanging
```csharp
private bool isChanging
```
Flag indicating a re-extraction is happening.

#### Field Value
**Type:** System.Boolean

### metaInfo
```csharp
private CreatureTypeInfo metaInfo
```
The information (see [`CreatureTypeInfo`](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo)) of the abnormality in this door.

#### Field Value
**Type:** Global.CreatureTypeInfo

### NormalCreatureFrame
```csharp
public GameObject NormalCreatureFrame
```
The frame for a normal (non-backer) abnormality.

#### Field Value
**Type:** UnityEngine.GameObject

### pointer
```csharp
private bool pointer
```
Flag indicating the door is being hovered over (speeds up the shaking).

#### Field Value
**Type:** System.Boolean

### PositionPivot
```csharp
public RectTransform PositionPivot
```
Represents some pivot on this game object...

#### Field Value
**Type:** UnityEngine.RectTransform

### RootObject
```csharp
public GameObject RootObject
```
This door.

#### Field Value
**Type:** UnityEngine.GameObject

### savedId
```csharp
private long savedId
```
The ID of an abnormality to switch in after the changing animation plays.

#### Field Value
**Type:** System.Int64

### TransAnim
```csharp
public Animator TransAnim
```
This door, as an animator, and what controls transition animations.

#### Field Value
**Type:** UnityEngine.Animator

### TransitionTime
```csharp
public float TransitionTime
```
Unused?

#### Field Value
**Type:** System.Single

### TransitionTimer
```csharp
private Timer TransitionTimer
```
Unused?

#### Field Value
**Type:** Global.Timer

### TransSelected
```csharp
public bool TransSelected
```
Flag indicating that this door has been selected and is transitioning to the next screen.

#### Field Value
**Type:** System.Boolean

## Properties
### CreatureID
```csharp
public long CreatureID { get; }
```
Get-only property for `_creatureID`.

#### Property Value
**Type:** System.Int64

### DullFreq
```csharp
private float DullFreq { get; }
```
The frequency of the shaking animation.

#### Property Value
**Type:** System.Single

### RectTransform
```csharp
private RectTransform RectTransform { get; }
```
Unused?

#### Property Value
**Type:** UnityEngine.RectTransform

## Methods
### AgentReset()
```csharp
public void AgentReset()
```
Unimplemented.

### AnimatorEventInit()
```csharp
public void AnimatorEventInit()
```
Unimplemented.

### AttackCalled(int)
```csharp
public void AttackCalled(int i)
```
Unimplemented.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()
```csharp
public void AttackDamageTimeCalled()
```
Unimplemented.

### CreatureAnimCall(int, CreatureBase)
```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```
Unimplemented.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### FixedUpdate()
```csharp
public void FixedUpdate()
```
Runs the shaking animation timer, and shakes if needed. Probably.

### GetName()
```csharp
private string GetName()
```
Returns the name (or ID number) of the abnormality in this door.

(Ex: "One Sin and Hundreds of Good Deeds" or "O-03-03".)

#### Returns
**Type:** System.String

### GetText()
```csharp
public string GetText()
```
Returns the preview text of the abnormality in the door.

(Ex: "It feeds on the “evil” that seeps out during conversations between people.")

#### Returns
**Type:** System.String

### Init(long)
```csharp
public void Init(long creatureId)
```
Initializes this door to hold the abnormality with ID `creatureId`.

###### Details
If the ID belongs to [Plague Doctor](/api/WhiteNightSpace/PlagueDoctor) and [WhiteNight](/api/WhiteNightSpace/DeathAngel) has advented, WhiteNight's ID is used instead.

If the given ID is no abnormality (`-1L`), disables this door.

Otherwise, enables this door (if not already enabled) and fills the abnormality info (`metaInfo`), name (`IdText`), and frame type (backer or normal) with the appropriate information. Also, resets the flag `TransSelected` and updates the shaking animation.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creatureId` | `System.Int64` | The ID of the abnormality in the door. |

### LateInit()
```csharp
private void LateInit()
```
If there is a saved ID (other than `-1L`), when this is called it will initialize this door with the saved ID, then set the saved ID to `-1L`. This is called by [`CreatureSelectUnit::OnChangeComplete`](/api/CreatureSelect/CreatureSelectUnit#onchangecomplete) at the end of the animation `CreatureChange.anim`, which is started by [`CreatureSelectUnit::OnChange`](/api/CreatureSelect/CreatureSelectUnit#onchange).

### OnCalled()
```csharp
public void OnCalled()
```
Does nothing.

### OnCalled(int)
```csharp
public void OnCalled(int i)
```
Unimplemented.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnChange()
```csharp
public void OnChange()
```
Sets the `isChanging` flag to prevent further interaction, then starts the changing animation (`CreatureChange.anim`). This animation calls [`CreatureSelectUnit::OnChangeComplete`](/api/CreatureSelect/CreatureSelectUnit#onchangecomplete) when it finishes.

### OnChangeComplete()
```csharp
public void OnChangeComplete()
```
Resets the flag `isChanging` and initializes the door ([`CreatureSelectUnit::LateInit`](/api/CreatureSelect/CreatureSelectUnit#lateinit)) with the saved abnormality ID.

### OnEnter()
```csharp
private void OnEnter()
```
Script for when this door is hovered over. Plays an animation on the door (`Enter.anim`) and informs the [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) via [`CreatureSelectUI::OnEnterUnit(CreatureSelectUnit)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#onenterunitcreatureselectunit).
### OnExit()
```csharp
private void OnExit()
```
Script for when this door is no longer hovered over. Plays an animation on the door (`Exit_Normal.anim`) and informs the [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) via [`CreatureSelectUI::OnExitUnit(CreatureSelectUnit)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#onexitunitcreatureselectunit).

### OnPointerClick()
```csharp
public void OnPointerClick()
```
Behaviour when this door is clicked, usually to select this abnormality.

If this door has not already been selected and the [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) is still interactable, sets the `TransSelected` flag, plays an animation (`OnClick2.anim`), and informs the selection UI via [`CreatureSelectUI::OnClickUnit(CreatureSelectUnit)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#onclickunitcreatureselectunit).

### OnPointerEnter()
```csharp
public void OnPointerEnter()
```
Event handler for when the pointer hovers over this door. Calls [`CreatureSelectUnit::OnEnter`](/api/CreatureSelect/CreatureSelectUnit#onenter), which plays an animation on the door and informs the [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) via [`CreatureSelectUI::OnEnterUnit(CreatureSelectUnit)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#onenterunitcreatureselectunit).

### OnPointerExit()
```csharp
public void OnPointerExit()
```
Event handler for when the pointer stops hovering over this door. Calls [`CreatureSelectUnit::OnExit`](/api/CreatureSelect/CreatureSelectUnit#onexit), which plays an animation on the door and informs the [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) via [`CreatureSelectUI::OnExitUnit(CreatureSelectUnit)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#onexitunitcreatureselectunit).

### ResetPos()
```csharp
private void ResetPos()
```
Unused.

### SetDisabled()
```csharp
public void SetDisabled()
```
Disables this door as a game object.

### SetEnabled()
```csharp
public void SetEnabled()
```
Enables this door as a game object.

### SimpleReset()
```csharp
public void SimpleReset()
```
Unimplemented.

### SoundMake(string)
```csharp
public void SoundMake(string src)
```
Unimplemented.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### Start()
```csharp
public void Start()
```
Called before the first frame. Calls [`CreatureSelectUnit::OnExit`](/api/CreatureSelect/CreatureSelectUnit#onexit), which enables the door frame and plays the `Exit_Normal.anim` animation (for when the door is not being hovered over).

### Update()
```csharp
public void Update()
```
Does nothing.

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)











