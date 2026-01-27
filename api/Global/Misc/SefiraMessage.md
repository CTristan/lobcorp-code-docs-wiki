---
uid: Global.SefiraMessage
canonical_path: /api/Global/Misc/SefiraMessage
---

# Class SefiraMessage

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraMessage
```
A single unit of Sephirah yap.

Holds a type and a text field.

See [Conversation](/api/Global/Misc/Conversation)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraMessage

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraMessage()

```csharp
public SefiraMessage()
```
#INC


### SefiraMessage(int, int, string)

```csharp
public SefiraMessage(int t, int d, string s)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `System.Int32` |  |
| `d` | `System.Int32` |  |
| `s` | `System.String` |  |

## Fields

### _desc

```csharp
private string _desc
```
#INC


#### Field Value

**Type:** System.String

### _descId

```csharp
private int _descId
```
#INC


#### Field Value

**Type:** System.Int32

### _type

```csharp
private int _type
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### desc

```csharp
public string desc { get; }
```

#### Property Value

**Type:** System.String

### type

```csharp
public int type { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### PrintFields()

```csharp
public void PrintFields()
```
#INC

