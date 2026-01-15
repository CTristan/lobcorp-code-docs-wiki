---
uid: Global.AgentEventListenerDelegate
canonical_path: /api/Global/Misc/AgentEventListenerDelegate
---

# Delegate AgentEventListenerDelegate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void AgentEventListenerDelegate(params object[] param)
```

## Constructors

### AgentEventListenerDelegate(object, IntPtr)

```csharp
public AgentEventListenerDelegate(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(object[], AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(object[] param, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |
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

### Invoke(params object[])

```csharp
public virtual void Invoke(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |
