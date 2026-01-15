---
uid: Spine.Unity.Modules.SkeletonRagdoll2D
canonical_path: /api/Spine/Unity/Modules/SkeletonRagdoll2D
---

# Class SkeletonRagdoll2D

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity) . [Modules](/api/Spine/Unity/Modules)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(SkeletonRenderer))]
public class SkeletonRagdoll2D : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SkeletonRagdoll2D

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonRagdoll2D()

```csharp
public SkeletonRagdoll2D()
```

## Fields

### applyOnStart

```csharp
[Header("Parameters")]
public bool applyOnStart
```

#### Field Value

**Type:** System.Boolean

### boneTable

```csharp
private Dictionary<Bone, Transform> boneTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{Spine.Bone,UnityEngine.Transform}

### colliderLayer

```csharp
[Tooltip("The layer assigned to all of the rigidbody parts.")]
[SkeletonRagdoll.LayerField]
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

### gravityScale

```csharp
public float gravityScale
```

#### Field Value

**Type:** System.Single

### isActive

```csharp
private bool isActive
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

### parentSpaceHelper

```csharp
private static Transform parentSpaceHelper
```

#### Field Value

**Type:** UnityEngine.Transform

### pinStartBone

```csharp
[Space]
[Tooltip("Set RootRigidbody IsKinematic to true when Apply is called.")]
public bool pinStartBone
```

#### Field Value

**Type:** System.Boolean

### ragdollRoot

```csharp
private Transform ragdollRoot
```

#### Field Value

**Type:** UnityEngine.Transform

### rootMass

```csharp
public float rootMass
```

#### Field Value

**Type:** System.Single

### rootOffset

```csharp
private Vector2 rootOffset
```

#### Field Value

**Type:** UnityEngine.Vector2

### rotationLimit

```csharp
[Tooltip("Default rotational limit value.  Min is negative this value, Max is this value.")]
public float rotationLimit
```

#### Field Value

**Type:** System.Single

### skeleton

```csharp
private Skeleton skeleton
```

#### Field Value

**Type:** Spine.Skeleton

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

### targetSkeletonComponent

```csharp
private ISkeletonAnimation targetSkeletonComponent
```

#### Field Value

**Type:** Spine.Unity.ISkeletonAnimation

### thickness

```csharp
[Tooltip("If no BoundingBox Attachment is attached to a bone, this becomes the default Width or Radius of a Bone's ragdoll Rigidbody")]
public float thickness
```

#### Field Value

**Type:** System.Single

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
public Rigidbody2D[] RigidbodyArray { get; }
```

#### Property Value

**Type:** UnityEngine.Rigidbody2D[]

### RootOffset

```csharp
public Vector3 RootOffset { get; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### RootRigidbody

```csharp
public Rigidbody2D RootRigidbody { get; private set; }
```

#### Property Value

**Type:** UnityEngine.Rigidbody2D

### StartingBone

```csharp
public Bone StartingBone { get; private set; }
```

#### Property Value

**Type:** Spine.Bone

## Methods

### Apply()

```csharp
public void Apply()
```

### AttachBoundingBoxRagdollColliders(Bone, GameObject, Skeleton, float)

```csharp
private static List<Collider2D> AttachBoundingBoxRagdollColliders(Bone b, GameObject go, Skeleton skeleton, float gravityScale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `Spine.Bone` |  |
| `go` | `UnityEngine.GameObject` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `gravityScale` | `System.Single` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnityEngine.Collider2D}

### FlipScale(bool, bool)

```csharp
private static Vector3 FlipScale(bool flipX, bool flipY)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `flipX` | `System.Boolean` |  |
| `flipY` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Vector3

### GetPropagatedRotation(Bone)

```csharp
private static float GetPropagatedRotation(Bone b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `Spine.Bone` |  |

#### Returns

**Type:** System.Single

### GetRigidbody(string)

```csharp
public Rigidbody2D GetRigidbody(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Rigidbody2D

### RecursivelyCreateBoneProxies(Bone)

```csharp
private void RecursivelyCreateBoneProxies(Bone b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `Spine.Bone` |  |

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

### SmoothMixCoroutine(float, float)

```csharp
private IEnumerator SmoothMixCoroutine(float target, float duration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Single` |  |
| `duration` | `System.Single` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### Start()

```csharp
private IEnumerator Start()
```

#### Returns

**Type:** System.Collections.IEnumerator

### UpdateSpineSkeleton(ISkeletonAnimation)

```csharp
private void UpdateSpineSkeleton(ISkeletonAnimation animatedSkeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animatedSkeleton` | `Spine.Unity.ISkeletonAnimation` |  |
