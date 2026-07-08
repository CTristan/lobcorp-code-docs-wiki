---
uid: Global.AgentNameTypeInfo
canonical_path: /api/Global/Info/AgentNameTypeInfo
---
# Class AgentNameTypeInfo
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentNameTypeInfo
```
> This section may have incomplete or incorrect information.
{.is-warning}

Stores an ID, whether an [agent name](/api/Global/Misc/AgentName) is custom, and provides a way to obtain the name...?

Oddly, it seems the difference between backer names and other names is based on the value of the ID -- SetAsCreditName *just* adds 10000 to the id...




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentNameTypeInfo

## Constructors
### AgentNameTypeInfo()
```csharp
public AgentNameTypeInfo()
```

## Fields
### isCustom
```csharp
public bool isCustom
```


#### Field Value
**Type:** System.Boolean

### nameDic
```csharp
public Dictionary<string, string> nameDic
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### nameId
```csharp
public int nameId
```


#### Field Value
**Type:** System.Int32

## Properties
### CurrentLangage
```csharp
public static string CurrentLangage { get; }
```

#### Property Value
**Type:** System.String

## Methods
### GetName()
```csharp
public string GetName()
```


#### Returns
**Type:** System.String

### IsCreditName()
```csharp
public bool IsCreditName()
```


#### Returns
**Type:** System.Boolean

### IsCustomName()
```csharp
public bool IsCustomName()
```


#### Returns
**Type:** System.Boolean

### SetAsCreditName()
```csharp
public void SetAsCreditName()
```


### SetAsCustomName()
```csharp
public void SetAsCustomName()
```


## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)




