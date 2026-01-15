---
uid: GlobalBullet.GlobalBulletManager.BulletFunc
canonical_path: /api/GlobalBullet/GlobalBulletManager/BulletFunc
---

# Delegate GlobalBulletManager.BulletFunc

**Namespace:** [GlobalBullet](/api/GlobalBullet)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate void GlobalBulletManager.BulletFunc(UnitModel target)
```

## Constructors

### BulletFunc(object, IntPtr)

```csharp
public BulletFunc(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(UnitModel, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(UnitModel target, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
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

### Invoke(UnitModel)

```csharp
public virtual void Invoke(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
