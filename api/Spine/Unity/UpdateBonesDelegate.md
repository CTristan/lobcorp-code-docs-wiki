---
uid: Spine.Unity.UpdateBonesDelegate
canonical_path: /api/Spine/Unity/UpdateBonesDelegate
---

# Delegate UpdateBonesDelegate

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void UpdateBonesDelegate(ISkeletonAnimation animated)
```

## Constructors

### UpdateBonesDelegate(object, IntPtr)

```csharp
public UpdateBonesDelegate(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(ISkeletonAnimation, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(ISkeletonAnimation animated, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animated` | `Spine.Unity.ISkeletonAnimation` |  |
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

### Invoke(ISkeletonAnimation)

```csharp
public virtual void Invoke(ISkeletonAnimation animated)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animated` | `Spine.Unity.ISkeletonAnimation` |  |
