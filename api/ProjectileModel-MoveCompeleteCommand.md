# Delegate ProjectileModel.MoveCompeleteCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void ProjectileModel.MoveCompeleteCommand(ProjectileModel proj)
```

## Constructors

### MoveCompeleteCommand(object, IntPtr)

```csharp
public MoveCompeleteCommand(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(ProjectileModel, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(ProjectileModel proj, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `proj` | `Global.ProjectileModel` |  |
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

### Invoke(ProjectileModel)

```csharp
public virtual void Invoke(ProjectileModel proj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `proj` | `Global.ProjectileModel` |  |
