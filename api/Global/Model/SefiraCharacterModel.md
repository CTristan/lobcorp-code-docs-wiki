---
uid: Global.SefiraCharacterModel
canonical_path: /api/Global/Model/SefiraCharacterModel
---

# Class SefiraCharacterModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraCharacterModel
```
Represents a Sephirah and whether their department is open. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraCharacterModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraCharacterModel(SefiraEnum)

```csharp
public SefiraCharacterModel(SefiraEnum sefira)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

## Fields

### bInit

```csharp
public bool bInit
```
#INC


#### Field Value

**Type:** System.Boolean

### level

```csharp
public int level
```
#INC


#### Field Value

**Type:** System.Int32

### sefira

```csharp
public SefiraEnum sefira
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

## Methods

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnOpenSefira()

```csharp
public void OnOpenSefira()
```
#INC

