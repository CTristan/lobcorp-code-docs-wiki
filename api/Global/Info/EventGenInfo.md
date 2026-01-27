---
uid: Global.EventGenInfo
canonical_path: /api/Global/Info/EventGenInfo
---

# Class EventGenInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EventGenInfo
```
Information about which events can be generated.

[Apocalypse Bird](/api/Global/Misc/BossBird) is banned from showing up until after day 20.

See [SpecialEventManager](/api/Global/Misc/SpecialEventManager)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EventGenInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EventGenInfo()

```csharp
public EventGenInfo()
```

## Fields

### _bossBirdAdditionDay

```csharp
private const int _bossBirdAdditionDay = 20
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### GenerateEvents(int)

```csharp
public static List<EventBase> GenerateEvents(int day)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{EventBase}
