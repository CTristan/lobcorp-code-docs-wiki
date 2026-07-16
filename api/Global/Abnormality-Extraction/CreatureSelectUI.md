---
title: CreatureSelectUI
description: 
published: true
date: 2026-07-16T17:18:30.612Z
tags: 
editor: markdown
dateCreated: 2026-07-08T14:03:29.725Z
---

# Class CreatureSelectUI
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSelectUI : MonoBehaviour, IAnimatorEventCalled
```

The abnormality selection UI.

See [Abnormality Extraction](/abnormality-extraction) for a description of the abnormality extraction system.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreatureSelectUI

## Implements
[IAnimatorEventCalled](/api/Global/Animation/IAnimatorEventCalled)

## Fields
### \_instance
```csharp
private static CreatureSelectUI _instance
```
The one instance of this class, for the singleton pattern.

#### Field Value
**Type:** Global.CreatureSelectUI

### \_reExtracted
```csharp
private bool _reExtracted
```
A flag tracking whether the player has re-extracted already during this selection.


#### Field Value
**Type:** System.Boolean

### \_skip
```csharp
private bool _skip
```
Unused.

#### Field Value
**Type:** System.Boolean

### \_tiperethRunned
```csharp
private bool _tiperethRunned
```
A flag tracking whether we have already done the first extraction, on days where we have two (Days 21-24 and 46-49).

#### Field Value
**Type:** System.Boolean

### Block
```csharp
public UIController Block
```
The grey filter applied to the background when a door is being hovered over.

#### Field Value
**Type:** Global.UIController

### clip
```csharp
public AudioClip clip
```
The background music for selection ([Tilarids - never frozen bottom flows](https://www.youtube.com/watch?v=UPvNk9t36WM)).

#### Field Value
**Type:** UnityEngine.AudioClip

### clipSaved
```csharp
private AudioClip clipSaved
```
Unused.

#### Field Value
**Type:** UnityEngine.AudioClip

### CurrentCreatures
```csharp
private List<long> CurrentCreatures
```
The abnormalities currently offered as the selection.

#### Field Value
**Type:** System.Collections.Generic.List{System.Int64}

### deathangel
```csharp
public const long deathangel = 100015
```
Abnormality ID for [WhiteNight](/api/WhiteNightSpace/DeathAngel).

#### Field Value
**Type:** System.Int64

### effectRunned
```csharp
private bool effectRunned
```
A flag tracking whether a door has already been chosen, to make the UI non-interactable.

#### Field Value
**Type:** System.Boolean

### EffectTimer
```csharp
private Timer EffectTimer
```
Unused.

#### Field Value
**Type:** Global.Timer

### FadeoutEffectTimer
```csharp
private Timer FadeoutEffectTimer
```
Controls the music fading out after an abnormality is selected.

#### Field Value
**Type:** Global.Timer

### filter
```csharp
public CameraFilterPack_TV_80 filter
```
The visual filter applied to the screen.

#### Field Value
**Type:** Global.CameraFilterPack_TV_80

### GlobalControlAnim
```csharp
[Header("Effect")]
public Animator GlobalControlAnim
```
The animator for this UI.

#### Field Value
**Type:** UnityEngine.Animator

### Index_Normal
```csharp
[Header("Index")]
public RectTransform Index_Normal
```
A transform, used as the parent for doors that are not currently selected.

#### Field Value
**Type:** UnityEngine.RectTransform

### Index_Select
```csharp
public RectTransform Index_Select
```
A transform, used as the parent for selected doors.

#### Field Value
**Type:** UnityEngine.RectTransform

### plagueDoctor
```csharp
public const long plagueDoctor = 100014
```
Abnormality ID of [Plague Doctor](/api/WhiteNightSpace/PlagueDoctor).

#### Field Value
**Type:** System.Int64

### reExtractController
```csharp
[Header("ReExtract")]
public UIController reExtractController
```
The UI element for the re-extraction button.
#### Field Value
**Type:** Global.UIController

### RootObject
```csharp
public GameObject RootObject
```
A reference to the object holding the UI and script (Canvas).

#### Field Value
**Type:** UnityEngine.GameObject

### SelectEndDay
```csharp
public const int SelectEndDay = 51
```
Incorrectly, the first day of the unlimited mode. (Should be 50, since days are zero-indexed.)

#### Field Value
**Type:** System.Int32

### SelectStartDay
```csharp
public const int SelectStartDay = 0
```
The first day for selection.

#### Field Value
**Type:** System.Int32

### startVolume
```csharp
private float startVolume
```
The initial volume of the background music, for the fading effect. Defaults to 1f, and is set to the current background music volume when the effect starts.

#### Field Value
**Type:** System.Single

### TextBoxController
```csharp
[Header("TextBox")]
public UIController TextBoxController
```
The UI element containing the abnormality preview text.
#### Field Value
**Type:** Global.UIController

### TextBoxText
```csharp
public Text TextBoxText
```
The abnormality preview text of the currently viewed abnormality.

#### Field Value
**Type:** UnityEngine.UI.Text

### threshold
```csharp
private int threshold
```
A counter preventing infinite recursion when checking [Yin](/api/Global/Abnormalities/Yin-and-Yang/Yin/Yin) and [Yang](/api/Global/Abnormalities/Yin-and-Yang/Yang/Yang)'s special condition.

#### Field Value
**Type:** System.Int32

### Units
```csharp
[Header("UI")]
public CreatureSelectUnit[] Units
```
The three doors which contain the abnormality selection.

#### Field Value
**Type:** CreatureSelect.CreatureSelectUnit[]

### yang
```csharp
public const long yang = 300109
```
Abnormality ID of [Yang](/api/Global/Abnormalities/Yin-and-Yang/Yang/Yang).

#### Field Value
**Type:** System.Int64

### yin
```csharp
public const long yin = 100104
```
Abnormlity ID of [Yin](/api/Global/Abnormalities/Yin-and-Yang/Yin/Yin).

#### Field Value
**Type:** System.Int64

## Properties
### Day
```csharp
private int Day { get; }
```
The current day as reported by [PlayerModel](/api/Global/Global-Data/PlayerModel).

#### Property Value
**Type:** System.Int32

### instance
```csharp
public static CreatureSelectUI instance { get; }
```
A reference to \_instance, and the single instance of this UI script.

#### Property Value
**Type:** Global.CreatureSelectUI

### IsEnabled
```csharp
public bool IsEnabled { get; private set; }
```
Flag which is true if the game object is active.

#### Property Value
**Type:** System.Boolean

### ReExtractResearchCompleted
```csharp
private bool ReExtractResearchCompleted { get; }
```
Flag which is true if the re-extraction research has been completed.

#### Property Value
**Type:** System.Boolean

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

### Awake()
```csharp
private void Awake()
```
Called when the scene containing this object starts. Disables the abnormality preview textbox and makes this instance the definitive singleton instance.

### CheckCreatureExisting(long)
```csharp
public static bool CheckCreatureExisting(long targetId)
```
Returns true if the abnormality with ID `targetId` is currently in the facility.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetId` | `System.Int64` | The ID of the abnormality to check |

#### Returns
**Type:** System.Boolean

### CheckKitGeneration()
```csharp
private void CheckKitGeneration()
```
Sets the flag `GenKit` on [CreatureGenerateInfoManager](/api/CreatureGenerate/CreatureGenerateInfoManager), which tracks if today should give a tool abnormality, as follows:
- True when the day is Day 1-20 and day is 4 modulo 5 (every 5 days, starting on day 4)
- True when the day is Day 21 or Day 23 and this is the second extraction of the day
- False when the day is Day 21-25 but doesn't meet the previous criteria
- True when the day is Day 26-50 and day is 4 modulo 5 (every 5 days, starting on day 29)
- False when there are no more tool abnormalities, regardless of any previous conditions (though this shouldn't happen in normal gameplay)

### CheckUIActivateCondition()
```csharp
private bool CheckUIActivateCondition()
```
Returns true when there is supposed to be an extraction today.

#### Returns
**Type:** System.Boolean

- False if the player is in a Keter gameover
- False if day < 0 (this also queues [Big Bird](/api/Global/Abnormalities/Big-Bird/BigBird) to the waiting abnormalities)
- False if this day never has a selection:
	- Every fifth day, except Day 15, Day 30, and Day 40
 	- Every day 52 or later
 	- Every day 51 or later
- True on Day 19 if Safety or Training has open level 3 (and so can accept a new abnormality), false otherwise.
- True on Day 34 if Welfare or Disciplinary has open level 3 (and so can accept a new abnormality), false otherwise.
- :interrobang: True on Day 34 if Extraction or Records has open level 3, false otherwise (this branch can never be reached).
- False if there's already enough abnormalities in the queue as determined by [`PlayerModel::IsWaitingCreatureExist`](/api/Global/Global-Data/PlayerModel), regardless of previous conditions.
- False if the player is viewing the True Ending ([`GlobalGameManager.gameMode`](/api/Global/Global-Data/GlobalGameManager) is [`GameMode.HIDDEN`](/api/Global/Global-Data/GameMode)), regardless of previous conditions.

### CheckYinAndYang()
```csharp
private void CheckYinAndYang()
```
Replaces today's selection with only [Yang](/api/Global/Abnormalities/Yin-and-Yang/Yang/Yang) when [Yin](/api/Global/Abnormalities/Yin-and-Yang/Yin/Yin) is present in the facility and today is a tool abnormality day.
<br></br>
###### Details
Increments the counter `threshold`, used to track recursion. If `threshold` reaches 3, immediately returns. This cannot happen during normal gameplay.

When Yin and Yang are both present, or Yin is not present, returns immediately, since the conditions for the interaction have not been met.

:interrobang: On Day 49 or later only:
- :interrobang: If there are 0 or 1 abnormalities in the current selection, call `GetCreatureList(false)`, which calls this code at the end. Effectively, if not enough abnormalities were found, try again without resetting their current contents. Since this doesn't alter the available abnormalities, this would always loop 3 times and stop. This code cannot normally be called because there are always enough available abnormalities.
- If there are at least two abnormalities in the current selection, :interrobang:remove Yin from the current selection. Yin is already in the facility, so it cannot be in the current selection; this code always does nothing.

On Day 48 and earlier, if today is a tool day (the flag `GenKit` is set on [CreatureGenerateInfoManager](/api/CreatureGenerate/CreatureGenerateInfoManager)), and Yang is not already queued, clear the current selection and add back Yang.

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

### FadeoutEffect(float)
```csharp
public void FadeoutEffect(float time = 3)
```
Fades the music out over `time` seconds.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` | How many seconds to fade out the music <!-- verify--> |

### FixedUpdate()
```csharp
private void FixedUpdate()
```
Updates the background music volume if the music is fading out.

### GetCreatureList(bool)
```csharp
private void GetCreatureList(bool setEmpty = true)
```

Populates `CurrentCreatures` with the abnormality selection of the day.

###### Details
Clears any pre-existing data in `CurrentCreatures`.

Calculates the effective day for the abnormality selection; see [`CreatureGenerateInfoManager::CalculateDay`](/api/CreatureGenerate/CreatureGenerateInfoManager) for when this is NOT the same as the current day.

Checks if today is a tool abnormality day using `CheckKitGeneration`.

Updates the available abnormality lists ([`CreatureGenerateInfoManager::CalculateDay`](/api/CreatureGenerate/CreatureGenerateInfoManager)).

Resets the doors with `SetSlotInit(setEmpty)`.

Gets a `list` of three random abnormalities, or else `null` if there are no abnormalities today ([`CreatureSelectUI::GetCreature`](/api/CreatureGenerate/CreatureSelectUI)).

If `list` is `null`, log an error and instead replace it with a new list of all non-tool abnormalities that are not in the facility, removing [WhiteNight](/api/WhiteNightSpace/DeathAngel) and [PlagueDoctor](/api/WhiteNightSpace/PlagueDoctor) together. :bangbang: This incorrectly ignores abnormalities which are 'used' but not in the facility yet, and so allows for an abnormality previously selected today to be offered again. If at the end the list is empty, log another error and return. 

Randomly add an abnormality from `list` to `list3` three times. If there are not three abnormalities in the list, but there was at least one, skip the rest and continue as normal (e.g., if there is only one abnormality in the list, continue with only that abnormality). :interrobang: If the list is empty, and `list3` is also empty, instead choose from all abnormalities except the ones in the facility. This cannot run since `list` cannot be empty at the start, and if it becomes empty `list3` would not be empty.

Finally, add `list3` to `CurrentCreatures` and run `CheckYinAndYang`.



#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `setEmpty` | `System.Boolean` | Flag determining if doors should be initialized to `-1L` |

### Init()
```csharp
public void Init()
```
Initializes the UI and populates the doors with the abnormality selection of the day.


###### Details
Activates or deactivates the re-extraction UI.

Checks if a selection should be made today (`CheckUIActivateCondition`), otherwise ends the selection phase (`OnUIActionEnd`).

Resets `effectRunned`, which tracks if a door has been chosen.

Enables the visual `filter` and all of the doors (`Units`).

Plays the opening animation.

Gets the selection for today. If there is one abnormality, only enables the middle door and initializes it. If there are no abnormalities, :interrobang: incorrectly initializes the selection with a random three from all abnormalities except those in the facility. Otherwise, initializes all three doors in a random order. (:question: If there are ever two abnormalities, this code behaves incorrectly.)

Starts the background music.

:question: If there are duplicate abnormalities, disable all but the first such abnormality. This does not happen in normal gameplay.

Displays the re-extraction UI if the research is completed and the player has not re-extracted yet.

### IsInteractable()
```csharp
public bool IsInteractable()
```


#### Returns
**Type:** System.Boolean

### OnCalled()
```csharp
public void OnCalled()
```
Called when the UI closing animation finishes (UIClose.anim), and either starts the next extraction if applicable, or else ends the selection phase.

###### Details
On Day 21-24 and :question: Day 46-50, if `_tiperethRunned` has not been set yet, set it and start the next extraction with `Init`. Also, reset the `_reExtracted` flag so the player can re-extract on the second selection.

On every other day, or if this was the second extraction, run the animation GlobalClose (`GlobalClose.anim`), fade in the story music over the next two seconds, and move to the story screen. GlobalClose has a callback to `OnCalled(int)` which ends the selection phase.

### OnCalled(int)
```csharp
public void OnCalled(int i)
```
Ends the selection phase. See `OnUIActionEnd`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` | Ignored |

### OnClickReExtract()
```csharp
public void OnClickReExtract()
```
Re-extracts the abnormalities when the button is clicked.

###### Details
Called when the re-extraction button is clicked.

If the research has not been completed, returns immediately.

Gets a new selection without clearing the old selection; this is to let the doors play their animation without changing until after the animation is finished. See [`CreatureSelectUnit::OnChange`](/api/CreatureSelect/CreatureSelectUnit).

If there is one abnormality, only enables the middle door and initializes it. If there are no abnormalities, :interrobang: incorrectly initializes the selection with a random three from all abnormalities except those in the facility. Otherwise, initializes all three doors in a random order. (:question: If there are ever two abnormalities, this code behaves incorrectly.)

:question: If there are duplicate abnormalities, disable all but the first such abnormality. This does not happen in normal gameplay.

:question: Displays the re-extraction UI if the research is completed and the player has not re-extracted yet. This is never true normally.

### OnClickUnit(CreatureSelectUnit)
```csharp
public void OnClickUnit(CreatureSelectUnit unit)
```
Queues the selected abnormality and begins closing the UI.

###### Details
Called by [`CreatureSelectUnit::OnPointerClick`](/api/CreatureSelect/CreatureSelectUnit).

Sets the `effectRunned` flag to prevent further selection.

Queues the selected abno, or [Plague Doctor](/api/WhiteNightSpace/PlagueDoctor) if [WhiteNight](/api/WhiteNightSpace/DeathAngel) was selected.

Informs [`CreatureGenerateInfoManager`](/api/CreatureGenerate/CreatureGenerateInfoManager) that this abnormality should be considered used. :question: This should prevent a duplicate abnormality from being chosen, but it doesn't. I am not sure where the bug is.

Sets the UI animation to Close (`UIClose.anim`) which contains a callback to `OnCalled()` to possibly start a second extraction if needed, or else just close the UI.

Starts a timer to fade out the music with `FadeoutEffect`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` | The selected door. |

### OnEnterUnit(CreatureSelectUnit)
```csharp
public void OnEnterUnit(CreatureSelectUnit unit)
```
Updates the UI to reflect that a door is being hovered over.

###### Details
Called by [`CreatureSelectUnit::OnEnter`](/api/CreatureSelect/CreatureSelectUnit).

If a door has already been selected, return immediately.

Show the grey filter over everything in the background.

Populate the text box with the preview text of the abnormality in `unit`.

Re-parent the doors' transforms so all but the selected unit are in the background.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` | The door hovered over. |

### OnExitUnit(CreatureSelectUnit)
```csharp
public void OnExitUnit(CreatureSelectUnit unit)
```
Updates the UI to reflect that a door is no longer being hovered over.

###### Details
Called by [`CreatureSelectUnit::OnExit`](/api/CreatureSelect/CreatureSelectUnit).

Hide the grey filter over everything in the background.

Hide the preview text box.

If none of the doors have been selected yet, reparent all doors' transforms to be in the background.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` | The door no longer hovered over. |

### OnUIActionEnd()
```csharp
public void OnUIActionEnd()
```
Closes the UI.
###### Details
Disable the UI, save Etc data if the file exists ([`GlobalGameManager::SaveEtcData`](/api/Global/Global-Data/GlobalGameManager)), and start the story.

### SetSlotInit(bool)
```csharp
private void SetSlotInit(bool setEmpty = true)
```
Clears the creatures in the selection, and if `setEmpty` is true, also initializes all units to the abnormality `-1L`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `setEmpty` | `System.Boolean` | Flag which decides if the doors should be initialized to `-1L` |

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
private void Start()
```
Called before the first frame of the scene. Resets most flags and loads Etc data before initializing the UI.

###### Details
Resets:
- `tiperethRunned`, which tracks if this is the first or second selection today
- `reExtracted`, which tracks if re-extracting is still permitted
- `threshold`, used to prevent infinite recursion from `CheckYinAndYang`

Also loads the Etc save file, mostly because it contains the waiting abnormalities. See also [`GlobalGameManager::LoadEtcFile`](/api/Global/Global-Data/GlobalGameManager).

Then continues to `Init`.

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









