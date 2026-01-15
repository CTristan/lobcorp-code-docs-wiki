---
uid: Global.CreatureObserveInfoModel
canonical_path: /api/Global/Model/CreatureObserveInfoModel
---

# Class CreatureObserveInfoModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureObserveInfoModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureObserveInfoModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureObserveInfoModel(long)

```csharp
public CreatureObserveInfoModel(long creatureTypeId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureTypeId` | `System.Int64` |  |

## Fields

### _metaInfo

```csharp
private CreatureTypeInfo _metaInfo
```

#### Field Value

**Type:** Global.CreatureTypeInfo

### creatureTypeId

```csharp
public long creatureTypeId
```

#### Field Value

**Type:** System.Int64

### cubeNum

```csharp
public int cubeNum
```

#### Field Value

**Type:** System.Int32

### observeProgress

```csharp
public int observeProgress
```

#### Field Value

**Type:** System.Int32

### observeRegions

```csharp
private Dictionary<string, ObserveRegion> observeRegions
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,ObserveRegion}

### totalKitUseCount

```csharp
public int totalKitUseCount
```

#### Field Value

**Type:** System.Int32

### totalKitUseTime

```csharp
public float totalKitUseTime
```

#### Field Value

**Type:** System.Single

## Methods

### AddObserveRegionData(Dictionary<string, object>)

```csharp
private void AddObserveRegionData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### GetObservationLevel()

```csharp
public int GetObservationLevel()
```

#### Returns

**Type:** System.Int32

### GetObserveCost(string)

```csharp
public int GetObserveCost(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.Int32

### GetObserveRegion(string, out ObserveRegion)

```csharp
public bool GetObserveRegion(string key, out ObserveRegion output)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `output` | `Global.ObserveRegion` |  |

#### Returns

**Type:** System.Boolean

### GetObserveRegionData(Dictionary<string, object>)

```csharp
private void GetObserveRegionData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### GetObserveState(string)

```csharp
public bool GetObserveState(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### GetRegion(string, out ObserveRegion)

```csharp
public bool GetRegion(string key, out ObserveRegion region)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `region` | `Global.ObserveRegion` |  |

#### Returns

**Type:** System.Boolean

### GetSaveGlobalData()

```csharp
public Dictionary<string, object> GetSaveGlobalData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### InitData()

```csharp
public void InitData()
```

### InitObserveRegion(List<ObserveInfoData>)

```csharp
public void InitObserveRegion(List<ObserveInfoData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{ObserveInfoData}` |  |

### IsMaxObserved()

```csharp
public bool IsMaxObserved()
```

#### Returns

**Type:** System.Boolean

### LoadGlobalData(Dictionary<string, object>)

```csharp
public void LoadGlobalData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### ObserveAll(params string[])

```csharp
public void ObserveAll(params string[] ignore)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ignore` | `System.String[]` |  |

### OnObserveRegion(string)

```csharp
public void OnObserveRegion(string region)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |

### OnResetObserve()

```csharp
public void OnResetObserve()
```

### Transaction(int)

```csharp
public void Transaction(int trans)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trans` | `System.Int32` |  |
