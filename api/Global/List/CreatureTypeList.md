---
uid: Global.CreatureTypeList
canonical_path: /api/Global/List/CreatureTypeList
---

# Class CreatureTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureTypeList()

```csharp
private CreatureTypeList()
```

## Fields

### _instance

```csharp
private static CreatureTypeList _instance
```

#### Field Value

**Type:** Global.CreatureTypeList

### _list

```csharp
private List<CreatureTypeInfo> _list
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureTypeInfo}

### _loaded

```csharp
private bool _loaded
```

#### Field Value

**Type:** System.Boolean

### _specialTipSizeDic

```csharp
private Dictionary<long, int> _specialTipSizeDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,System.Int32}

### _tableList

```csharp
private List<CreatureSpecialSkillTipTable> _tableList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureSpecialSkillTipTable}

## Properties

### instance

```csharp
public static CreatureTypeList instance { get; }
```

#### Property Value

**Type:** Global.CreatureTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public CreatureTypeInfo GetData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureTypeInfo

### GetList()

```csharp
public CreatureTypeInfo[] GetList()
```

#### Returns

**Type:** Global.CreatureTypeInfo[]

### GetSkillTipData(long)

```csharp
public CreatureSpecialSkillTipTable GetSkillTipData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureSpecialSkillTipTable

### GetSpecialSkillSize(long)

```csharp
public int GetSpecialSkillSize(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Int32

### GetTable()

```csharp
public CreatureSpecialSkillTipTable[] GetTable()
```

#### Returns

**Type:** Global.CreatureSpecialSkillTipTable[]

### Init(CreatureTypeInfo[], CreatureSpecialSkillTipTable[], Dictionary<long, int>)

```csharp
public void Init(CreatureTypeInfo[] list, CreatureSpecialSkillTipTable[] table, Dictionary<long, int> specialTipSize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.CreatureTypeInfo[]` |  |
| `table` | `Global.CreatureSpecialSkillTipTable[]` |  |
| `specialTipSize` | `System.Collections.Generic.Dictionary{System.Int64,System.Int32}` |  |

### ResetSkillTipTable()

```csharp
public void ResetSkillTipTable()
```
