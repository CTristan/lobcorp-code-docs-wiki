---
uid: Global.AgentAnim.ParameterInfo
canonical_path: /api/Global/Info/AgentAnimParameterInfo
---

# Class AgentAnim.ParameterInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class AgentAnim.ParameterInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentAnim.ParameterInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ParameterInfo(string, bool, int)

```csharp
public ParameterInfo(string name, bool value, int state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `value` | `System.Boolean` |  |
| `state` | `System.Int32` |  |

### ParameterInfo(string, bool, int, float)

```csharp
public ParameterInfo(string name, bool value, int state, float remainTimer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `value` | `System.Boolean` |  |
| `state` | `System.Int32` |  |
| `remainTimer` | `System.Single` |  |

### ParameterInfo(string, int, int)

```csharp
public ParameterInfo(string name, int value, int state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `value` | `System.Int32` |  |
| `state` | `System.Int32` |  |

### ParameterInfo(string, int, int, float)

```csharp
public ParameterInfo(string name, int value, int state, float remainTimer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `value` | `System.Int32` |  |
| `state` | `System.Int32` |  |
| `remainTimer` | `System.Single` |  |

## Fields

### bvalue

```csharp
public bool bvalue
```

#### Field Value

**Type:** System.Boolean

### ivalue

```csharp
public int ivalue
```

#### Field Value

**Type:** System.Int32

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### remainTimer

```csharp
public float remainTimer
```

#### Field Value

**Type:** System.Single

### state

```csharp
public int state
```

#### Field Value

**Type:** System.Int32

### type

```csharp
public AgentAnim.ParameterInfo.ParameterType type
```

#### Field Value

**Type:** Global.AgentAnim.ParameterInfo.ParameterType
