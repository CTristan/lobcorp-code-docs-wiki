# Class CreatureDefenseTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureDefenseTable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureDefenseTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureDefenseTable()

```csharp
public CreatureDefenseTable()
```

## Methods

### GetDefenseInfo()

```csharp
public DefenseInfo GetDefenseInfo()
```

#### Returns

**Type:** Global.DefenseInfo

### GetDefenseInfo(string)

```csharp
public DefenseInfo GetDefenseInfo(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.DefenseInfo

### GetDefenseInfoList()

```csharp
public List<DefenseInfo> GetDefenseInfoList()
```

#### Returns

**Type:** System.Collections.Generic.List{DefenseInfo}

### Init(Dictionary<string, DefenseInfo>)

```csharp
public void Init(Dictionary<string, DefenseInfo> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,DefenseInfo}` |  |
