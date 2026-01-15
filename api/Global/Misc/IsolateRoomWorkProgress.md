---
uid: Global.IsolateRoom.WorkProgress
canonical_path: /api/Global/Misc/IsolateRoomWorkProgress
---

# Class IsolateRoom.WorkProgress

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IsolateRoom.WorkProgress
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IsolateRoom.WorkProgress

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkProgress(GameObject, RectTransform, RectTransform, Text, Image)

```csharp
public WorkProgress(GameObject root, RectTransform Success, RectTransform Fail, Text CubeText, Image CubeTextFill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `root` | `UnityEngine.GameObject` |  |
| `Success` | `UnityEngine.RectTransform` |  |
| `Fail` | `UnityEngine.RectTransform` |  |
| `CubeText` | `UnityEngine.UI.Text` |  |
| `CubeTextFill` | `UnityEngine.UI.Image` |  |

## Fields

### _failIndex

```csharp
private int _failIndex
```

#### Field Value

**Type:** System.Int32

### _index

```csharp
private int _index
```

#### Field Value

**Type:** System.Int32

### _max

```csharp
private int _max
```

#### Field Value

**Type:** System.Int32

### _spacing

```csharp
private const float _spacing = 30
```

#### Field Value

**Type:** System.Single

### _successIndex

```csharp
private int _successIndex
```

#### Field Value

**Type:** System.Int32

### ActiveContorl

```csharp
public GameObject ActiveContorl
```

#### Field Value

**Type:** UnityEngine.GameObject

### CubeTextFill

```csharp
public Image CubeTextFill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentTotalCube

```csharp
public Text CurrentTotalCube
```

#### Field Value

**Type:** UnityEngine.UI.Text

### FailLayout

```csharp
public GridLayoutGroup FailLayout
```

#### Field Value

**Type:** UnityEngine.UI.GridLayoutGroup

### FailObject

```csharp
public List<GameObject> FailObject
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### FailParent

```csharp
public RectTransform FailParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### SuccessLayout

```csharp
public GridLayoutGroup SuccessLayout
```

#### Field Value

**Type:** UnityEngine.UI.GridLayoutGroup

### SuccessObject

```csharp
public List<GameObject> SuccessObject
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### SuccessParent

```csharp
public RectTransform SuccessParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

## Methods

### AddBar(bool)

```csharp
public void AddBar(bool isSuccess)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isSuccess` | `System.Boolean` |  |

### GenerateText(int)

```csharp
public string GenerateText(int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetResultCount()

```csharp
public int GetResultCount()
```

#### Returns

**Type:** System.Int32

### GetResultText()

```csharp
public string GetResultText()
```

#### Returns

**Type:** System.String

### Init(CreatureModel, GameObject, GameObject)

```csharp
public void Init(CreatureModel creature, GameObject success, GameObject fail)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `success` | `UnityEngine.GameObject` |  |
| `fail` | `UnityEngine.GameObject` |  |

### InitializeState()

```csharp
public void InitializeState()
```

### InitSetting(GameObject, Transform)

```csharp
private void InitSetting(GameObject target, Transform parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `UnityEngine.GameObject` |  |
| `parent` | `UnityEngine.Transform` |  |

### SetVisible(bool)

```csharp
public void SetVisible(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
