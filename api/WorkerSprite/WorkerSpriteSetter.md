---
uid: WorkerSprite.WorkerSpriteSetter
canonical_path: /api/WorkerSprite/WorkerSpriteSetter
---

# Class WorkerSpriteSetter

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(SkeletonAnimator), typeof(Animator))]
public class WorkerSpriteSetter : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → WorkerSpriteSetter

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpriteSetter()

```csharp
public WorkerSpriteSetter()
```

## Fields

### _armorColored

```csharp
private bool _armorColored
```
#INC


#### Field Value

**Type:** System.Boolean

### _initWeaponData

```csharp
private bool _initWeaponData
```
#INC


#### Field Value

**Type:** System.Boolean

### _model

```csharp
private WorkerModel _model
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### _weaponPosition

```csharp
private Vector2 _weaponPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### _weaponRotation

```csharp
private float _weaponRotation
```
#INC


#### Field Value

**Type:** System.Single

### AddObjectSrc

```csharp
private const string AddObjectSrc = "Slot/WorkerAttachment"
```
#INC


#### Field Value

**Type:** System.String

### armorId

```csharp
public int armorId
```
#INC


#### Field Value

**Type:** System.Int32

### attachGiftData

```csharp
private Dictionary<int, EGOGiftRenderData> attachGiftData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,WorkerSprite.EGOGiftRenderData}

### currentGift

```csharp
private List<EGOgiftModel> currentGift
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EGOgiftModel}

### currentSkin

```csharp
public Skin currentSkin
```
#INC


#### Field Value

**Type:** Spine.Skin

### currentSpriteSet

```csharp
[Header("Data")]
public WorkerCurrentSpriteSet currentSpriteSet
```

#### Field Value

**Type:** WorkerSprite.WorkerCurrentSpriteSet

### currentWeaponType

```csharp
private WeaponClassType currentWeaponType
```
#INC


#### Field Value

**Type:** Global.WeaponClassType

### debugCheck

```csharp
public bool debugCheck
```
#INC


#### Field Value

**Type:** System.Boolean

### EyebrowRenderer

```csharp
public SpriteRenderer EyebrowRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### eyeColor

```csharp
public Color eyeColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### EyeRenderer

```csharp
[Header("Renderer")]
public SpriteRenderer EyeRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### faceType

```csharp
public WorkerFaceType faceType
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerFaceType

### GiftPos

```csharp
[Header("EGO_Gift")]
public Transform[] GiftPos
```

#### Field Value

**Type:** UnityEngine.Transform[]

### hairColor

```csharp
public Color hairColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### HeadRegion

```csharp
private const string HeadRegion = "Head"
```
#INC


#### Field Value

**Type:** System.String

### HeadSprite

```csharp
public Sprite HeadSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### MouthRenderer

```csharp
public SpriteRenderer MouthRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### MouthReplaceGiftRender

```csharp
public SpriteRenderer MouthReplaceGiftRender
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### NoteRenderer

```csharp
public SpriteRenderer NoteRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### panicRenderer

```csharp
[Header("Panic Related")]
public SpriteRenderer panicRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### repack

```csharp
public bool repack
```
#INC


#### Field Value

**Type:** System.Boolean

### repackedShader

```csharp
public Shader repackedShader
```
#INC


#### Field Value

**Type:** UnityEngine.Shader

### replaceGiftData

```csharp
private Dictionary<EGOgiftAttachRegion, EGOGiftRenderData> replaceGiftData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{EGOgiftAttachRegion,WorkerSprite.EGOGiftRenderData}

### runtimeAtlas

```csharp
[Header("Not Assigned")]
public Texture2D runtimeAtlas
```

#### Field Value

**Type:** UnityEngine.Texture2D

### runtimeMaterial

```csharp
public Material runtimeMaterial
```
#INC


#### Field Value

**Type:** UnityEngine.Material

### separator

```csharp
private SkeletonRenderSeparator separator
```
#INC


#### Field Value

**Type:** Spine.Unity.Modules.SkeletonRenderSeparator

### SetHeadSprite

```csharp
public bool SetHeadSprite
```
#INC


#### Field Value

**Type:** System.Boolean

### SymbolRenderer

```csharp
public SpriteRenderer SymbolRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### TransparentSprite

```csharp
public Sprite TransparentSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### WeaponRenderer

```csharp
[Header("Renderer")]
public SpriteRenderer WeaponRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

## Properties

### animator

```csharp
private Animator animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### Model

```csharp
public WorkerModel Model { get; }
```

#### Property Value

**Type:** Global.WorkerModel

### skeleton

```csharp
private Skeleton skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

### skeletonAnimator

```csharp
private SkeletonAnimator skeletonAnimator { get; }
```

#### Property Value

**Type:** Spine.Unity.SkeletonAnimator

### skeletonDataAsset

```csharp
private SkeletonDataAsset skeletonDataAsset { get; set; }
```

#### Property Value

**Type:** Spine.Unity.SkeletonDataAsset

### workerSpriteData

```csharp
public WorkerSprite workerSpriteData { get; set; }
```

#### Property Value

**Type:** WorkerSprite.WorkerSprite

## Methods

### AddGift(EGOGiftRenderData)

```csharp
public void AddGift(EGOGiftRenderData renderData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderData` | `WorkerSprite.EGOGiftRenderData` |  |

### AddGiftModel(EGOgiftModel)

```csharp
public void AddGiftModel(EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### Apply(List<SpineChangeData>)

```csharp
public void Apply(List<SpineChangeData> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSprite.SpineChangeData}` |  |

### ArmorApply()

```csharp
public void ArmorApply()
```
#INC


### ArmorEquip(int)

```csharp
public void ArmorEquip(int armorId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armorId` | `System.Int32` |  |

### BaiscRendererInit()

```csharp
public void BaiscRendererInit()
```
#INC


### BaiscUniqueApply()

```csharp
public void BaiscUniqueApply()
```
#INC


### BasicApply()

```csharp
public void BasicApply()
```
#INC


### ChangeBasicSpriteData()

```csharp
public void ChangeBasicSpriteData()
```
#INC


### ChangeSpineData(Skeleton, Skin, SpineChangeData)

```csharp
private void ChangeSpineData(Skeleton skeleton, Skin newSkin, SpineChangeData data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `newSkin` | `Spine.Skin` |  |
| `data` | `WorkerSprite.SpineChangeData` |  |

### ChangeSpineData(Skeleton, Skin, SpineChangeData, ref Vector3)

```csharp
private void ChangeSpineData(Skeleton skeleton, Skin newSkin, SpineChangeData data, ref Vector3 PositionFix)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `newSkin` | `Spine.Skin` |  |
| `data` | `WorkerSprite.SpineChangeData` |  |
| `PositionFix` | `UnityEngine.Vector3` |  |

### CheckGiftModel(List<EGOgiftModel>)

```csharp
public void CheckGiftModel(List<EGOgiftModel> gifts)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gifts` | `System.Collections.Generic.List{EGOgiftModel}` |  |

### DebugArmorEquip()

```csharp
private void DebugArmorEquip()
```
#INC


### DisableSeparartor(WorkerFaceType)

```csharp
public void DisableSeparartor(WorkerFaceType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### DisableSeparator()

```csharp
public void DisableSeparator()
```
#INC


### DisableSeparatorForUnique()

```csharp
public void DisableSeparatorForUnique()
```
#INC


### EnableSeparator()

```csharp
public void EnableSeparator()
```
#INC


### EquipmentApply()

```csharp
public void EquipmentApply()
```
#INC


### ExtractWeaponRegionData()

```csharp
private void ExtractWeaponRegionData()
```
#INC


### EyeApply()

```csharp
public void EyeApply()
```
#INC


### GetGiftPos(EGOgiftAttachRegion)

```csharp
public Transform GetGiftPos(EGOgiftAttachRegion region)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Global.EGOgiftAttachRegion` |  |

#### Returns

**Type:** UnityEngine.Transform

### IgnoreSpriteRenderer()

```csharp
private void IgnoreSpriteRenderer()
```
#INC


### IgnoreSpriteRenderer(WorkerFaceType)

```csharp
private void IgnoreSpriteRenderer(WorkerFaceType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### Init(WorkerModel)

```csharp
public void Init(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### InitBasicSet()

```csharp
public void InitBasicSet()
```
#INC


### LateUpdate()

```csharp
private void LateUpdate()
```
#INC


### LoadBasicSpriteData()

```csharp
public void LoadBasicSpriteData()
```
#INC


### MouthApply()

```csharp
public void MouthApply()
```
#INC


### OnDie(bool)

```csharp
public void OnDie(bool isPanic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isPanic` | `System.Boolean` |  |

### OnSetEyeColor(Color)

```csharp
public void OnSetEyeColor(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### OnSetHair(Color)

```csharp
public void OnSetHair(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### RemoveGiftModel(EGOgiftModel)

```csharp
public void RemoveGiftModel(EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### ReplaceGift(EGOGiftRenderData)

```csharp
public void ReplaceGift(EGOGiftRenderData renderData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderData` | `WorkerSprite.EGOGiftRenderData` |  |

### ReplaceGiftMouth(Sprite)

```csharp
private void ReplaceGiftMouth(Sprite sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### Reskin()

```csharp
public void Reskin()
```
#INC


### SetBodyRegionKey(List<SpineChangeData>)

```csharp
public void SetBodyRegionKey(List<SpineChangeData> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSprite.SpineChangeData}` |  |

### SetFaceEnable(bool)

```csharp
public void SetFaceEnable(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetHeadColor(Color)

```csharp
public void SetHeadColor(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### SetLayer(int, int)

```csharp
public void SetLayer(int layerId, int order)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `layerId` | `System.Int32` |  |
| `order` | `System.Int32` |  |

### SetLayer(Transform, int, int)

```csharp
private void SetLayer(Transform tr, int layerId, int order)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tr` | `UnityEngine.Transform` |  |
| `layerId` | `System.Int32` |  |
| `order` | `System.Int32` |  |

### SetLeftWeapon(WeaponClassType, Sprite)

```csharp
public void SetLeftWeapon(WeaponClassType type, Sprite sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### SetPanicShadow(bool, RwbpType)

```csharp
public void SetPanicShadow(bool state, RwbpType type = RwbpType.N)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
| `type` | `Global.RwbpType` |  |

### SetRegionAsTransparent(string, string)

```csharp
public void SetRegionAsTransparent(string slot, string attachmentName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `System.String` |  |
| `attachmentName` | `System.String` |  |

### SetRightWeapon(WeaponClassType, Sprite)

```csharp
public void SetRightWeapon(WeaponClassType type, Sprite sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### SetSefira(SefiraEnum, int)

```csharp
public void SetSefira(SefiraEnum sefira, int level = 1)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `level` | `System.Int32` |  |

### SetWeaponTransparent()

```csharp
public void SetWeaponTransparent()
```
#INC


### SetWorkerFaceType(WorkerFaceType)

```csharp
public void SetWorkerFaceType(WorkerFaceType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### SetWorkerType(WorkerModel)

```csharp
public void SetWorkerType(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### SetWorkNoteSprite(Sprite)

```csharp
public void SetWorkNoteSprite(Sprite s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |

### StageStart()

```csharp
public void StageStart()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### TryGetGift(EGOgiftModel, out EGOGiftRenderData)

```csharp
public bool TryGetGift(EGOgiftModel model, out EGOGiftRenderData renderData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `renderData` | `WorkerSprite.EGOGiftRenderData` |  |

#### Returns

**Type:** System.Boolean

### UniqueFaceReskin()

```csharp
public void UniqueFaceReskin()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateArmorSpriteSet()

```csharp
public void UpdateArmorSpriteSet()
```
#INC


### UpdateAttachment()

```csharp
public void UpdateAttachment()
```
#INC


### UpdateBasicSpriteSet()

```csharp
public void UpdateBasicSpriteSet()
```
#INC


### WeaponApply()

```csharp
public void WeaponApply()
```
#INC

