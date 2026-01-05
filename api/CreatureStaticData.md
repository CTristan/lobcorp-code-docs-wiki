# Class CreatureStaticData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureStaticData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureStaticData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureStaticData()

```csharp
public CreatureStaticData()
```

## Fields

### paramList

```csharp
public List<CreatureStaticData.ParameterData> paramList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureStaticData.ParameterData}

## Methods

### GetParam(int)

```csharp
public CreatureStaticData.ParameterData GetParam(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData

### GetParam(string)

```csharp
public CreatureStaticData.ParameterData GetParam(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureStaticData.ParameterData
