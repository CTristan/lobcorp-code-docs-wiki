# Class InventoryModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class InventoryModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → InventoryModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### InventoryModel()

```csharp
public InventoryModel()
```

## Fields

### _nextInstanceId

```csharp
public long _nextInstanceId
```

#### Field Value

**Type:** System.Int64

## Properties

### equipList

```csharp
public List<EquipmentModel> equipList { get; }
```

#### Property Value

**Type:** System.Collections.Generic.List{EquipmentModel}

### Instance

```csharp
public static InventoryModel Instance { get; }
```

#### Property Value

**Type:** Global.InventoryModel

## Methods

### CheckEquipmentCount(int)

```csharp
public bool CheckEquipmentCount(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### CreateEquipment(int)

```csharp
public EquipmentModel CreateEquipment(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.EquipmentModel

### CreateEquipment(int, long)

```csharp
public EquipmentModel CreateEquipment(int id, long instanceId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `instanceId` | `System.Int64` |  |

#### Returns

**Type:** Global.EquipmentModel

### CreateEquipmentForcely(int)

```csharp
public EquipmentModel CreateEquipmentForcely(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.EquipmentModel

### GetAllEquipmentList()

```csharp
public IList<EquipmentModel> GetAllEquipmentList()
```

#### Returns

**Type:** System.Collections.Generic.IList{EquipmentModel}

### GetEquipCount(int, out int, out int)

```csharp
public bool GetEquipCount(int id, out int current, out int max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `current` | `System.Int32` |  |
| `max` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### GetEquipment(long)

```csharp
public EquipmentModel GetEquipment(long instanceId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

#### Returns

**Type:** Global.EquipmentModel

### GetEquipmentListByTypeInfo()

```csharp
public Dictionary<int, List<EquipmentModel>> GetEquipmentListByTypeInfo()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{EquipmentModel}}

### GetGlobalSaveData()

```csharp
public Dictionary<string, object> GetGlobalSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWaitingEquipmentList()

```csharp
public IList<EquipmentModel> GetWaitingEquipmentList()
```

#### Returns

**Type:** System.Collections.Generic.IList{EquipmentModel}

### Init()

```csharp
public void Init()
```

### LoadGlobalData(Dictionary<string, object>)

```csharp
public void LoadGlobalData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnReleaseGame()

```csharp
public void OnReleaseGame()
```

### RemoveAllDlcEquipment()

```csharp
public bool RemoveAllDlcEquipment()
```

#### Returns

**Type:** System.Boolean

### RemoveEquipment(EquipmentModel)

```csharp
public void RemoveEquipment(EquipmentModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EquipmentModel` |  |
