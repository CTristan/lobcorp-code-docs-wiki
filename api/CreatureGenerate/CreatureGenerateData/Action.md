---
title: Action
description: 
published: true
date: 2026-07-16T21:37:19.004Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:53:48.297Z
---

# Delegate CreatureGenerateData.Action
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void CreatureGenerateData.Action(params object[] param)
```

A delegate to either [`CreatureGenerateData::OnlyAction`](/api/CreatureGenerate/CreatureGenerateData#onlyactionparams-object) or [`CreatureGenerateData::RemoveAction`](/api/CreatureGenerate/CreatureGenerateData#removeactionparams-object), for restricting abnormality selections on certain days.

## Constructors
### Action(object, IntPtr)
```csharp
public Action(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(object[], AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(object[] param, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |
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

### Invoke(params object[])
```csharp
public virtual void Invoke(params object[] param)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |







