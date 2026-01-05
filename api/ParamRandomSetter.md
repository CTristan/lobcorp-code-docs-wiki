# Class ParamRandomSetter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ParamRandomSetter : StateMachineBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → [StateMachineBehaviour](#) → ParamRandomSetter

## Inherited Members
[OnStateUpdate(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMove(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateEnter(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateUpdate(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateExit(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMove(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateIK(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineEnter(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [OnStateMachineExit(Animator, int, AnimatorControllerPlayable)](https://learn.microsoft.com/dotnet/api/system.int32), [SetDirty()](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ParamRandomSetter()

```csharp
public ParamRandomSetter()
```

## Fields

### onStateEnterBool

```csharp
public List<ParamRandomSetter.BoolParamData> onStateEnterBool
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.BoolParamData}

### onStateEnterFloat

```csharp
public List<ParamRandomSetter.FloatParamData> onStateEnterFloat
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.FloatParamData}

### onStateEnterInt

```csharp
public List<ParamRandomSetter.IntParamData> onStateEnterInt
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.IntParamData}

### onStateExitBool

```csharp
public List<ParamRandomSetter.BoolParamData> onStateExitBool
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.BoolParamData}

### onStateExitFloat

```csharp
public List<ParamRandomSetter.FloatParamData> onStateExitFloat
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.FloatParamData}

### onStateExitInt

```csharp
public List<ParamRandomSetter.IntParamData> onStateExitInt
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.IntParamData}

### onStateMoveFloat

```csharp
public List<ParamRandomSetter.FloatParamData> onStateMoveFloat
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.FloatParamData}

### onStateMoveInt

```csharp
public List<ParamRandomSetter.IntParamData> onStateMoveInt
```

#### Field Value

**Type:** System.Collections.Generic.List{ParamRandomSetter.IntParamData}

## Methods

### OnStateEnter(Animator, AnimatorStateInfo, int)

```csharp
public override void OnStateEnter(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` |  |
| `layerIndex` | `System.Int32` |  |

### OnStateExit(Animator, AnimatorStateInfo, int)

```csharp
public override void OnStateExit(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `stateInfo` | `UnityEngine.AnimatorStateInfo` |  |
| `layerIndex` | `System.Int32` |  |
