---
uid: Global.AgentNameList
canonical_path: /api/Global/List/AgentNameList
---

# Class AgentNameList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentNameList : ISerializablePlayData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentNameList

## Implements
[ISerializablePlayData](/api/Global/Misc/ISerializablePlayData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentNameList()

```csharp
public AgentNameList()
```

## Fields

### _allTypeInfo

```csharp
private Dictionary<int, AgentNameTypeInfo> _allTypeInfo
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,AgentNameTypeInfo}

### _allTypeInfo_list

```csharp
private List<AgentNameTypeInfo> _allTypeInfo_list
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _creditInfoPool

```csharp
private List<int> _creditInfoPool
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### _creditNameList

```csharp
private List<AgentNameTypeInfo> _creditNameList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _creditNameNotUsed

```csharp
private List<AgentName> _creditNameNotUsed
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _defaultInfoPool

```csharp
private List<int> _defaultInfoPool
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### _defaultNameList

```csharp
private List<AgentNameTypeInfo> _defaultNameList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _instance

```csharp
private static AgentNameList _instance
```

#### Field Value

**Type:** Global.AgentNameList

### _isLoaded

```csharp
private bool _isLoaded
```

#### Field Value

**Type:** System.Boolean

### _list

```csharp
private List<AgentName> _list
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _notUsed

```csharp
private List<AgentName> _notUsed
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _uniqueCreditNameInfo

```csharp
private Dictionary<int, UniqueCreditAgentInfo> _uniqueCreditNameInfo
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,UniqueCreditAgentInfo}

### _uniqueCreditSearchTable

```csharp
private Dictionary<string, int> _uniqueCreditSearchTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### _used

```csharp
private List<AgentName> _used
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### creditAgentNameProb

```csharp
private float creditAgentNameProb
```

#### Field Value

**Type:** System.Single

### creditIndex

```csharp
private int creditIndex
```

#### Field Value

**Type:** System.Int32

### creditName_id_added

```csharp
public const int creditName_id_added = 10000
```

#### Field Value

**Type:** System.Int32

### customName_id_added

```csharp
public const int customName_id_added = 20000
```

#### Field Value

**Type:** System.Int32

### instId

```csharp
private int instId
```

#### Field Value

**Type:** System.Int32

## Properties

### currentMax

```csharp
public int currentMax { get; }
```

#### Property Value

**Type:** System.Int32

### instance

```csharp
public static AgentNameList instance { get; }
```

#### Property Value

**Type:** Global.AgentNameList

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddCreditNames(List<AgentName>)

```csharp
public void AddCreditNames(List<AgentName> nameList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nameList` | `System.Collections.Generic.List{AgentName}` |  |

### AddCustomName(Dictionary<string, object>)

```csharp
public void AddCustomName(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### CheckCustomForOldSave(long)

```csharp
public static bool CheckCustomForOldSave(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### ExtractFromPool(AgentName)

```csharp
public void ExtractFromPool(AgentName name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |

### GetCreditIndex()

```csharp
public int GetCreditIndex()
```

#### Returns

**Type:** System.Int32

### GetCustomName(int)

```csharp
public AgentName GetCustomName(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentName

### GetCustomName(string)

```csharp
public AgentName GetCustomName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.AgentName

### GetCustomNameByInfo(string, int)

```csharp
public AgentName GetCustomNameByInfo(string name, int nameId = -1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `nameId` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentName

### GetFakeNameByInfo()

```csharp
public AgentName GetFakeNameByInfo()
```

#### Returns

**Type:** Global.AgentName

### GetName(int)

```csharp
public AgentName GetName(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentName

### GetNameByInfo(int)

```csharp
public AgentName GetNameByInfo(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentName

### GetNotUsedName()

```csharp
public AgentName GetNotUsedName()
```

#### Returns

**Type:** Global.AgentName

### GetNotUsedNameAsFake()

```csharp
public AgentName GetNotUsedNameAsFake()
```

#### Returns

**Type:** Global.AgentName

### GetRandomInfo()

```csharp
public AgentNameTypeInfo GetRandomInfo()
```

#### Returns

**Type:** Global.AgentNameTypeInfo

### GetRandomInfoFromPool(AgentNameType)

```csharp
public AgentNameTypeInfo GetRandomInfoFromPool(AgentNameType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.AgentNameType` |  |

#### Returns

**Type:** Global.AgentNameTypeInfo

### GetRandomInfoIdFromPool(AgentNameType)

```csharp
private int GetRandomInfoIdFromPool(AgentNameType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.AgentNameType` |  |

#### Returns

**Type:** System.Int32

### GetRandomNameByInfo()

```csharp
public AgentName GetRandomNameByInfo()
```

#### Returns

**Type:** Global.AgentName

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetUniqueCreditInfo(string)

```csharp
public UniqueCreditAgentInfo GetUniqueCreditInfo(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.UniqueCreditAgentInfo

### GetUsedName(string)

```csharp
public AgentName GetUsedName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.AgentName

### Init(AgentName[])

```csharp
public void Init(AgentName[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.AgentName[]` |  |

### InitializeCreditPool()

```csharp
private void InitializeCreditPool()
```

### InitializeDefaultPool()

```csharp
private void InitializeDefaultPool()
```

### InitializePool(List<int>, List<AgentNameTypeInfo>)

```csharp
private void InitializePool(List<int> targetPool, List<AgentNameTypeInfo> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPool` | `System.Collections.Generic.List{System.Int32}` |  |
| `data` | `System.Collections.Generic.List{AgentNameTypeInfo}` |  |

### InitNameTypes(AgentNameTypeInfo[], AgentNameTypeInfo[], UniqueCreditAgentInfo[])

```csharp
public void InitNameTypes(AgentNameTypeInfo[] defaultName, AgentNameTypeInfo[] creditName, UniqueCreditAgentInfo[] uniqueCreditAgent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defaultName` | `Global.AgentNameTypeInfo[]` |  |
| `creditName` | `Global.AgentNameTypeInfo[]` |  |
| `uniqueCreditAgent` | `Global.UniqueCreditAgentInfo[]` |  |

### IsUniqueName(string)

```csharp
public bool IsUniqueName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnInit()

```csharp
public void OnInit()
```

### Print()

```csharp
public void Print()
```

### ReturnName(long)

```csharp
public void ReturnName(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### SetCustomName(string, int)

```csharp
public AgentName SetCustomName(string name, int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentName

### SetFakeAsRealUsed(AgentName)

```csharp
public void SetFakeAsRealUsed(AgentName name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |
