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

Loads and holds the lists of (default) [names](/api/Global/Misc/AgentName) for [agents](/api/Global/Worker/AgentModel). May do more...

Seems that names are 'used up' when given to an agent, and are then removed from the pool?
#INC 


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
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,AgentNameTypeInfo}

### _allTypeInfo_list

```csharp
private List<AgentNameTypeInfo> _allTypeInfo_list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _creditInfoPool

```csharp
private List<int> _creditInfoPool
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### _creditNameList

```csharp
private List<AgentNameTypeInfo> _creditNameList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _creditNameNotUsed

```csharp
private List<AgentName> _creditNameNotUsed
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _defaultInfoPool

```csharp
private List<int> _defaultInfoPool
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### _defaultNameList

```csharp
private List<AgentNameTypeInfo> _defaultNameList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentNameTypeInfo}

### _instance

```csharp
private static AgentNameList _instance
```
#INC


#### Field Value

**Type:** Global.AgentNameList

### _isLoaded

```csharp
private bool _isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### _list

```csharp
private List<AgentName> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _notUsed

```csharp
private List<AgentName> _notUsed
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### _uniqueCreditNameInfo

```csharp
private Dictionary<int, UniqueCreditAgentInfo> _uniqueCreditNameInfo
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,UniqueCreditAgentInfo}

### _uniqueCreditSearchTable

```csharp
private Dictionary<string, int> _uniqueCreditSearchTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### _used

```csharp
private List<AgentName> _used
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentName}

### creditAgentNameProb

```csharp
private float creditAgentNameProb
```
#INC


#### Field Value

**Type:** System.Single

### creditIndex

```csharp
private int creditIndex
```
#INC


#### Field Value

**Type:** System.Int32

### creditName_id_added

```csharp
public const int creditName_id_added = 10000
```
#INC


#### Field Value

**Type:** System.Int32

### customName_id_added

```csharp
public const int customName_id_added = 20000
```
#INC


#### Field Value

**Type:** System.Int32

### instId

```csharp
private int instId
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nameList` | `System.Collections.Generic.List{AgentName}` |  |

### AddCustomName(Dictionary<string, object>)

```csharp
public void AddCustomName(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### CheckCustomForOldSave(long)

```csharp
public static bool CheckCustomForOldSave(long id)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |

### GetCreditIndex()

```csharp
public int GetCreditIndex()
```
#INC


#### Returns

**Type:** System.Int32

### GetCustomName(int)

```csharp
public AgentName GetCustomName(int id)
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.AgentName

### GetName(int)

```csharp
public AgentName GetName(int id)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.AgentName

### GetNotUsedNameAsFake()

```csharp
public AgentName GetNotUsedNameAsFake()
```
#INC


#### Returns

**Type:** Global.AgentName

### GetRandomInfo()

```csharp
public AgentNameTypeInfo GetRandomInfo()
```
#INC


#### Returns

**Type:** Global.AgentNameTypeInfo

### GetRandomInfoFromPool(AgentNameType)

```csharp
public AgentNameTypeInfo GetRandomInfoFromPool(AgentNameType type)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.AgentName

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetUniqueCreditInfo(string)

```csharp
public UniqueCreditAgentInfo GetUniqueCreditInfo(string name)
```
#INC


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
#INC


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
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.AgentName[]` |  |

### InitializeCreditPool()

```csharp
private void InitializeCreditPool()
```
#INC


### InitializeDefaultPool()

```csharp
private void InitializeDefaultPool()
```
#INC


### InitializePool(List<int>, List<AgentNameTypeInfo>)

```csharp
private void InitializePool(List<int> targetPool, List<AgentNameTypeInfo> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPool` | `System.Collections.Generic.List{System.Int32}` |  |
| `data` | `System.Collections.Generic.List{AgentNameTypeInfo}` |  |

### InitNameTypes(AgentNameTypeInfo[], AgentNameTypeInfo[], UniqueCreditAgentInfo[])

```csharp
public void InitNameTypes(AgentNameTypeInfo[] defaultName, AgentNameTypeInfo[] creditName, UniqueCreditAgentInfo[] uniqueCreditAgent)
```
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnInit()

```csharp
public void OnInit()
```
#INC


### Print()

```csharp
public void Print()
```
#INC


### ReturnName(long)

```csharp
public void ReturnName(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### SetCustomName(string, int)

```csharp
public AgentName SetCustomName(string name, int id)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `Global.AgentName` |  |
