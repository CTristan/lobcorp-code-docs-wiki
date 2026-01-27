---
uid: Global.WorkerSpriteManager
canonical_path: /api/Global/Worker/WorkerSpriteManager
---

# Class WorkerSpriteManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpriteManager : MonoBehaviour
```

Manages worker sprites. #INC 
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → WorkerSpriteManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpriteManager()

```csharp
public WorkerSpriteManager()
```

## Fields

### _instance

```csharp
private static WorkerSpriteManager _instance
```
#INC


#### Field Value

**Type:** Global.WorkerSpriteManager

### _uniqueWeaponDic

```csharp
private Dictionary<string, UniqueWeaponSpriteUnit> _uniqueWeaponDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,WorkerSprite.UniqueWeaponSpriteUnit}

### basicData

```csharp
[Header("Spine")]
public WorkerBasicSpriteController basicData
```

#### Field Value

**Type:** WorkerSprite.WorkerBasicSpriteController

### bothHairPath

```csharp
public const string bothHairPath = "Sprites/Agent/Hair/Both"
```
#INC


#### Field Value

**Type:** System.String

### custom_128

```csharp
private static float custom_128
```
#INC


#### Field Value

**Type:** System.Single

### custom_256

```csharp
private static float custom_256
```
#INC


#### Field Value

**Type:** System.Single

### custom_512

```csharp
private static float custom_512
```
#INC


#### Field Value

**Type:** System.Single

### custom_x_std_face

```csharp
private const float custom_x_std_face = 256
```
#INC


#### Field Value

**Type:** System.Single

### custom_x_std_hair

```csharp
private const float custom_x_std_hair = 256
```
#INC


#### Field Value

**Type:** System.Single

### equipData

```csharp
public WorkerEquipmentSpriteController equipData
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerEquipmentSpriteController

### facePath

```csharp
public const string facePath = "Sprites/Agent/Face"
```
#INC


#### Field Value

**Type:** System.String

### femaleHairPath

```csharp
public const string femaleHairPath = "Sprites/Agent/Hair/Female"
```
#INC


#### Field Value

**Type:** System.String

### maleHairPath

```csharp
public const string maleHairPath = "Sprites/Agent/Hair/Male"
```
#INC


#### Field Value

**Type:** System.String

### ModifyBases

```csharp
private static string ModifyBases
```

#### Field Value

**Type:** System.String

### Modifys

```csharp
public List<int> Modifys
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### PanicShadow

```csharp
public List<Sprite> PanicShadow
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### pivot

```csharp
private static Vector2 pivot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### righthand

```csharp
public Sprite righthand
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### SefiraSymbol

```csharp
public List<Sprite> SefiraSymbol
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### SefiraSymbol2

```csharp
public List<Sprite> SefiraSymbol2
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### SefiraSymbol3

```csharp
public List<Sprite> SefiraSymbol3
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### SefiraSymbol4

```csharp
public List<Sprite> SefiraSymbol4
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### Special_Basic

```csharp
public static Sprite Special_Basic
```

#### Field Value

**Type:** UnityEngine.Sprite

### UniqueWeapon

```csharp
public List<Sprite> UniqueWeapon
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### uniqueWeaponSprites

```csharp
[Header("UniqueWeapon")]
public List<UniqueWeaponSpriteUnit> uniqueWeaponSprites
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.UniqueWeaponSpriteUnit}

### workerColor

```csharp
public List<WorkerColorPreset> workerColor
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerSpine.WorkerColorPreset}

### WorkNote

```csharp
public List<Sprite> WorkNote
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

## Properties

### CustomBattleEyebrowSrc

```csharp
public string CustomBattleEyebrowSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomBattleMouthSrc

```csharp
public string CustomBattleMouthSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomDeadEyeSrc

```csharp
public string CustomDeadEyeSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomEyebrowSrc

```csharp
public string CustomEyebrowSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomEyeSrc

```csharp
public string CustomEyeSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomFaceSrc

```csharp
public string CustomFaceSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomFolderSrc

```csharp
public string CustomFolderSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomFrontHairSrc

```csharp
public string CustomFrontHairSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomHairSrc

```csharp
public string CustomHairSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomMouthSrc

```csharp
public string CustomMouthSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomPanicEyebrowSrc

```csharp
public string CustomPanicEyebrowSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomPanicEyeSrc

```csharp
public string CustomPanicEyeSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomRearHairSrc

```csharp
public string CustomRearHairSrc { get; }
```

#### Property Value

**Type:** System.String

### instance

```csharp
public static WorkerSpriteManager instance { get; }
```

#### Property Value

**Type:** Global.WorkerSpriteManager

## Methods

### Awake()

```csharp
public void Awake()
```
#INC
#code-generated


### GetAgentArmor(ref WorkerSprite)

```csharp
public void GetAgentArmor(ref WorkerSprite set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |

### GetArmorData(int, ref WorkerSprite)

```csharp
public void GetArmorData(int id, ref WorkerSprite set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `set` | `WorkerSprite.WorkerSprite` |  |

### GetAttachmentSprite(EGOgiftAttachRegion, string)

```csharp
public Sprite GetAttachmentSprite(EGOgiftAttachRegion region, string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Global.EGOgiftAttachRegion` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetClothesSet(int)

```csharp
public SpriteResourceLoadData GetClothesSet(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### GetFistSprite(int)

```csharp
public Sprite[] GetFistSprite(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite[]

### GetOfficerArmor(SefiraEnum)

```csharp
private int GetOfficerArmor(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Int32

### GetOfficerArmror(ref WorkerSprite, SefiraEnum)

```csharp
public void GetOfficerArmror(ref WorkerSprite set, SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |
| `sefira` | `Global.SefiraEnum` |  |

### GetPanicShadow(RwbpType)

```csharp
public Sprite GetPanicShadow(RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetRandomBasicData(WorkerSprite, bool)

```csharp
public void GetRandomBasicData(WorkerSprite set, bool containCustoms = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |
| `containCustoms` | `System.Boolean` |  |

### GetRandomColor()

```csharp
public Color GetRandomColor()
```
#INC


#### Returns

**Type:** UnityEngine.Color

### GetSefiraSymbol(AgentModel)

```csharp
public Sprite GetSefiraSymbol(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetSefiraSymbol(SefiraEnum, int)

```csharp
public Sprite GetSefiraSymbol(SefiraEnum sefira, int level = 1)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetUniqueBasicData(WorkerSprite, UniqueCreditAgentInfo)

```csharp
public void GetUniqueBasicData(WorkerSprite set, UniqueCreditAgentInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |
| `info` | `Global.UniqueCreditAgentInfo` |  |

### GetUniqueWeaponSpriteInfo(string, out UniqueWeaponSpriteUnit)

```csharp
public bool GetUniqueWeaponSpriteInfo(string name, out UniqueWeaponSpriteUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `unit` | `WorkerSprite.UniqueWeaponSpriteUnit` |  |

#### Returns

**Type:** System.Boolean

### GetWeaponSprite(WeaponClassType, string)

```csharp
public Sprite GetWeaponSprite(WeaponClassType type, string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetWorkNoteSprite(int)

```csharp
public Sprite GetWorkNoteSprite(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite

### LoadBasicData(BasicSpriteRegion, Pair)

```csharp
public Sprite LoadBasicData(BasicSpriteRegion region, WorkerSpriteSaveData.Pair pair)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `WorkerSprite.BasicSpriteRegion` |  |
| `pair` | `WorkerSprite.WorkerSpriteSaveData.Pair` |  |

#### Returns

**Type:** UnityEngine.Sprite

### LoadCustomSprite(DirectoryInfo, BasicSpriteRegion, SizeRef)

```csharp
public void LoadCustomSprite(DirectoryInfo di, BasicSpriteRegion region, WorkerSpriteManager.SizeRef size)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `di` | `System.IO.DirectoryInfo` |  |
| `region` | `WorkerSprite.BasicSpriteRegion` |  |
| `size` | `Global.WorkerSpriteManager.SizeRef` |  |

### LoadCustomSprites()

```csharp
public void LoadCustomSprites()
```
#INC


### LoadSpineData()

```csharp
private void LoadSpineData()
```
#INC


### LoadWorkerSpriteSetBySaveData(WorkerSprite)

```csharp
public void LoadWorkerSpriteSetBySaveData(WorkerSprite set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |

### MakeNewUniqueWeaponSpriteUnit(string, UniqueWeaponSpriteUnit, DirectoryInfo, Texture2D, out Sprite)

```csharp
public void MakeNewUniqueWeaponSpriteUnit(string name, UniqueWeaponSpriteUnit unit, DirectoryInfo dir, Texture2D texture, out Sprite result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `unit` | `WorkerSprite.UniqueWeaponSpriteUnit` |  |
| `dir` | `System.IO.DirectoryInfo` |  |
| `texture` | `UnityEngine.Texture2D` |  |
| `result` | `UnityEngine.Sprite` |  |

### ScaleTexture(Texture2D, int, int, bool)

```csharp
public static Texture2D ScaleTexture(Texture2D source, int targetWidth, int targetHeight, bool mipmap = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `source` | `UnityEngine.Texture2D` |  |
| `targetWidth` | `System.Int32` |  |
| `targetHeight` | `System.Int32` |  |
| `mipmap` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### SetAgentBasicData(WorkerSprite, Appearance)

```csharp
public void SetAgentBasicData(WorkerSprite set, Appearance appear)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `set` | `WorkerSprite.WorkerSprite` |  |
| `appear` | `Customizing.Appearance` |  |

### SpecialFindDir_Texture(string, ref DirectoryInfo, ref Texture2D)

```csharp
public bool SpecialFindDir_Texture(string name, ref DirectoryInfo info, ref Texture2D tex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `info` | `System.IO.DirectoryInfo` |  |
| `tex` | `UnityEngine.Texture2D` |  |

#### Returns

**Type:** System.Boolean
