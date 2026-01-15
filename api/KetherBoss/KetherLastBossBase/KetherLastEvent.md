---
uid: KetherBoss.KetherLastBossBase.KetherLastEvent
canonical_path: /api/KetherBoss/KetherLastBossBase/KetherLastEvent
---

# Delegate KetherLastBossBase.KetherLastEvent

**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void KetherLastBossBase.KetherLastEvent()
```

## Constructors

### KetherLastEvent(object, IntPtr)

```csharp
public KetherLastEvent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
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

### Invoke()

```csharp
public virtual void Invoke()
```
