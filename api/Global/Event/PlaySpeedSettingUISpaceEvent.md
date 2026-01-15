---
uid: Global.PlaySpeedSettingUI.SpaceEvent
canonical_path: /api/Global/Event/PlaySpeedSettingUISpaceEvent
---

# Delegate PlaySpeedSettingUI.SpaceEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void PlaySpeedSettingUI.SpaceEvent(bool state)
```

## Constructors

### SpaceEvent(object, IntPtr)

```csharp
public SpaceEvent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(bool, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(bool state, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
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

### Invoke(bool)

```csharp
public virtual void Invoke(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
