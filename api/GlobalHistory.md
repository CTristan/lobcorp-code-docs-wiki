# Class GlobalHistory

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalHistory : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalHistory

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GlobalHistory()

```csharp
public GlobalHistory()
```

## Properties

### instance

```csharp
public static GlobalHistory instance { get; }
```

#### Property Value

**Type:** Global.GlobalHistory

## Methods

### AddOrdsAndEmers(History)

```csharp
public void AddOrdsAndEmers(History history)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `history` | `Global.History` |  |

### GetCurrentTime()

```csharp
public float GetCurrentTime()
```

#### Returns

**Type:** System.Single

### GetHistory()

```csharp
public List<History> GetHistory()
```

#### Returns

**Type:** System.Collections.Generic.List{History}

### GetOrdsAndEmers()

```csharp
public List<History> GetOrdsAndEmers()
```

#### Returns

**Type:** System.Collections.Generic.List{History}

### GetResults()

```csharp
public List<Result> GetResults()
```

#### Returns

**Type:** System.Collections.Generic.List{Result}

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
