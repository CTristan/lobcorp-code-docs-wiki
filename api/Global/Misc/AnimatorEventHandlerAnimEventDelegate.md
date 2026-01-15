---
uid: Global.AnimatorEventHandler.AnimEventDelegate
canonical_path: /api/Global/Misc/AnimatorEventHandlerAnimEventDelegate
---

# Delegate AnimatorEventHandler.AnimEventDelegate

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void AnimatorEventHandler.AnimEventDelegate(int i)
```

## Constructors

### AnimEventDelegate(object, IntPtr)

```csharp
public AnimEventDelegate(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(int, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(int i, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
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

### Invoke(int)

```csharp
public virtual void Invoke(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
