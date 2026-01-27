---
uid: Global.WorkerPrimaryStat
canonical_path: /api/Global/Misc/WorkerPrimaryStat
---

# Class WorkerPrimaryStat

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerPrimaryStat
```
Holds the stats for a [worker](/api/Global/Model/WorkerModel).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerPrimaryStat

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


#### Field Value

**Type:** System.Int32

### hp

```csharp
public int hp
```
#INC


#### Field Value

**Type:** System.Int32

### mental

```csharp
public int mental
```
#INC


#### Field Value

**Type:** System.Int32

### work

```csharp
public int work
```
#INC


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
#INC
#code-generated


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
#INC


#### Returns

**Type:** System.Int32

### MaxStatP()

```csharp
public static int MaxStatP()
```
#INC


#### Returns

**Type:** System.Int32

### MaxStatR()

```csharp
public static int MaxStatR()
```
#INC


#### Returns

**Type:** System.Int32

### MaxStatW()

```csharp
public static int MaxStatW()
```
#INC


#### Returns

**Type:** System.Int32

### UpdateStat(WorkerPrimaryStatExp)

```csharp
public void UpdateStat(WorkerPrimaryStatExp exp)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exp` | `Global.WorkerPrimaryStatExp` |  |
