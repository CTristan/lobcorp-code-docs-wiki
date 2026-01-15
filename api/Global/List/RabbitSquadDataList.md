---
uid: Global.RabbitSquadDataList
canonical_path: /api/Global/List/RabbitSquadDataList
---

# Class RabbitSquadDataList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitSquadDataList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitSquadDataList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitSquadDataList()

```csharp
public RabbitSquadDataList()
```

## Fields

### _dic

```csharp
private Dictionary<int, RabbitSquadData> _dic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,RabbitSquadData}

### _dicSefira

```csharp
private Dictionary<SefiraEnum, RabbitSquadData> _dicSefira
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,RabbitSquadData}

### _instance

```csharp
private static RabbitSquadDataList _instance
```

#### Field Value

**Type:** Global.RabbitSquadDataList

### _loaded

```csharp
private bool _loaded
```

#### Field Value

**Type:** System.Boolean

## Properties

### instance

```csharp
public static RabbitSquadDataList instance { get; }
```

#### Property Value

**Type:** Global.RabbitSquadDataList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public RabbitSquadData GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.RabbitSquadData

### GetData(SefiraEnum)

```csharp
public RabbitSquadData GetData(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.RabbitSquadData

### Init(Dictionary<int, RabbitSquadData>, Dictionary<SefiraEnum, RabbitSquadData>)

```csharp
public void Init(Dictionary<int, RabbitSquadData> dic, Dictionary<SefiraEnum, RabbitSquadData> dicSefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.Int32,RabbitSquadData}` |  |
| `dicSefira` | `System.Collections.Generic.Dictionary{SefiraEnum,RabbitSquadData}` |  |
