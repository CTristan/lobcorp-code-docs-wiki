# Class BackGroundMoveEffect

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BackGroundMoveEffect : KetherLastEffectBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [KetherLastEffectBase](/api/KetherBoss-KetherLastEffectBase) → BackGroundMoveEffect

## Inherited Members
[type](/api/KetherBoss-KetherLastEffectBase#type), [OnStart()](/api/KetherBoss-KetherLastEffectBase#onstart), [OnDestroy()](/api/KetherBoss-KetherLastEffectBase#ondestroy), [Terminate()](/api/KetherBoss-KetherLastEffectBase#terminate), [BossBase](/api/KetherBoss-KetherLastEffectBase#bossbase), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BackGroundMoveEffect(KetherLastBossBase)

```csharp
public BackGroundMoveEffect(KetherLastBossBase bossBase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `KetherBoss.KetherLastBossBase` |  |

## Fields

### _changeAction

```csharp
public BackGroundMoveEffect.ChangeBackgournd _changeAction
```

#### Field Value

**Type:** KetherBoss.BackGroundMoveEffect.ChangeBackgournd

## Methods

### ApplyFrameChangeEvent(ChangeBackgournd)

```csharp
public void ApplyFrameChangeEvent(BackGroundMoveEffect.ChangeBackgournd changeBackgournd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `changeBackgournd` | `KetherBoss.BackGroundMoveEffect.ChangeBackgournd` |  |

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### StartVertiaclMovement(float, bool)

```csharp
public void StartVertiaclMovement(float speed, bool eqEanble = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |
| `eqEanble` | `System.Boolean` |  |

### Update()

```csharp
public override void Update()
```
