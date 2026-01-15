---
uid: Spine.Unity.SkeletonAnimation
canonical_path: /api/Spine/Unity/SkeletonAnimation
---

# Class SkeletonAnimation

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.ExecuteInEditMode]`](#)
[`[UnityEngine.AddComponentMenu]`](#)
[`[UnityEngine.HelpURLAttribute]`](#)

```csharp
[ExecuteInEditMode]
[AddComponentMenu("Spine/SkeletonAnimation")]
[HelpURL("http://esotericsoftware.com/spine-unity-documentation#Controlling-Animation")]
public class SkeletonAnimation : SkeletonRenderer, ISkeletonComponent, ISkeletonAnimation, IAnimationStateComponent
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [SkeletonRenderer](/api/Spine/Unity/SkeletonRenderer) → SkeletonAnimation

## Implements
[ISkeletonComponent](/api/Spine/Unity/ISkeletonComponent), [ISkeletonAnimation](/api/Spine/Unity/ISkeletonAnimation), [IAnimationStateComponent](/api/Spine/Unity/IAnimationStateComponent)

## Inherited Members
[skeletonDataAsset](/api/Spine/Unity/SkeletonRenderer#skeletondataasset), [initialSkinName](/api/Spine/Unity/SkeletonRenderer#initialskinname), [initialFlipX](/api/Spine/Unity/SkeletonRenderer#initialflipx), [initialFlipY](/api/Spine/Unity/SkeletonRenderer#initialflipy), [optimizeLevel](/api/Spine/Unity/SkeletonRenderer#optimizelevel), [separatorSlotNames](/api/Spine/Unity/SkeletonRenderer#separatorslotnames), [separatorSlots](/api/Spine/Unity/SkeletonRenderer#separatorslots), [zSpacing](/api/Spine/Unity/SkeletonRenderer#zspacing), [useClipping](/api/Spine/Unity/SkeletonRenderer#useclipping), [immutableTriangles](/api/Spine/Unity/SkeletonRenderer#immutabletriangles), [pmaVertexColors](/api/Spine/Unity/SkeletonRenderer#pmavertexcolors), [clearStateOnDisable](/api/Spine/Unity/SkeletonRenderer#clearstateondisable), [tintBlack](/api/Spine/Unity/SkeletonRenderer#tintblack), [singleSubmesh](/api/Spine/Unity/SkeletonRenderer#singlesubmesh), [addNormals](/api/Spine/Unity/SkeletonRenderer#addnormals), [calculateTangents](/api/Spine/Unity/SkeletonRenderer#calculatetangents), [logErrors](/api/Spine/Unity/SkeletonRenderer#logerrors), [disableRenderingOnOverride](/api/Spine/Unity/SkeletonRenderer#disablerenderingonoverride), [customMaterialOverride](/api/Spine/Unity/SkeletonRenderer#custommaterialoverride), [customSlotMaterials](/api/Spine/Unity/SkeletonRenderer#customslotmaterials), [meshRenderer](/api/Spine/Unity/SkeletonRenderer#meshrenderer), [meshFilter](/api/Spine/Unity/SkeletonRenderer#meshfilter), [valid](/api/Spine/Unity/SkeletonRenderer#valid), [skeleton](/api/Spine/Unity/SkeletonRenderer#skeleton), [currentInstructions](/api/Spine/Unity/SkeletonRenderer#currentinstructions), [meshGenerator](/api/Spine/Unity/SkeletonRenderer#meshgenerator), [rendererBuffers](/api/Spine/Unity/SkeletonRenderer#rendererbuffers), [_optCount](/api/Spine/Unity/SkeletonRenderer#optcount), [NewSpineGameObject<T>(SkeletonDataAsset)](/api/Spine/Unity/SkeletonRenderer#newspinegameobject-t-skeletondataasset), [AddSpineComponent<T>(GameObject, SkeletonDataAsset)](/api/Spine/Unity/SkeletonRenderer#addspinecomponent-t-gameobject-skeletondataasset), [SetMeshSettings(Settings)](/api/Spine/Unity/SkeletonRenderer#setmeshsettings-settings), [Awake()](/api/Spine/Unity/SkeletonRenderer#awake), [OnDisable()](/api/Spine/Unity/SkeletonRenderer#ondisable), [OnDestroy()](/api/Spine/Unity/SkeletonRenderer#ondestroy), [LateUpdate()](/api/Spine/Unity/SkeletonRenderer#lateupdate), [SkeletonDataAsset](/api/Spine/Unity/SkeletonRenderer#skeletondataasset), [CustomMaterialOverride](/api/Spine/Unity/SkeletonRenderer#custommaterialoverride), [CustomSlotMaterials](/api/Spine/Unity/SkeletonRenderer#customslotmaterials), [Skeleton](/api/Spine/Unity/SkeletonRenderer#skeleton), [OnRebuild](/api/Spine/Unity/SkeletonRenderer#onrebuild), [OnPostProcessVertices](/api/Spine/Unity/SkeletonRenderer#onpostprocessvertices), [generateMeshOverride](/api/Spine/Unity/SkeletonRenderer#generatemeshoverride), [GenerateMeshOverride](/api/Spine/Unity/SkeletonRenderer#generatemeshoverride), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonAnimation()

```csharp
public SkeletonAnimation()
```

## Fields

### _animationName

```csharp
[SerializeField]
[SpineAnimation("", "", true)]
private string _animationName
```

#### Field Value

**Type:** System.String

### loop

```csharp
public bool loop
```

#### Field Value

**Type:** System.Boolean

### state

```csharp
public AnimationState state
```

#### Field Value

**Type:** Spine.AnimationState

### timeScale

```csharp
public float timeScale
```

#### Field Value

**Type:** System.Single

## Properties

### AnimationName

```csharp
public string AnimationName { get; set; }
```

#### Property Value

**Type:** System.String

### AnimationState

```csharp
public AnimationState AnimationState { get; }
```

#### Property Value

**Type:** Spine.AnimationState

## Methods

### AddToGameObject(GameObject, SkeletonDataAsset)

```csharp
public static SkeletonAnimation AddToGameObject(GameObject gameObject, SkeletonDataAsset skeletonDataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gameObject` | `UnityEngine.GameObject` |  |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** Spine.Unity.SkeletonAnimation

### ClearState()

```csharp
public override void ClearState()
```

### Initialize(bool)

```csharp
public override void Initialize(bool overwrite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overwrite` | `System.Boolean` |  |

### NewSkeletonAnimationGameObject(SkeletonDataAsset)

```csharp
public static SkeletonAnimation NewSkeletonAnimationGameObject(SkeletonDataAsset skeletonDataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

#### Returns

**Type:** Spine.Unity.SkeletonAnimation

### Update()

```csharp
private void Update()
```

### Update(float)

```csharp
public void Update(float deltaTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deltaTime` | `System.Single` |  |

## Events

### _UpdateComplete

```csharp
protected event UpdateBonesDelegate _UpdateComplete
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### _UpdateLocal

```csharp
protected event UpdateBonesDelegate _UpdateLocal
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### _UpdateWorld

```csharp
protected event UpdateBonesDelegate _UpdateWorld
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

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
