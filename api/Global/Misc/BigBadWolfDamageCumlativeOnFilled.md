---
uid: Global.BigBadWolf.DamageCumlative.OnFilled
canonical_path: /api/Global/Misc/BigBadWolfDamageCumlativeOnFilled
---

# Delegate BigBadWolf.DamageCumlative.OnFilled

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void BigBadWolf.DamageCumlative.OnFilled()
```

## Constructors

### OnFilled(object, IntPtr)

```csharp
public OnFilled(object @object, IntPtr method)
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
