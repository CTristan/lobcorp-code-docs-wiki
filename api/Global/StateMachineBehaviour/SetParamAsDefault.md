---
uid: Global.SetParamAsDefault
canonical_path: /api/Global/StateMachineBehaviour/SetParamAsDefault
---

# Class SetParamAsDefault

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SetParamAsDefault : StateMachineBehaviour
```

Sets the given parameter to the default value on entry.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → [StateMachineBehaviour](#) → SetParamAsDefault

## Inherited Members
[OnStateUpdate(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateExit(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMove(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateEnter(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateUpdate(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateExit(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMove(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [Internal_CreateScriptableObject(ScriptableObject)](#), [SetDirty()](#), [INTERNAL_CALL_SetDirty(ScriptableObject)](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstanceFromType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SetParamAsDefault()

```csharp
public SetParamAsDefault()
```

## Fields

### list

```csharp
private List<SetParamAsDefault.ParamItem> list
```

#### Field Value

**Type:** System.Collections.Generic.List{SetParamAsDefault.ParamItem}

## Methods

### Init(Animator)

```csharp
public void Init(Animator animator)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |

### OnStateEnter(Animator, AnimatorStateInfo, int)

```csharp
public override void OnStateEnter(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` |  |
| `layerIndex` | `System.Int32` |  |
