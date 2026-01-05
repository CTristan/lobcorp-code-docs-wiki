# Class RecoilEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RecoilEffect
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RecoilEffect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RecoilEffect()

```csharp
public RecoilEffect()
```

## Fields

### maxTime

```csharp
public float maxTime
```

#### Field Value

**Type:** System.Single

### recoilCount

```csharp
public int recoilCount
```

#### Field Value

**Type:** System.Int32

### scale

```csharp
public float scale
```

#### Field Value

**Type:** System.Single

### targetTransform

```csharp
public Transform targetTransform
```

#### Field Value

**Type:** UnityEngine.Transform

## Methods

### GetArrow(int)

```csharp
public static RecoilArrow GetArrow(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.RecoilArrow

### GetVector(RecoilArrow, Vector2, float)

```csharp
public static Vector2 GetVector(RecoilArrow arrow, Vector2 initial, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `arrow` | `Global.RecoilArrow` |  |
| `initial` | `UnityEngine.Vector2` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector2

### GetVector(RecoilArrow, Vector3, float)

```csharp
public static Vector3 GetVector(RecoilArrow arrow, Vector3 initial, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `arrow` | `Global.RecoilArrow` |  |
| `initial` | `UnityEngine.Vector3` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector3

### MakeRecoilArrow(int)

```csharp
public static List<RecoilArrow> MakeRecoilArrow(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{RecoilArrow}
