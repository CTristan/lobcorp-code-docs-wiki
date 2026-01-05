# Class SkeletonGraphic

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.ExecuteInEditMode]`](#)
[`[UnityEngine.RequireComponent]`](#)
[`[UnityEngine.DisallowMultipleComponent]`](#)
[`[UnityEngine.AddComponentMenu]`](#)

```csharp
[ExecuteInEditMode]
[RequireComponent(typeof(CanvasRenderer), typeof(RectTransform))]
[DisallowMultipleComponent]
[AddComponentMenu("Spine/SkeletonGraphic (Unity UI Canvas)")]
public class SkeletonGraphic : MaskableGraphic, ICanvasElement, IClippable, IMaskable, IMaterialModifier, ISkeletonComponent, IAnimationStateComponent, ISkeletonAnimation
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [UIBehaviour](#) → [Graphic](#) → [MaskableGraphic](#) → SkeletonGraphic

## Inherited Members
[m_ShouldRecalculateStencil](#), [m_MaskMaterial](#), [m_IncludeForMasking](#), [m_ShouldRecalculate](#), [m_StencilValue](#), [GetModifiedMaterial(Material)](#), [Cull(Rect, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [SetClipRect(Rect, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [OnEnable()](#), [OnDisable()](#), [OnTransformParentChanged()](#), [ParentMaskStateChanged()](#), [OnCanvasHierarchyChanged()](#), [RecalculateClipping()](#), [RecalculateMasking()](#), [onCullStateChanged](#), [maskable](#), [s_DefaultUI](#), [s_WhiteTexture](#), [m_Material](#), [m_OnDirtyLayoutCallback](#), [m_OnDirtyVertsCallback](#), [m_OnDirtyMaterialCallback](#), [s_Mesh](#), [SetAllDirty()](#), [SetLayoutDirty()](#), [SetVerticesDirty()](#), [SetMaterialDirty()](#), [OnRectTransformDimensionsChange()](#), [OnBeforeTransformParentChanged()](#), [OnCullingChanged()](#), [LayoutComplete()](#), [GraphicUpdateComplete()](#), [UpdateMaterial()](#), [UpdateGeometry()](#), [OnFillVBO(List<UIVertex>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [OnPopulateMesh(Mesh)](#), [OnPopulateMesh(VertexHelper)](#), [OnDidApplyAnimationProperties()](#), [SetNativeSize()](#), [Raycast(Vector2, Camera)](#), [PixelAdjustPoint(Vector2)](#), [GetPixelAdjustedRect()](#), [CrossFadeColor(Color, float, bool, bool)](https://learn.microsoft.com/dotnet/api/system.single), [CrossFadeColor(Color, float, bool, bool, bool)](https://learn.microsoft.com/dotnet/api/system.single), [CrossFadeAlpha(float, float, bool)](https://learn.microsoft.com/dotnet/api/system.single), [RegisterDirtyLayoutCallback(UnityAction)](#), [UnregisterDirtyLayoutCallback(UnityAction)](#), [RegisterDirtyVerticesCallback(UnityAction)](#), [UnregisterDirtyVerticesCallback(UnityAction)](#), [RegisterDirtyMaterialCallback(UnityAction)](#), [UnregisterDirtyMaterialCallback(UnityAction)](#), [defaultGraphicMaterial](#), [color](#), [raycastTarget](#), [useLegacyMeshGeneration](#), [depth](#), [rectTransform](#), [canvas](#), [canvasRenderer](#), [defaultMaterial](#), [material](#), [materialForRendering](#), [workerMesh](#), [Start()](#), [OnDestroy()](#), [IsActive()](#), [OnCanvasGroupChanged()](#), [IsDestroyed()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonGraphic()

```csharp
public SkeletonGraphic()
```

## Fields

### freeze

```csharp
public bool freeze
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
[SpineSkin("", "skeletonDataAsset", true)]
public string initialSkinName
```

#### Field Value

**Type:** System.String

### meshGenerator

```csharp
[SerializeField]
protected MeshGenerator meshGenerator
```

#### Field Value

**Type:** Spine.Unity.MeshGenerator

### skeleton

```csharp
protected Skeleton skeleton
```

#### Field Value

**Type:** Spine.Skeleton

### skeletonDataAsset

```csharp
public SkeletonDataAsset skeletonDataAsset
```

#### Field Value

**Type:** Spine.Unity.SkeletonDataAsset

### startingAnimation

```csharp
[SpineAnimation("", "skeletonDataAsset", true)]
public string startingAnimation
```

#### Field Value

**Type:** System.String

### startingLoop

```csharp
public bool startingLoop
```

#### Field Value

**Type:** System.Boolean

### state

```csharp
protected AnimationState state
```

#### Field Value

**Type:** Spine.AnimationState

### timeScale

```csharp
public float timeScale
```

#### Field Value

**Type:** System.Single

### unscaledTime

```csharp
public bool unscaledTime
```

#### Field Value

**Type:** System.Boolean

## Properties

### AnimationState

```csharp
public AnimationState AnimationState { get; }
```

#### Property Value

**Type:** Spine.AnimationState

### IsValid

```csharp
public bool IsValid { get; }
```

#### Property Value

**Type:** System.Boolean

### mainTexture

```csharp
public override Texture mainTexture { get; }
```

#### Property Value

**Type:** UnityEngine.Texture

### MeshGenerator

```csharp
public MeshGenerator MeshGenerator { get; }
```

#### Property Value

**Type:** Spine.Unity.MeshGenerator

### OverrideTexture

```csharp
public Texture OverrideTexture { get; set; }
```

#### Property Value

**Type:** UnityEngine.Texture

### Skeleton

```csharp
public Skeleton Skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

### SkeletonData

```csharp
public SkeletonData SkeletonData { get; }
```

#### Property Value

**Type:** Spine.SkeletonData

### SkeletonDataAsset

```csharp
public SkeletonDataAsset SkeletonDataAsset { get; }
```

#### Property Value

**Type:** Spine.Unity.SkeletonDataAsset

## Methods

### AddSkeletonGraphicComponent(GameObject, SkeletonDataAsset)

```csharp
public static SkeletonGraphic AddSkeletonGraphicComponent(GameObject gameObject, SkeletonDataAsset skeletonDataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gameObject` | `UnityEngine.GameObject` |  |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** Spine.Unity.SkeletonGraphic

### Awake()

```csharp
protected override void Awake()
```

### Clear()

```csharp
public void Clear()
```

### GetLastMesh()

```csharp
public Mesh GetLastMesh()
```

#### Returns

**Type:** UnityEngine.Mesh

### Initialize(bool)

```csharp
public void Initialize(bool overwrite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overwrite` | `System.Boolean` |  |

### LateUpdate()

```csharp
public void LateUpdate()
```

### NewSkeletonGraphicGameObject(SkeletonDataAsset, Transform)

```csharp
public static SkeletonGraphic NewSkeletonGraphicGameObject(SkeletonDataAsset skeletonDataAsset, Transform parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |
| `parent` | `UnityEngine.Transform` |  |

#### Returns

**Type:** Spine.Unity.SkeletonGraphic

### Rebuild(CanvasUpdate)

```csharp
public override void Rebuild(CanvasUpdate update)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `update` | `UnityEngine.UI.CanvasUpdate` |  |

### Update()

```csharp
public virtual void Update()
```

### Update(float)

```csharp
public virtual void Update(float deltaTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deltaTime` | `System.Single` |  |

### UpdateMesh()

```csharp
public void UpdateMesh()
```

## Events

### OnPostProcessVertices

```csharp
public event MeshGeneratorDelegate OnPostProcessVertices
```

#### Returns

**Type:** Spine.Unity.MeshGeneratorDelegate

### UpdateComplete

```csharp
public event UpdateBonesDelegate UpdateComplete
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateLocal

```csharp
public event UpdateBonesDelegate UpdateLocal
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateWorld

```csharp
public event UpdateBonesDelegate UpdateWorld
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate
