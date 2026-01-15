---
uid: Global.StoryFadeUI.StoryFadeEnd
canonical_path: /api/Global/Misc/StoryFadeUIStoryFadeEnd
---

# Delegate StoryFadeUI.StoryFadeEnd

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StoryFadeUI.StoryFadeEnd(string nextStory)
```

## Constructors

### StoryFadeEnd(object, IntPtr)

```csharp
public StoryFadeEnd(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(string, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(string nextStory, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nextStory` | `System.String` |  |
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
public virtual void Invoke(string nextStory)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nextStory` | `System.String` |  |
