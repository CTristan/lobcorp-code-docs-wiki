---
uid: Global.InventoryModel
canonical_path: /api/Global/Model/InventoryModel
---

# Class InventoryModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class InventoryModel
```
Maintains the list of EGO in the facility.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → InventoryModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InventoryModel()

```csharp
public InventoryModel()
```

## Fields

### _equipList

```csharp
private List<EquipmentModel> _equipList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EquipmentModel}

### _instance

```csharp
private static InventoryModel _instance
```
#INC


#### Field Value

**Type:** Global.InventoryModel

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
#INC


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
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.IList{EquipmentModel}

### GetEquipCount(int, out int, out int)

```csharp
public bool GetEquipCount(int id, out int current, out int max)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{EquipmentModel}}

### GetGlobalSaveData()

```csharp
public Dictionary<string, object> GetGlobalSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWaitingEquipmentList()

```csharp
public IList<EquipmentModel> GetWaitingEquipmentList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{EquipmentModel}

### Init()

```csharp
public void Init()
```
#INC
#code-generated


### LoadGlobalData(Dictionary<string, object>)

```csharp
public void LoadGlobalData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnReleaseGame()

```csharp
public void OnReleaseGame()
```
#INC


### RemoveAllDlcEquipment()

```csharp
public bool RemoveAllDlcEquipment()
```
#INC


#### Returns

**Type:** System.Boolean

### RemoveEquipment(EquipmentModel)

```csharp
public void RemoveEquipment(EquipmentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EquipmentModel` |  |
