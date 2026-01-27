---
uid: WhiteNightSpace.ApostleData
canonical_path: /api/WhiteNightSpace/ApostleData
---

# Class ApostleData

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ApostleData
```
structure for apostle data (including stuff gotten from the old agent)
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ApostleData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ApostleData(AgentModel)

```csharp
public ApostleData(AgentModel agent)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### ApostleData(Dictionary<string, object>)

```csharp
public ApostleData(Dictionary<string, object> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

## Fields

### hairColor

```csharp
public WorkerSpriteSaveData.ColorData hairColor
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerSpriteSaveData.ColorData

### hairData

```csharp
public WorkerSpriteSaveData.Pair hairData
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerSpriteSaveData.Pair

### instId

```csharp
public long instId
```
#INC


#### Field Value

**Type:** System.Int64

### Name

```csharp
public string Name
```
#INC


#### Field Value

**Type:** System.String

### NameId

```csharp
public int NameId
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}
