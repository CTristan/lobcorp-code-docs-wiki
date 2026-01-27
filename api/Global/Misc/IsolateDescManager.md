---
uid: Global.IsolateDescManager
canonical_path: /api/Global/Misc/IsolateDescManager
---

# Class IsolateDescManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IsolateDescManager
```

Helper for displaying [IsolateDescription](/api/Assets/Scripts/UI/Isolate/IsolateDescription) instances.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IsolateDescManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### IsolateDescManager()

```csharp
public IsolateDescManager()
```

## Fields

### Max_B_Desc

```csharp
public const int Max_B_Desc = 25
```

#### Field Value

**Type:** System.Int32

### Max_NormalDesc

```csharp
public const int Max_NormalDesc = 10
```

#### Field Value

**Type:** System.Int32

### Max_P_Desc

```csharp
public const int Max_P_Desc = 26
```

#### Field Value

**Type:** System.Int32

### Max_R_Desc

```csharp
public const int Max_R_Desc = 26
```

#### Field Value

**Type:** System.Int32

### Max_W_Desc

```csharp
public const int Max_W_Desc = 27
```

#### Field Value

**Type:** System.Int32

### Max_WorkEnd

```csharp
public const int Max_WorkEnd = 1
```

#### Field Value

**Type:** System.Int32

### Max_WorkStart

```csharp
public const int Max_WorkStart = 1
```

#### Field Value

**Type:** System.Int32

## Methods

### GetList(RwbpType)

```csharp
public static List<int> GetList(RwbpType type)
```
Produces a list of integers from 0 to the maximum number of available different [IsolateDescription](/api/Assets/Scripts/UI/Isolate/IsolateDescription) texts for the given work type.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Collections.Generic.List{System.Int32}
