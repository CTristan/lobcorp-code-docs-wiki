# Delegate LaserParticleEffect.OnArrivedEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void LaserParticleEffect.OnArrivedEvent(BossBird.LaserAttackTargetData data)
```

## Constructors

### OnArrivedEvent(object, IntPtr)

```csharp
public OnArrivedEvent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(LaserAttackTargetData, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(BossBird.LaserAttackTargetData data, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBird.LaserAttackTargetData` |  |
| `callback` | `System.AsyncCallback` |  |
| `object` | `System.Object` |  |

#### Returns

**Type:** System.IAsyncResult

### EndInvoke(IAsyncResult)

```csharp
public virtual void EndInvoke(IAsyncResult result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

### Invoke(LaserAttackTargetData)

```csharp
public virtual void Invoke(BossBird.LaserAttackTargetData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBird.LaserAttackTargetData` |  |
