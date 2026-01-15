---
uid: Spine.Unity.SkeletonRenderer
canonical_path: /api/Spine/Unity/SkeletonRenderer
---

# Class SkeletonRenderer

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.ExecuteInEditMode]`](#)
[`[UnityEngine.RequireComponent]`](#)
[`[UnityEngine.DisallowMultipleComponent]`](#)
[`[UnityEngine.HelpURLAttribute]`](#)

```csharp
[ExecuteInEditMode]
[RequireComponent(typeof(MeshFilter), typeof(MeshRenderer))]
[DisallowMultipleComponent]
[HelpURL("http://esotericsoftware.com/spine-unity-documentation#Rendering")]
public class SkeletonRenderer : MonoBehaviour, ISkeletonComponent
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SkeletonRenderer

## Derived
[SkeletonAnimation](/api/Spine/Unity/SkeletonAnimation), [SkeletonAnimator](/api/Spine/Unity/SkeletonAnimator)

## Implements
[ISkeletonComponent](/api/Spine/Unity/ISkeletonComponent)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonRenderer()

```csharp
public SkeletonRenderer()
```

## Fields

### _optCount

```csharp
protected int _optCount
```

#### Field Value

**Type:** System.Int32

### addNormals

```csharp
[FormerlySerializedAs("calculateNormals")]
public bool addNormals
```

#### Field Value

**Type:** System.Boolean

### calculateTangents

```csharp
public bool calculateTangents
```

#### Field Value

**Type:** System.Boolean

### clearStateOnDisable

```csharp
public bool clearStateOnDisable
```

#### Field Value

**Type:** System.Boolean

### currentInstructions

```csharp
private readonly SkeletonRendererInstruction currentInstructions
```

#### Field Value

**Type:** Spine.Unity.SkeletonRendererInstruction

### customMaterialOverride

```csharp
private readonly Dictionary<Material, Material> customMaterialOverride
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{UnityEngine.Material,UnityEngine.Material}

### customSlotMaterials

```csharp
private readonly Dictionary<Slot, Material> customSlotMaterials
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{Spine.Slot,UnityEngine.Material}

### disableRenderingOnOverride

```csharp
public bool disableRenderingOnOverride
```

#### Field Value

**Type:** System.Boolean

### immutableTriangles

```csharp
public bool immutableTriangles
```

#### Field Value

**Type:** System.Boolean

### initialFlipX

```csharp
public bool initialFlipX
```

#### Field Value

**Type:** System.Boolean

### initialFlipY

```csharp
public bool initialFlipY
```

#### Field Value

**Type:** System.Boolean

### initialSkinName

```csharp
public string initialSkinName
```

#### Field Value

**Type:** System.String

### logErrors

```csharp
public bool logErrors
```

#### Field Value

**Type:** System.Boolean

### meshFilter

```csharp
private MeshFilter meshFilter
```

#### Field Value

**Type:** UnityEngine.MeshFilter

### meshGenerator

```csharp
private readonly MeshGenerator meshGenerator
```

#### Field Value

**Type:** Spine.Unity.MeshGenerator

### meshRenderer

```csharp
private MeshRenderer meshRenderer
```

#### Field Value

**Type:** UnityEngine.MeshRenderer

### optimizeLevel

```csharp
public int optimizeLevel
```

#### Field Value

**Type:** System.Int32

### pmaVertexColors

```csharp
public bool pmaVertexColors
```

#### Field Value

**Type:** System.Boolean

### rendererBuffers

```csharp
private readonly MeshRendererBuffers rendererBuffers
```

#### Field Value

**Type:** Spine.Unity.MeshRendererBuffers

### separatorSlotNames

```csharp
[FormerlySerializedAs("submeshSeparators")]
[SpineSlot("", "", false, true)]
public string[] separatorSlotNames
```

#### Field Value

**Type:** System.String[]

### separatorSlots

```csharp
public readonly List<Slot> separatorSlots
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.Slot}

### singleSubmesh

```csharp
public bool singleSubmesh
```

#### Field Value

**Type:** System.Boolean

### skeleton

```csharp
public Skeleton skeleton
```

#### Field Value

**Type:** Spine.Skeleton

### skeletonDataAsset

```csharp
public SkeletonDataAsset skeletonDataAsset
```

#### Field Value

**Type:** Spine.Unity.SkeletonDataAsset

### tintBlack

```csharp
public bool tintBlack
```

#### Field Value

**Type:** System.Boolean

### useClipping

```csharp
public bool useClipping
```

#### Field Value

**Type:** System.Boolean

### valid

```csharp
public bool valid
```

#### Field Value

**Type:** System.Boolean

### zSpacing

```csharp
[Range(-0.1, 0)]
public float zSpacing
```

#### Field Value

**Type:** System.Single

## Properties

### CustomMaterialOverride

```csharp
public Dictionary<Material, Material> CustomMaterialOverride { get; }
```

#### Property Value

**Type:** System.Collections.Generic.Dictionary{UnityEngine.Material,UnityEngine.Material}

### CustomSlotMaterials

```csharp
public Dictionary<Slot, Material> CustomSlotMaterials { get; }
```

#### Property Value

**Type:** System.Collections.Generic.Dictionary{Spine.Slot,UnityEngine.Material}

### Skeleton

```csharp
public Skeleton Skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

### SkeletonDataAsset

```csharp
public SkeletonDataAsset SkeletonDataAsset { get; }
```

#### Property Value

**Type:** Spine.Unity.SkeletonDataAsset

## Methods

### AddSpineComponent<T>(GameObject, SkeletonDataAsset)

```csharp
public static T AddSpineComponent<T>(GameObject gameObject, SkeletonDataAsset skeletonDataAsset) where T : SkeletonRenderer
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gameObject` | `UnityEngine.GameObject` |  |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** {T}

### Awake()

```csharp
public virtual void Awake()
```

### ClearState()

```csharp
public virtual void ClearState()
```

### Initialize(bool)

```csharp
public virtual void Initialize(bool overwrite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overwrite` | `System.Boolean` |  |

### LateUpdate()

```csharp
public virtual void LateUpdate()
```

### NewSpineGameObject<T>(SkeletonDataAsset)

```csharp
public static T NewSpineGameObject<T>(SkeletonDataAsset skeletonDataAsset) where T : SkeletonRenderer
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** {T}

### OnDestroy()

```csharp
private void OnDestroy()
```

### OnDisable()

```csharp
private void OnDisable()
```

### SetMeshSettings(Settings)

```csharp
public void SetMeshSettings(MeshGenerator.Settings settings)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `settings` | `Spine.Unity.MeshGenerator.Settings` |  |

## Events

### generateMeshOverride

```csharp
private event SkeletonRenderer.InstructionDelegate generateMeshOverride
```

#### Returns

**Type:** Spine.Unity.SkeletonRenderer.InstructionDelegate

### GenerateMeshOverride

```csharp
public event SkeletonRenderer.InstructionDelegate GenerateMeshOverride
```

#### Returns

**Type:** Spine.Unity.SkeletonRenderer.InstructionDelegate

### OnPostProcessVertices

```csharp
public event MeshGeneratorDelegate OnPostProcessVertices
```

#### Returns

**Type:** Spine.Unity.MeshGeneratorDelegate

### OnRebuild

```csharp
public event SkeletonRenderer.SkeletonRendererDelegate OnRebuild
```

#### Returns

**Type:** Spine.Unity.SkeletonRenderer.SkeletonRendererDelegate
