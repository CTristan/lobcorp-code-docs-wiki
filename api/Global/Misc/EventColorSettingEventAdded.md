---
uid: Global.EventColorSetting.EventAdded
canonical_path: /api/Global/Misc/EventColorSettingEventAdded
---

# Delegate EventColorSetting.EventAdded

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate void EventColorSetting.EventAdded()
```

## Constructors

### EventAdded(object, IntPtr)

```csharp
public EventAdded(object @object, IntPtr method)
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
