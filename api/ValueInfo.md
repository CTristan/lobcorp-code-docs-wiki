# Class ValueInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ValueInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ValueInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ValueInfo(int, int, int, int)

```csharp
public ValueInfo(int hp, int mental, int workspeed, int movement)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hp` | `System.Int32` |  |
| `mental` | `System.Int32` |  |
| `workspeed` | `System.Int32` |  |
| `movement` | `System.Int32` |  |

## Fields

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

### movementSpeed

```csharp
public int movementSpeed
```

#### Field Value

**Type:** System.Int32

### stats

```csharp
public int[] stats
```

#### Field Value

**Type:** System.Int32[]

### workSpeed

```csharp
public int workSpeed
```

#### Field Value

**Type:** System.Int32

## Methods

### getAverage()

```csharp
public static ValueInfo getAverage()
```

#### Returns

**Type:** Global.ValueInfo

### SetVal(int, int, int, int)

```csharp
public void SetVal(int hp, int mental, int workSpeed, int movement)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hp` | `System.Int32` |  |
| `mental` | `System.Int32` |  |
| `workSpeed` | `System.Int32` |  |
| `movement` | `System.Int32` |  |
