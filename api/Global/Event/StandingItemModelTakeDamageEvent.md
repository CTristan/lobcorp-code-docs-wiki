---
uid: Global.StandingItemModel.TakeDamageEvent
canonical_path: /api/Global/Event/StandingItemModelTakeDamageEvent
---

# Delegate StandingItemModel.TakeDamageEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate bool StandingItemModel.TakeDamageEvent(UnitModel target, float damage)
```

## Constructors

### TakeDamageEvent(object, IntPtr)

```csharp
public TakeDamageEvent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(UnitModel, float, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(UnitModel target, float damage, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |
| `callback` | `System.AsyncCallback` |  |
| `object` | `System.Object` |  |

#### Returns

**Type:** System.IAsyncResult

### EndInvoke(IAsyncResult)

```csharp
public virtual bool EndInvoke(IAsyncResult result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

#### Returns

**Type:** System.Boolean

### Invoke(UnitModel, float)

```csharp
public virtual bool Invoke(UnitModel target, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

#### Returns

**Type:** System.Boolean
