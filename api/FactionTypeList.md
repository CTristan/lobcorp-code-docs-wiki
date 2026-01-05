# Class FactionTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FactionTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FactionTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FactionTypeList()

```csharp
public FactionTypeList()
```

## Properties

### instance

```csharp
public static FactionTypeList instance { get; }
```

#### Property Value

**Type:** Global.FactionTypeList

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetFaction(string)

```csharp
public FactionTypeInfo GetFaction(string code)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `code` | `System.String` |  |

#### Returns

**Type:** Global.FactionTypeInfo

### GetFactionByName(string)

```csharp
public FactionTypeInfo GetFactionByName(string factionName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionName` | `System.String` |  |

#### Returns

**Type:** Global.FactionTypeInfo

### Init(ReadOnlyCollection<FactionTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<FactionTypeInfo> factions)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factions` | `System.Collections.ObjectModel.ReadOnlyCollection{FactionTypeInfo}` |  |
