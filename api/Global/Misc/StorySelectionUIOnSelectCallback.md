---
uid: Global.StorySelectionUI.OnSelectCallback
canonical_path: /api/Global/Misc/StorySelectionUIOnSelectCallback
---

# Delegate StorySelectionUI.OnSelectCallback

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StorySelectionUI.OnSelectCallback(int index)
```

## Constructors

### OnSelectCallback(object, IntPtr)

```csharp
public OnSelectCallback(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(int, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(int index, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
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
public virtual void Invoke(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
