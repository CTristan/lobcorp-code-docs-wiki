---
uid: Global.StoryUI.StoryEndFunc
canonical_path: /api/Global/Misc/StoryUIStoryEndFunc
---

# Delegate StoryUI.StoryEndFunc

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StoryUI.StoryEndFunc()
```

## Constructors

### StoryEndFunc(object, IntPtr)

```csharp
public StoryEndFunc(object @object, IntPtr method)
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
