---
uid: Global.GlobalEtcDataModel
canonical_path: /api/Global/Model/GlobalEtcDataModel
---

# Class GlobalEtcDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GlobalEtcDataModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GlobalEtcDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GlobalEtcDataModel()

```csharp
private GlobalEtcDataModel()
```

## Fields

### _instance

```csharp
private static GlobalEtcDataModel _instance
```

#### Field Value

**Type:** Global.GlobalEtcDataModel

### _nextUnitInstanceId

```csharp
private long _nextUnitInstanceId
```

#### Field Value

**Type:** System.Int64

### cube

```csharp
public int cube
```

#### Field Value

**Type:** System.Int32

### day1clearCount

```csharp
public int day1clearCount
```

#### Field Value

**Type:** System.Int32

### ending1Done

```csharp
public bool ending1Done
```

#### Field Value

**Type:** System.Boolean

### ending2Done

```csharp
public bool ending2Done
```

#### Field Value

**Type:** System.Boolean

### ending3Done

```csharp
public bool ending3Done
```

#### Field Value

**Type:** System.Boolean

### hiddenEndingDone

```csharp
public bool hiddenEndingDone
```

#### Field Value

**Type:** System.Boolean

### trueEndingDone

```csharp
public bool trueEndingDone
```

#### Field Value

**Type:** System.Boolean

### tutorialDone

```csharp
public bool tutorialDone
```

#### Field Value

**Type:** System.Boolean

### unlockedMaxDay

```csharp
public int unlockedMaxDay
```

#### Field Value

**Type:** System.Int32

## Properties

### instance

```csharp
public static GlobalEtcDataModel instance { get; }
```

#### Property Value

**Type:** Global.GlobalEtcDataModel

## Methods

### AddCube(int)

```csharp
public void AddCube(int v)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Int32` |  |

### GetGlobalSaveData()

```csharp
public Dictionary<string, object> GetGlobalSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadGlobalData(Dictionary<string, object>)

```csharp
public void LoadGlobalData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### NextUnitInstanceId()

```csharp
public long NextUnitInstanceId()
```

#### Returns

**Type:** System.Int64

### ResetGlobalData()

```csharp
public void ResetGlobalData()
```

### SubCube(int)

```csharp
public void SubCube(int v)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Int32` |  |

### UpdateUnlockedMaxDay(int)

```csharp
public void UpdateUnlockedMaxDay(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |
