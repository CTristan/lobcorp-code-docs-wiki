---
uid: Spine.Unity.SkeletonRenderer.InstructionDelegate
canonical_path: /api/Spine/Unity/SkeletonRenderer/InstructionDelegate
---

# Delegate SkeletonRenderer.InstructionDelegate

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void SkeletonRenderer.InstructionDelegate(SkeletonRendererInstruction instruction)
```

## Constructors

### InstructionDelegate(object, IntPtr)

```csharp
public InstructionDelegate(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(SkeletonRendererInstruction, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(SkeletonRendererInstruction instruction, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instruction` | `Spine.Unity.SkeletonRendererInstruction` |  |
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

### Invoke(SkeletonRendererInstruction)

```csharp
public virtual void Invoke(SkeletonRendererInstruction instruction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instruction` | `Spine.Unity.SkeletonRendererInstruction` |  |
