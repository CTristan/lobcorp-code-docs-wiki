# Class SkeletonRagdoll

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity) . [Modules](/api/Spine-Unity-Modules)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(SkeletonRenderer))]
public class SkeletonRagdoll : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SkeletonRagdoll

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonRagdoll()

```csharp
public SkeletonRagdoll()
```

## Fields

### applyOnStart

```csharp
[Header("Parameters")]
public bool applyOnStart
```

#### Field Value

**Type:** System.Boolean

### colliderLayer

```csharp
[Tooltip("The layer assigned to all of the rigidbody parts.")]
public int colliderLayer
```

#### Field Value

**Type:** System.Int32

### disableIK

```csharp
[Tooltip("Warning!  You will have to re-enable and tune mix values manually if attempting to remove the ragdoll system.")]
public bool disableIK
```

#### Field Value

**Type:** System.Boolean

### disableOtherConstraints

```csharp
public bool disableOtherConstraints
```

#### Field Value

**Type:** System.Boolean

### enableJointCollision

```csharp
[Tooltip("Enable Collision between adjacent ragdoll elements (IE: Neck and Head)")]
public bool enableJointCollision
```

#### Field Value

**Type:** System.Boolean

### massFalloffFactor

```csharp
[Tooltip("If your ragdoll seems unstable or uneffected by limits, try lowering this value.")]
[Range(0.01, 1)]
public float massFalloffFactor
```

#### Field Value

**Type:** System.Single

### mix

```csharp
[Range(0, 1)]
public float mix
```

#### Field Value

**Type:** System.Single

### pinStartBone

```csharp
[Space(18)]
[Tooltip("Set RootRigidbody IsKinematic to true when Apply is called.")]
public bool pinStartBone
```

#### Field Value

**Type:** System.Boolean

### rootMass

```csharp
public float rootMass
```

#### Field Value

**Type:** System.Single

### rotationLimit

```csharp
[Tooltip("Default rotational limit value.  Min is negative this value, Max is this value.")]
public float rotationLimit
```

#### Field Value

**Type:** System.Single

### startingBoneName

```csharp
[Header("Hierarchy")]
[SpineBone("", "", true)]
public string startingBoneName
```

#### Field Value

**Type:** System.String

### stopBoneNames

```csharp
[SpineBone("", "", true)]
public List<string> stopBoneNames
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### thickness

```csharp
[Tooltip("If no BoundingBox Attachment is attached to a bone, this becomes the default Width or Radius of a Bone's ragdoll Rigidbody")]
public float thickness
```

#### Field Value

**Type:** System.Single

### useGravity

```csharp
public bool useGravity
```

#### Field Value

**Type:** System.Boolean

## Properties

### EstimatedSkeletonPosition

```csharp
public Vector3 EstimatedSkeletonPosition { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### IsActive

```csharp
public bool IsActive { get; }
```

#### Property Value

**Type:** System.Boolean

### RigidbodyArray

```csharp
public Rigidbody[] RigidbodyArray { get; }
```

#### Property Value

**Type:** UnityEngine.Rigidbody[]

### RootOffset

```csharp
public Vector3 RootOffset { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### RootRigidbody

```csharp
public Rigidbody RootRigidbody { get; }
```

#### Property Value

**Type:** UnityEngine.Rigidbody

### StartingBone

```csharp
public Bone StartingBone { get; }
```

#### Property Value

**Type:** Spine.Bone

## Methods

### Apply()

```csharp
public void Apply()
```

### GetRigidbody(string)

```csharp
public Rigidbody GetRigidbody(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Rigidbody

### Remove()

```csharp
public void Remove()
```

### SetSkeletonPosition(Vector3)

```csharp
public void SetSkeletonPosition(Vector3 worldPosition)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worldPosition` | `UnityEngine.Vector3` |  |

### SmoothMix(float, float)

```csharp
public Coroutine SmoothMix(float target, float duration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Single` |  |
| `duration` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Coroutine
