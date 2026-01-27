---
uid: Global.MoneyModel
canonical_path: /api/Global/Model/MoneyModel
---

# Class MoneyModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoneyModel
```
Keeps track of LOB points.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MoneyModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoneyModel()

```csharp
private MoneyModel()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static MoneyModel _instance
```
#INC


#### Field Value

**Type:** Global.MoneyModel

### money

```csharp
public int money
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### instance

```csharp
public static MoneyModel instance { get; }
```

#### Property Value

**Type:** Global.MoneyModel

## Methods

### Add(int)

```csharp
public void Add(int added)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `added` | `System.Int32` |  |

### EnoughCheck(int)

```csharp
public bool EnoughCheck(int cost)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cost` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Init()

```csharp
public void Init()
```
#INC


### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### Pay(int)

```csharp
public bool Pay(int cost)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cost` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean
