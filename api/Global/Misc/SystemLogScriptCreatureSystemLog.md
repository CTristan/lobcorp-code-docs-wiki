---
uid: Global.SystemLogScript.CreatureSystemLog
canonical_path: /api/Global/Misc/SystemLogScriptCreatureSystemLog
---

# Class SystemLogScript.CreatureSystemLog

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SystemLogScript.CreatureSystemLog
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SystemLogScript.CreatureSystemLog

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSystemLog(long)

```csharp
public CreatureSystemLog(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

## Fields

### targetId

```csharp
public long targetId
```

#### Field Value

**Type:** System.Int64

### textList

```csharp
public List<LogItemScript> textList
```

#### Field Value

**Type:** System.Collections.Generic.List{LogItemScript}

## Methods

### AddLog(LogItemScript)

```csharp
public void AddLog(LogItemScript t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Global.LogItemScript` |  |

### ChangeText(string, string)

```csharp
public void ChangeText(string origin, string dest)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `dest` | `System.String` |  |

### OnObserveLevelUpdated()

```csharp
public void OnObserveLevelUpdated()
```

### OnObserveLevelUpdated(CreatureModel)

```csharp
public void OnObserveLevelUpdated(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
