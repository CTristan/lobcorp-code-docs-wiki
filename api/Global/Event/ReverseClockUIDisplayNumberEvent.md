---
uid: Global.ReverseClockUI.DisplayNumberEvent
canonical_path: /api/Global/Event/ReverseClockUIDisplayNumberEvent
---

# Delegate ReverseClockUI.DisplayNumberEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void ReverseClockUI.DisplayNumberEvent(int i)
```

## Constructors

### DisplayNumberEvent(object, IntPtr)

```csharp
public DisplayNumberEvent(object @object, IntPtr method)
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
