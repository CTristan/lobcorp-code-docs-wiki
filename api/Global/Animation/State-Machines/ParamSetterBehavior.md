---
title: ParamSetterBehavior
description: 
published: true
date: 2026-08-01T01:51:42.426Z
tags: 
editor: markdown
dateCreated: 2026-07-08T14:52:07.513Z
---

# Class ParamSetterBehavior
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ParamSetterBehavior : StateMachineBehaviour
```
Custom state machine behaviour which sets a list of parameters upon entry and exit, specified by the Animator using this state.

For example, the clerk animator (`Resources/animators/workeranimators/OfficerAnimator.controller`) resets the `PanicStart` parameter to `false` after entering the `PanicReady` state.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → [StateMachineBehaviour](#) → ParamSetterBehavior

## Fields
### onStateEnter
```csharp
public List<ParamSetterBehavior.ParamData> onStateEnter
```
The list of integer parameters to modify when the state is entered, as `ParamData` (name and integer value).

#### Field Value
**Type:** System.Collections.Generic.List{ParamSetterBehavior.ParamData}

### onStateEnterBool
```csharp
public List<ParamSetterBehavior.BoolParamData> onStateEnterBool
```
The list of boolean parameters to modify when the state is entered, as `BoolParamData` (name and bool value).

#### Field Value
**Type:** System.Collections.Generic.List{ParamSetterBehavior.BoolParamData}

### onStateExit
```csharp
public List<ParamSetterBehavior.ParamData> onStateExit
```
The list of integer parameters to modify when the state is exited, as `ParamData` (name and integer value).

#### Field Value
**Type:** System.Collections.Generic.List{ParamSetterBehavior.ParamData}

### onStateExitBool
```csharp
public List<ParamSetterBehavior.BoolParamData> onStateExitBool
```
The list of boolean parameters to modify when the state is exited, as `BoolParamData` (name and bool value).

#### Field Value
**Type:** System.Collections.Generic.List{ParamSetterBehavior.BoolParamData}

### onStateMove
```csharp
public List<ParamSetterBehavior.ParamData> onStateMove
```
Unused.

#### Field Value
**Type:** System.Collections.Generic.List{ParamSetterBehavior.ParamData}

## Methods
### OnStateEnter(Animator, AnimatorStateInfo, int)
```csharp
public override void OnStateEnter(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```
For each integer parameter `ParamData` in `onStateEnter` and each boolean parameter `BoolParamData` in `onStateEnterBool`, sets that parameter to the stored value.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` | The animator to set the parameters of. |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` | Unused. |
| `layerIndex` | `System.Int32` | Unused. |

### OnStateExit(Animator, AnimatorStateInfo, int)
```csharp
public override void OnStateExit(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```
For each integer parameter `ParamData` in `onStateExit` and each boolean parameter `BoolParamData` in `onStateExitBool`, sets that parameter to the stored value.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` | The animator to set the parameters of. |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` | Unused. |
| `layerIndex` | `System.Int32` | Unused. |

### OnStateUpdate(Animator, AnimatorStateInfo, int)
```csharp
public override void OnStateUpdate(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` |  |
| `layerIndex` | `System.Int32` |  |

## Inherited Members
[OnStateMove(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateEnter(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateUpdate(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateExit(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMove(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [Internal_CreateScriptableObject(ScriptableObject)](#), [SetDirty()](#), [INTERNAL_CALL_SetDirty(ScriptableObject)](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstanceFromType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







