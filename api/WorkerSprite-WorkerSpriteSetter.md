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
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerSpriteSetter()

```csharp
public WorkerSpriteSetter()
```

## Fields

### armorId

```csharp
public int armorId
```

#### Field Value

**Type:** System.Int32

### currentSkin

```csharp
public Skin currentSkin
```

#### Field Value

**Type:** Spine.Skin

### currentSpriteSet

```csharp
[Header("Data")]
public WorkerCurrentSpriteSet currentSpriteSet
```

#### Field Value

**Type:** WorkerSprite.WorkerCurrentSpriteSet

### debugCheck

```csharp
public bool debugCheck
```

#### Field Value

**Type:** System.Boolean

### EyebrowRenderer

```csharp
public SpriteRenderer EyebrowRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### eyeColor

```csharp
public Color eyeColor
```

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

#### Field Value

**Type:** UnityEngine.Color

### HeadSprite

```csharp
public Sprite HeadSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### MouthRenderer

```csharp
public SpriteRenderer MouthRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### MouthReplaceGiftRender

```csharp
public SpriteRenderer MouthReplaceGiftRender
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### NoteRenderer

```csharp
public SpriteRenderer NoteRenderer
```

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

#### Field Value

**Type:** System.Boolean

### repackedShader

```csharp
public Shader repackedShader
```

#### Field Value

**Type:** UnityEngine.Shader

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

#### Field Value

**Type:** UnityEngine.Material

### SetHeadSprite

```csharp
public bool SetHeadSprite
```

#### Field Value

**Type:** System.Boolean

### SymbolRenderer

```csharp
public SpriteRenderer SymbolRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### TransparentSprite

```csharp
public Sprite TransparentSprite
```

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

### Model

```csharp
public WorkerModel Model { get; }
```

#### Property Value

**Type:** Global.WorkerModel

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderData` | `WorkerSprite.EGOGiftRenderData` |  |

### AddGiftModel(EGOgiftModel)

```csharp
public void AddGiftModel(EGOgiftModel gift)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### Apply(List<SpineChangeData>)

```csharp
public void Apply(List<SpineChangeData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSprite.SpineChangeData}` |  |

### ArmorApply()

```csharp
public void ArmorApply()
```

### ArmorEquip(int)

```csharp
public void ArmorEquip(int armorId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armorId` | `System.Int32` |  |

### BaiscRendererInit()

```csharp
public void BaiscRendererInit()
```

### BaiscUniqueApply()

```csharp
public void BaiscUniqueApply()
```

### BasicApply()

```csharp
public void BasicApply()
```

### ChangeBasicSpriteData()

```csharp
public void ChangeBasicSpriteData()
```

### CheckGiftModel(List<EGOgiftModel>)

```csharp
public void CheckGiftModel(List<EGOgiftModel> gifts)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gifts` | `System.Collections.Generic.List{EGOgiftModel}` |  |

### DisableSeparartor(WorkerFaceType)

```csharp
public void DisableSeparartor(WorkerFaceType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### DisableSeparator()

```csharp
public void DisableSeparator()
```

### DisableSeparatorForUnique()

```csharp
public void DisableSeparatorForUnique()
```

### EnableSeparator()

```csharp
public void EnableSeparator()
```

### EquipmentApply()

```csharp
public void EquipmentApply()
```

### EyeApply()

```csharp
public void EyeApply()
```

### GetGiftPos(EGOgiftAttachRegion)

```csharp
public Transform GetGiftPos(EGOgiftAttachRegion region)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Global.EGOgiftAttachRegion` |  |

#### Returns

**Type:** UnityEngine.Transform

### Init(WorkerModel)

```csharp
public void Init(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### InitBasicSet()

```csharp
public void InitBasicSet()
```

### LoadBasicSpriteData()

```csharp
public void LoadBasicSpriteData()
```

### MouthApply()

```csharp
public void MouthApply()
```

### OnDie(bool)

```csharp
public void OnDie(bool isPanic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isPanic` | `System.Boolean` |  |

### OnSetEyeColor(Color)

```csharp
public void OnSetEyeColor(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### OnSetHair(Color)

```csharp
public void OnSetHair(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### RemoveGiftModel(EGOgiftModel)

```csharp
public void RemoveGiftModel(EGOgiftModel gift)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### ReplaceGift(EGOGiftRenderData)

```csharp
public void ReplaceGift(EGOGiftRenderData renderData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `renderData` | `WorkerSprite.EGOGiftRenderData` |  |

### Reskin()

```csharp
public void Reskin()
```

### SetBodyRegionKey(List<SpineChangeData>)

```csharp
public void SetBodyRegionKey(List<SpineChangeData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WorkerSprite.SpineChangeData}` |  |

### SetFaceEnable(bool)

```csharp
public void SetFaceEnable(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetHeadColor(Color)

```csharp
public void SetHeadColor(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### SetLayer(int, int)

```csharp
public void SetLayer(int layerId, int order)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `layerId` | `System.Int32` |  |
| `order` | `System.Int32` |  |

### SetLeftWeapon(WeaponClassType, Sprite)

```csharp
public void SetLeftWeapon(WeaponClassType type, Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### SetPanicShadow(bool, RwbpType)

```csharp
public void SetPanicShadow(bool state, RwbpType type = RwbpType.N)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
| `type` | `Global.RwbpType` |  |

### SetRegionAsTransparent(string, string)

```csharp
public void SetRegionAsTransparent(string slot, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `System.String` |  |
| `attachmentName` | `System.String` |  |

### SetRightWeapon(WeaponClassType, Sprite)

```csharp
public void SetRightWeapon(WeaponClassType type, Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### SetSefira(SefiraEnum, int)

```csharp
public void SetSefira(SefiraEnum sefira, int level = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `level` | `System.Int32` |  |

### SetWeaponTransparent()

```csharp
public void SetWeaponTransparent()
```

### SetWorkerFaceType(WorkerFaceType)

```csharp
public void SetWorkerFaceType(WorkerFaceType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### SetWorkerType(WorkerModel)

```csharp
public void SetWorkerType(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### SetWorkNoteSprite(Sprite)

```csharp
public void SetWorkNoteSprite(Sprite s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |

### StageStart()

```csharp
public void StageStart()
```

### TryGetGift(EGOgiftModel, out EGOGiftRenderData)

```csharp
public bool TryGetGift(EGOgiftModel model, out EGOGiftRenderData renderData)
```

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

### UpdateArmorSpriteSet()

```csharp
public void UpdateArmorSpriteSet()
```

### UpdateAttachment()

```csharp
public void UpdateAttachment()
```

### UpdateBasicSpriteSet()

```csharp
public void UpdateBasicSpriteSet()
```

### WeaponApply()

```csharp
public void WeaponApply()
```
