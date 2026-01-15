---
uid: GeburahBoss.GeburahEventCalled
canonical_path: /api/GeburahBoss/GeburahEventCalled
---

# Delegate GeburahEventCalled

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void GeburahEventCalled(int i)
```

## Constructors

### GeburahEventCalled(object, IntPtr)

```csharp
public GeburahEventCalled(object @object, IntPtr method)
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
