# Class PanicData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PanicData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PanicData()

```csharp
public PanicData()
```

## Fields

### PanicBuildCode

```csharp
public string PanicBuildCode
```

#### Field Value

**Type:** System.String

### PanicDesc

```csharp
public string PanicDesc
```

#### Field Value

**Type:** System.String

### PanicId

```csharp
public int PanicId
```

#### Field Value

**Type:** System.Int32

### PanicLifeStyle

```csharp
public string PanicLifeStyle
```

#### Field Value

**Type:** System.String

### PanicName

```csharp
public string PanicName
```

#### Field Value

**Type:** System.String

## Methods

### BuildDefaultPanicAction(WorkerModel)

```csharp
public PanicAction BuildDefaultPanicAction(WorkerModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

#### Returns

**Type:** Global.PanicAction

### BuildPanicAction(WorkerModel)

```csharp
public PanicAction BuildPanicAction(WorkerModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

#### Returns

**Type:** Global.PanicAction
