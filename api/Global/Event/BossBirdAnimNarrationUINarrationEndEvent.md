---
uid: Global.BossBirdAnim.NarrationUI.NarrationEndEvent
canonical_path: /api/Global/Event/BossBirdAnimNarrationUINarrationEndEvent
---

# Delegate BossBirdAnim.NarrationUI.NarrationEndEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void BossBirdAnim.NarrationUI.NarrationEndEvent()
```

## Constructors

### NarrationEndEvent(object, IntPtr)

```csharp
public NarrationEndEvent(object @object, IntPtr method)
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
