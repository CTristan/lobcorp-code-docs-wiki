---
uid: Global.ChokhmahBossBase.TV_Vhs
canonical_path: /api/Global/Misc/ChokhmahBossBaseTVVhs
---

# Class ChokhmahBossBase.TV_Vhs

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChokhmahBossBase.TV_Vhs : ChokhmahBossBase.CameraFilterValue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ChokhmahBossBase.CameraFilterValue](/api/Global/Misc/ChokhmahBossBaseCameraFilterValue) → ChokhmahBossBase.TV_Vhs

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TV_Vhs()

```csharp
public TV_Vhs()
```

## Fields

### calibrage

```csharp
public float calibrage
```

#### Field Value

**Type:** System.Single

### cryptage

```csharp
public float cryptage
```

#### Field Value

**Type:** System.Single

### parasite

```csharp
public float parasite
```

#### Field Value

**Type:** System.Single

### whiteparasite

```csharp
public float whiteparasite
```

#### Field Value

**Type:** System.Single

## Methods

### Lerp<T>(T, float)

```csharp
public override T Lerp<T>(T v2, float rate) where T : ChokhmahBossBase.CameraFilterValue
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v2` | `{T}` |  |
| `rate` | `System.Single` |  |

#### Returns

**Type:** {T}

### SetFilterValue(CameraFilterPack_TV_VHS)

```csharp
public void SetFilterValue(CameraFilterPack_TV_VHS filter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `filter` | `Global.CameraFilterPack_TV_VHS` |  |
