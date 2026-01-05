# Class EquipmentTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static EquipmentTypeList instance { get; }
```

#### Property Value

**Type:** Global.EquipmentTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetAllData()

```csharp
public List<EquipmentTypeInfo> GetAllData()
```

#### Returns

**Type:** System.Collections.Generic.List{EquipmentTypeInfo}

### GetData(int)

```csharp
public EquipmentTypeInfo GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo

### Init(Dictionary<int, EquipmentTypeInfo>)

```csharp
public void Init(Dictionary<int, EquipmentTypeInfo> info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `System.Collections.Generic.Dictionary{System.Int32,EquipmentTypeInfo}` |  |
