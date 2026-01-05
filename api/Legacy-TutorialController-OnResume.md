# Delegate TutorialController.OnResume

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void TutorialController.OnResume(PAUSECALL caller)
```

## Constructors

### OnResume(object, IntPtr)

```csharp
public OnResume(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(PAUSECALL, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(PAUSECALL caller, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |
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

### Invoke(PAUSECALL)

```csharp
public virtual void Invoke(PAUSECALL caller)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.PAUSECALL` |  |
