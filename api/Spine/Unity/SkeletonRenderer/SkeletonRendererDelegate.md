---
uid: Spine.Unity.SkeletonRenderer.SkeletonRendererDelegate
canonical_path: /api/Spine/Unity/SkeletonRenderer/SkeletonRendererDelegate
---

# Delegate SkeletonRenderer.SkeletonRendererDelegate

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void SkeletonRenderer.SkeletonRendererDelegate(SkeletonRenderer skeletonRenderer)
```

## Constructors

### SkeletonRendererDelegate(object, IntPtr)

```csharp
public SkeletonRendererDelegate(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(SkeletonRenderer, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(SkeletonRenderer skeletonRenderer, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonRenderer` | `Spine.Unity.SkeletonRenderer` |  |
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

### Invoke(SkeletonRenderer)

```csharp
public virtual void Invoke(SkeletonRenderer skeletonRenderer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonRenderer` | `Spine.Unity.SkeletonRenderer` |  |
