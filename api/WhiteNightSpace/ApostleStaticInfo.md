---
uid: WhiteNightSpace.ApostleStaticInfo
canonical_path: /api/WhiteNightSpace/ApostleStaticInfo
---

# Class ApostleStaticInfo

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class ApostleStaticInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ApostleStaticInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### GuardApostleAry

```csharp
public static int[] GuardApostleAry
```

#### Field Value

**Type:** System.Int32[]

### ScytheApostleDead

```csharp
public const string ScytheApostleDead = "ScytheApostleDead"
```

#### Field Value

**Type:** System.String

### ScytheApostlePrefab

```csharp
public const string ScytheApostlePrefab = "Unit/CreatureAnimator/Apostle/ScytheApostleAnim"
```

#### Field Value

**Type:** System.String

### ScytheApostleScript

```csharp
public const string ScytheApostleScript = "WhiteNightSpace.ScytheApostle"
```

#### Field Value

**Type:** System.String

### SpearApostleDead

```csharp
public const string SpearApostleDead = "SpearApostleDead"
```

#### Field Value

**Type:** System.String

### SpearApostlePrefab

```csharp
public const string SpearApostlePrefab = "Unit/CreatureAnimator/Apostle/SpearApostleAnim"
```

#### Field Value

**Type:** System.String

### SpearApostleScript

```csharp
public const string SpearApostleScript = "WhiteNightSpace.SpearApostle"
```

#### Field Value

**Type:** System.String

### WandApostleDead

```csharp
public const string WandApostleDead = "WandApostleDead"
```

#### Field Value

**Type:** System.String

### WandApostlePrefab

```csharp
public const string WandApostlePrefab = "Unit/CreatureAnimator/Apostle/WandApostleAnim"
```

#### Field Value

**Type:** System.String

### WandApostleScript

```csharp
public const string WandApostleScript = "WhiteNightSpace.WandApostle"
```

#### Field Value

**Type:** System.String

## Methods

### GetApostleGenInfo(ApostleType, out string, out string)

```csharp
public static void GetApostleGenInfo(ApostleType type, out string script, out string prefab)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WhiteNightSpace.ApostleType` |  |
| `script` | `System.String` |  |
| `prefab` | `System.String` |  |

### GetApostleType(int)

```csharp
public static ApostleType GetApostleType(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** WhiteNightSpace.ApostleType
