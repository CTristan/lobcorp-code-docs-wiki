# Delegate StoryUI.AddFilterFunc

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StoryUI.AddFilterFunc(StoryFilterParameter param)
```

## Constructors

### AddFilterFunc(object, IntPtr)

```csharp
public AddFilterFunc(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(StoryFilterParameter, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(StoryFilterParameter param, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |
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

### Invoke(StoryFilterParameter)

```csharp
public virtual void Invoke(StoryFilterParameter param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `Global.StoryFilterParameter` |  |
