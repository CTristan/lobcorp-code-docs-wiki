# Class SystemLoggerUI.CreatureSystemLog

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SystemLoggerUI.CreatureSystemLog : SystemLoggerUI.SystemLoggerItem
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SystemLoggerUI.SystemLoggerItem](/api/SystemLoggerUI-SystemLoggerItem) → SystemLoggerUI.CreatureSystemLog

## Inherited Members
[targetInstanceId](/api/SystemLoggerUI-SystemLoggerItem#targetinstanceid), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### OnObserveLevelUpdated()

```csharp
public void OnObserveLevelUpdated()
```
