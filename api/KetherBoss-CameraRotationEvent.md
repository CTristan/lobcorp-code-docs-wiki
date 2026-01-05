# Class CameraRotationEvent

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CameraRotationEvent : KetherLastEffectBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss-KetherLastEffectBase) → CameraRotationEvent

## Inherited Members
[type](/api/KetherBoss-KetherLastEffectBase#type), [FixedUpdate()](/api/KetherBoss-KetherLastEffectBase#fixedupdate), [OnDestroy()](/api/KetherBoss-KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss-KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss-KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CameraRotationEvent(KetherLastBossBase)

```csharp
public CameraRotationEvent(KetherLastBossBase bossBase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Methods

### OnStart()

```csharp
public override void OnStart()
```

### SetCameraRotation(float)

```csharp
public void SetCameraRotation(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### StartRotation(int)

```csharp
public void StartRotation(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### Update()

```csharp
public override void Update()
```
