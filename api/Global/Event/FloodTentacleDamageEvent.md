---
uid: Global.FloodTentacle.DamageEvent
canonical_path: /api/Global/Event/FloodTentacleDamageEvent
---

# Delegate FloodTentacle.DamageEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate void FloodTentacle.DamageEvent(UnitModel target)
```

## Constructors

### DamageEvent(object, IntPtr)

```csharp
public DamageEvent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(UnitModel, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(UnitModel target, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
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

### Invoke(UnitModel)

```csharp
public virtual void Invoke(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
