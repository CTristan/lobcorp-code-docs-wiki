---
uid: Global.Drop.OnDropEvent
canonical_path: /api/Global/Event/DropOnDropEvent
---

# Delegate Drop.OnDropEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate bool Drop.OnDropEvent(params object[] param)
```

## Constructors

### OnDropEvent(object, IntPtr)

```csharp
public OnDropEvent(object @object, IntPtr method)
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
public virtual bool EndInvoke(IAsyncResult result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

#### Returns

**Type:** System.Boolean

### Invoke(params object[])

```csharp
public virtual bool Invoke(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.Boolean
