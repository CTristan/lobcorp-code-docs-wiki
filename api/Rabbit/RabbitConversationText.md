---
uid: Rabbit.RabbitConversationText
canonical_path: /api/Rabbit/RabbitConversationText
---

# Class RabbitConversationText

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class RabbitConversationText
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitConversationText

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### keyCount

```csharp
public static int[] keyCount
```

#### Field Value

**Type:** System.Int32[]

### txt

```csharp
private const string txt = "Rabbit_Unit_{0}_"
```

#### Field Value

**Type:** System.String

## Methods

### GetKey(RabbitConversationType)

```csharp
public static string GetKey(RabbitConversationType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitConversationType` |  |

#### Returns

**Type:** System.String

### GetText(RabbitConversationType)

```csharp
public static string GetText(RabbitConversationType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitConversationType` |  |

#### Returns

**Type:** System.String
