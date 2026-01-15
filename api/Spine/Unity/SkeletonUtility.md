---
uid: Spine.Unity.SkeletonUtility
canonical_path: /api/Spine/Unity/SkeletonUtility
---

# Class SkeletonUtility

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)
[`[UnityEngine.ExecuteInEditMode]`](#)

```csharp
[RequireComponent(typeof(ISkeletonAnimation))]
[ExecuteInEditMode]
public class SkeletonUtility : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SkeletonUtility

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonUtility()

```csharp
public SkeletonUtility()
```

## Fields

### boneRoot

```csharp
public Transform boneRoot
```

#### Field Value

**Type:** UnityEngine.Transform

### hasTransformBones

```csharp
protected bool hasTransformBones
```

#### Field Value

**Type:** System.Boolean

### hasUtilityConstraints

```csharp
protected bool hasUtilityConstraints
```

#### Field Value

**Type:** System.Boolean

### needToReprocessBones

```csharp
protected bool needToReprocessBones
```

#### Field Value

**Type:** System.Boolean

### skeletonAnimation

```csharp
[HideInInspector]
public ISkeletonAnimation skeletonAnimation
```

#### Field Value

**Type:** Spine.Unity.ISkeletonAnimation

### skeletonRenderer

```csharp
[HideInInspector]
public SkeletonRenderer skeletonRenderer
```

#### Field Value

**Type:** Spine.Unity.SkeletonRenderer

### utilityBones

```csharp
public List<SkeletonUtilityBone> utilityBones
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.Unity.SkeletonUtilityBone}

### utilityConstraints

```csharp
public List<SkeletonUtilityConstraint> utilityConstraints
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.Unity.SkeletonUtilityConstraint}

## Methods

### AddBoundingBoxAsComponent(BoundingBoxAttachment, Slot, GameObject, bool, bool, float)

```csharp
public static PolygonCollider2D AddBoundingBoxAsComponent(BoundingBoxAttachment box, Slot slot, GameObject gameObject, bool isTrigger = true, bool isKinematic = true, float gravityScale = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `box` | `Spine.BoundingBoxAttachment` |  |
| `slot` | `Spine.Slot` |  |
| `gameObject` | `UnityEngine.GameObject` |  |
| `isTrigger` | `System.Boolean` |  |
| `isKinematic` | `System.Boolean` |  |
| `gravityScale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.PolygonCollider2D

### AddBoundingBoxGameObject(Skeleton, string, string, string, Transform, bool)

```csharp
public static PolygonCollider2D AddBoundingBoxGameObject(Skeleton skeleton, string skinName, string slotName, string attachmentName, Transform parent, bool isTrigger = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `skinName` | `System.String` |  |
| `slotName` | `System.String` |  |
| `attachmentName` | `System.String` |  |
| `parent` | `UnityEngine.Transform` |  |
| `isTrigger` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.PolygonCollider2D

### AddBoundingBoxGameObject(string, BoundingBoxAttachment, Slot, Transform, bool)

```csharp
public static PolygonCollider2D AddBoundingBoxGameObject(string name, BoundingBoxAttachment box, Slot slot, Transform parent, bool isTrigger = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `box` | `Spine.BoundingBoxAttachment` |  |
| `slot` | `Spine.Slot` |  |
| `parent` | `UnityEngine.Transform` |  |
| `isTrigger` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.PolygonCollider2D

### CollectBones()

```csharp
public void CollectBones()
```

### GetBoneRoot()

```csharp
public Transform GetBoneRoot()
```

#### Returns

**Type:** UnityEngine.Transform

### GetBoundingBoxBounds(BoundingBoxAttachment, float)

```csharp
public static Bounds GetBoundingBoxBounds(BoundingBoxAttachment boundingBox, float depth = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boundingBox` | `Spine.BoundingBoxAttachment` |  |
| `depth` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Bounds

### HandleRendererReset(SkeletonRenderer)

```csharp
private void HandleRendererReset(SkeletonRenderer r)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Spine.Unity.SkeletonRenderer` |  |

### OnDisable()

```csharp
private void OnDisable()
```

### OnEnable()

```csharp
private void OnEnable()
```

### RegisterBone(SkeletonUtilityBone)

```csharp
public void RegisterBone(SkeletonUtilityBone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Unity.SkeletonUtilityBone` |  |

### RegisterConstraint(SkeletonUtilityConstraint)

```csharp
public void RegisterConstraint(SkeletonUtilityConstraint constraint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraint` | `Spine.Unity.SkeletonUtilityConstraint` |  |

### SetColliderPointsLocal(PolygonCollider2D, Slot, BoundingBoxAttachment)

```csharp
public static void SetColliderPointsLocal(PolygonCollider2D collider, Slot slot, BoundingBoxAttachment box)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collider` | `UnityEngine.PolygonCollider2D` |  |
| `slot` | `Spine.Slot` |  |
| `box` | `Spine.BoundingBoxAttachment` |  |

### SpawnBone(Bone, Transform, Mode, bool, bool, bool)

```csharp
public GameObject SpawnBone(Bone bone, Transform parent, SkeletonUtilityBone.Mode mode, bool pos, bool rot, bool sca)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `parent` | `UnityEngine.Transform` |  |
| `mode` | `Spine.Unity.SkeletonUtilityBone.Mode` |  |
| `pos` | `System.Boolean` |  |
| `rot` | `System.Boolean` |  |
| `sca` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### SpawnBoneRecursively(Bone, Transform, Mode, bool, bool, bool)

```csharp
public GameObject SpawnBoneRecursively(Bone bone, Transform parent, SkeletonUtilityBone.Mode mode, bool pos, bool rot, bool sca)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `parent` | `UnityEngine.Transform` |  |
| `mode` | `Spine.Unity.SkeletonUtilityBone.Mode` |  |
| `pos` | `System.Boolean` |  |
| `rot` | `System.Boolean` |  |
| `sca` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### SpawnHierarchy(Mode, bool, bool, bool)

```csharp
public GameObject SpawnHierarchy(SkeletonUtilityBone.Mode mode, bool pos, bool rot, bool sca)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mode` | `Spine.Unity.SkeletonUtilityBone.Mode` |  |
| `pos` | `System.Boolean` |  |
| `rot` | `System.Boolean` |  |
| `sca` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### SpawnRoot(Mode, bool, bool, bool)

```csharp
public GameObject SpawnRoot(SkeletonUtilityBone.Mode mode, bool pos, bool rot, bool sca)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mode` | `Spine.Unity.SkeletonUtilityBone.Mode` |  |
| `pos` | `System.Boolean` |  |
| `rot` | `System.Boolean` |  |
| `sca` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### Start()

```csharp
private void Start()
```

### UnregisterBone(SkeletonUtilityBone)

```csharp
public void UnregisterBone(SkeletonUtilityBone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Unity.SkeletonUtilityBone` |  |

### UnregisterConstraint(SkeletonUtilityConstraint)

```csharp
public void UnregisterConstraint(SkeletonUtilityConstraint constraint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraint` | `Spine.Unity.SkeletonUtilityConstraint` |  |

### Update()

```csharp
private void Update()
```

### UpdateAllBones()

```csharp
private void UpdateAllBones()
```

### UpdateComplete(ISkeletonAnimation)

```csharp
private void UpdateComplete(ISkeletonAnimation anim)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `Spine.Unity.ISkeletonAnimation` |  |

### UpdateLocal(ISkeletonAnimation)

```csharp
private void UpdateLocal(ISkeletonAnimation anim)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `Spine.Unity.ISkeletonAnimation` |  |

### UpdateWorld(ISkeletonAnimation)

```csharp
private void UpdateWorld(ISkeletonAnimation anim)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `Spine.Unity.ISkeletonAnimation` |  |

## Events

### OnReset

```csharp
public event SkeletonUtility.SkeletonUtilityDelegate OnReset
```

#### Returns

**Type:** Spine.Unity.SkeletonUtility.SkeletonUtilityDelegate
