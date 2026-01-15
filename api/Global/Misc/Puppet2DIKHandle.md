---
uid: Global.Puppet2D_IKHandle
canonical_path: /api/Global/Misc/Puppet2DIKHandle
---

# Class Puppet2D_IKHandle

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Puppet2D_IKHandle : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → Puppet2D_IKHandle

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Puppet2D_IKHandle()

```csharp
public Puppet2D_IKHandle()
```

## Fields

### AimDirection

```csharp
[HideInInspector]
public Vector3 AimDirection
```

#### Field Value

**Type:** UnityEngine.Vector3

### angleLimits

```csharp
public List<Vector2> angleLimits
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Vector2}

### angleLimitTransform

```csharp
public List<Transform> angleLimitTransform
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Transform}

### bindBones

```csharp
public List<Transform> bindBones
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Transform}

### bindPose

```csharp
public List<Vector3> bindPose
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Vector3}

### bottomJointTransform

```csharp
[HideInInspector]
public Transform bottomJointTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### damping

```csharp
public float damping
```

#### Field Value

**Type:** System.Single

### endTransform

```csharp
public Transform endTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### Flip

```csharp
public bool Flip
```

#### Field Value

**Type:** System.Boolean

### IK_CTRL

```csharp
private Transform IK_CTRL
```

#### Field Value

**Type:** UnityEngine.Transform

### IKControl

```csharp
public Transform IKControl
```

#### Field Value

**Type:** UnityEngine.Transform

### iterations

```csharp
public int iterations
```

#### Field Value

**Type:** System.Int32

### LargerMiddleJoint

```csharp
private bool LargerMiddleJoint
```

#### Field Value

**Type:** System.Boolean

### limitBones

```csharp
public bool limitBones
```

#### Field Value

**Type:** System.Boolean

### middleJointTransform

```csharp
[HideInInspector]
public Transform middleJointTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### numberIkBonesIndex

```csharp
[HideInInspector]
public int numberIkBonesIndex
```

#### Field Value

**Type:** System.Int32

### numberOfBones

```csharp
public int numberOfBones
```

#### Field Value

**Type:** System.Int32

### OffsetScale

```csharp
[HideInInspector]
public Vector3 OffsetScale
```

#### Field Value

**Type:** UnityEngine.Vector3

### poleVector

```csharp
[HideInInspector]
public Transform poleVector
```

#### Field Value

**Type:** UnityEngine.Transform

### root2IK

```csharp
private Vector3 root2IK
```

#### Field Value

**Type:** UnityEngine.Vector3

### root2IK2MiddleJoint

```csharp
private Vector3 root2IK2MiddleJoint
```

#### Field Value

**Type:** UnityEngine.Vector3

### Scale

```csharp
public bool Scale
```

#### Field Value

**Type:** System.Boolean

### scaleStart

```csharp
[HideInInspector]
public Vector3[] scaleStart
```

#### Field Value

**Type:** UnityEngine.Vector3[]

### SquashAndStretch

```csharp
public bool SquashAndStretch
```

#### Field Value

**Type:** System.Boolean

### startTransform

```csharp
public Transform startTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### topJointTransform

```csharp
[HideInInspector]
public Transform topJointTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### UpDirection

```csharp
[HideInInspector]
public Vector3 UpDirection
```

#### Field Value

**Type:** UnityEngine.Vector3

## Methods

### CalculateIK()

```csharp
public void CalculateIK()
```

### CalculateMultiIK()

```csharp
public void CalculateMultiIK()
```

### CalculateMultiIK_run()

```csharp
private void CalculateMultiIK_run()
```

### ClampAngle(float, float, float)

```csharp
private float ClampAngle(float angle, float min, float max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angle` | `System.Single` |  |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetAngle()

```csharp
private float GetAngle()
```

#### Returns

**Type:** System.Single

### IsNaN(Quaternion)

```csharp
private bool IsNaN(Quaternion q)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `q` | `UnityEngine.Quaternion` |  |

#### Returns

**Type:** System.Boolean

### OnValidate()

```csharp
private void OnValidate()
```

### RotateTowardsTarget(Transform)

```csharp
private void RotateTowardsTarget(Transform startTransform)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startTransform` | `UnityEngine.Transform` |  |

### SignedAngle(Vector3, Vector3)

```csharp
public static float SignedAngle(Vector3 a, Vector3 b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `UnityEngine.Vector3` |  |
| `b` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** System.Single
