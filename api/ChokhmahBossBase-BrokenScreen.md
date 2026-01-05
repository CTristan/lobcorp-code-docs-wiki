# Class ChokhmahBossBase.BrokenScreen

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChokhmahBossBase.BrokenScreen : ChokhmahBossBase.CameraFilterValue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ChokhmahBossBase.CameraFilterValue](/api/ChokhmahBossBase-CameraFilterValue) → ChokhmahBossBase.BrokenScreen

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BrokenScreen()

```csharp
public BrokenScreen()
```

## Fields

### fade

```csharp
public float fade
```

#### Field Value

**Type:** System.Single

### shadow

```csharp
public float shadow
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

### SetFilterValue(CameraFilterPack_Broken_Screen)

```csharp
public void SetFilterValue(CameraFilterPack_Broken_Screen filter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `filter` | `Global.CameraFilterPack_Broken_Screen` |  |
