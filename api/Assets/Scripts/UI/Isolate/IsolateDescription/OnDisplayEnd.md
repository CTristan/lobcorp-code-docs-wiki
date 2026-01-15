---
uid: Assets.Scripts.UI.Isolate.IsolateDescription.OnDisplayEnd
canonical_path: /api/Assets/Scripts/UI/Isolate/IsolateDescription/OnDisplayEnd
---

# Delegate IsolateDescription.OnDisplayEnd

**Namespace:** Assets . Scripts . UI . [Isolate](/api/Assets/Scripts/UI/Isolate)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void IsolateDescription.OnDisplayEnd(IsolateDescription i)
```

## Constructors

### OnDisplayEnd(object, IntPtr)

```csharp
public OnDisplayEnd(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(IsolateDescription, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(IsolateDescription i, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Assets.Scripts.UI.Isolate.IsolateDescription` |  |
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

### Invoke(IsolateDescription)

```csharp
public virtual void Invoke(IsolateDescription i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Assets.Scripts.UI.Isolate.IsolateDescription` |  |
