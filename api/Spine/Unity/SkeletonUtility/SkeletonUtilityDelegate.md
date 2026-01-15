---
uid: Spine.Unity.SkeletonUtility.SkeletonUtilityDelegate
canonical_path: /api/Spine/Unity/SkeletonUtility/SkeletonUtilityDelegate
---

# Delegate SkeletonUtility.SkeletonUtilityDelegate

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void SkeletonUtility.SkeletonUtilityDelegate()
```

## Constructors

### SkeletonUtilityDelegate(object, IntPtr)

```csharp
public SkeletonUtilityDelegate(object @object, IntPtr method)
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
