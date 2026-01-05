# Class ShieldTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ShieldTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ShieldTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static ShieldTypeList instance { get; }
```

#### Property Value

**Type:** Global.ShieldTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public ShieldTypeInfo GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ShieldTypeInfo

### GetList()

```csharp
public ReadOnlyCollection<ShieldTypeInfo> GetList()
```

#### Returns

**Type:** System.Collections.ObjectModel.ReadOnlyCollection{ShieldTypeInfo}

### Init(ReadOnlyCollection<ShieldTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<ShieldTypeInfo> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.ObjectModel.ReadOnlyCollection{ShieldTypeInfo}` |  |
