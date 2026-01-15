---
uid: Global.StorySeedUI.StorySeedEnd
canonical_path: /api/Global/Misc/StorySeedUIStorySeedEnd
---

# Delegate StorySeedUI.StorySeedEnd

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StorySeedUI.StorySeedEnd(string angelaStory)
```

## Constructors

### StorySeedEnd(object, IntPtr)

```csharp
public StorySeedEnd(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(string, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(string angelaStory, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angelaStory` | `System.String` |  |
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

### Invoke(string)

```csharp
public virtual void Invoke(string angelaStory)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angelaStory` | `System.String` |  |
