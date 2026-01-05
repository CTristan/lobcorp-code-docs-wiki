# Class WorkerPrimaryStat

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerPrimaryStat
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerPrimaryStat

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerPrimaryStat()

```csharp
public WorkerPrimaryStat()
```

## Fields

### battle

```csharp
public int battle
```

#### Field Value

**Type:** System.Int32

### hp

```csharp
public int hp
```

#### Field Value

**Type:** System.Int32

### mental

```csharp
public int mental
```

#### Field Value

**Type:** System.Int32

### work

```csharp
public int work
```

#### Field Value

**Type:** System.Int32

## Properties

### attackSpeed

```csharp
public int attackSpeed { get; }
```

#### Property Value

**Type:** System.Int32

### cubeSpeed

```csharp
public int cubeSpeed { get; }
```

#### Property Value

**Type:** System.Int32

### maxHP

```csharp
public int maxHP { get; }
```

#### Property Value

**Type:** System.Int32

### maxMental

```csharp
public int maxMental { get; }
```

#### Property Value

**Type:** System.Int32

### movementSpeed

```csharp
public int movementSpeed { get; }
```

#### Property Value

**Type:** System.Int32

### workProb

```csharp
public int workProb { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetAddedStat(WorkerPrimaryStatExp)

```csharp
public WorkerPrimaryStat GetAddedStat(WorkerPrimaryStatExp expAdd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `expAdd` | `Global.WorkerPrimaryStatExp` |  |

#### Returns

**Type:** Global.WorkerPrimaryStat

### MaxStatB()

```csharp
public static int MaxStatB()
```

#### Returns

**Type:** System.Int32

### MaxStatP()

```csharp
public static int MaxStatP()
```

#### Returns

**Type:** System.Int32

### MaxStatR()

```csharp
public static int MaxStatR()
```

#### Returns

**Type:** System.Int32

### MaxStatW()

```csharp
public static int MaxStatW()
```

#### Returns

**Type:** System.Int32

### UpdateStat(WorkerPrimaryStatExp)

```csharp
public void UpdateStat(WorkerPrimaryStatExp exp)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exp` | `Global.WorkerPrimaryStatExp` |  |
