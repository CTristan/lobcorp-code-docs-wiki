---
uid: Global.SystemLoggerUI.CreatureSystemLog
canonical_path: /api/Global/Misc/SystemLoggerUICreatureSystemLog
---

# Class SystemLoggerUI.CreatureSystemLog

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SystemLoggerUI.CreatureSystemLog : SystemLoggerUI.SystemLoggerItem
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SystemLoggerUI.SystemLoggerItem](/api/Global/Misc/SystemLoggerUISystemLoggerItem) → SystemLoggerUI.CreatureSystemLog

## Inherited Members
[targetInstanceId](/api/Global/Misc/SystemLoggerUISystemLoggerItem#targetinstanceid), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### textList

```csharp
public List<Text> textList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Text}

## Methods

### AddLog(Text)

```csharp
public void AddLog(Text t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.UI.Text` |  |

### ChangeCodeIDtoName(string, string)

```csharp
private void ChangeCodeIDtoName(string origin, string dest)
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
