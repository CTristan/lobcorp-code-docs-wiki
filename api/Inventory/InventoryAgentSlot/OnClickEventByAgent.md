---
uid: Inventory.InventoryAgentSlot.OnClickEventByAgent
canonical_path: /api/Inventory/InventoryAgentSlot/OnClickEventByAgent
---

# Delegate InventoryAgentSlot.OnClickEventByAgent

**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void InventoryAgentSlot.OnClickEventByAgent(InventoryAgentSlot slot)
```

## Constructors

### OnClickEventByAgent(object, IntPtr)

```csharp
public OnClickEventByAgent(object @object, IntPtr method)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods

### BeginInvoke(InventoryAgentSlot, AsyncCallback, object)

```csharp
public virtual IAsyncResult BeginInvoke(InventoryAgentSlot slot, AsyncCallback callback, object @object)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Inventory.InventoryAgentSlot` |  |
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

### Invoke(InventoryAgentSlot)

```csharp
public virtual void Invoke(InventoryAgentSlot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Inventory.InventoryAgentSlot` |  |
