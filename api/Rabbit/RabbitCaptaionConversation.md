---
uid: Rabbit.RabbitCaptaionConversation
canonical_path: /api/Rabbit/RabbitCaptaionConversation
---

# Class RabbitCaptaionConversation

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class RabbitCaptaionConversation
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitCaptaionConversation

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### format

```csharp
private const string format = "Rabbit_Captain_{0}_"
```

#### Field Value

**Type:** System.String

### keyCount

```csharp
public static int[] keyCount
```

#### Field Value

**Type:** System.Int32[]

## Properties

### Binah

```csharp
public static bool Binah { get; }
```

#### Property Value

**Type:** System.Boolean

### Geburah

```csharp
public static bool Geburah { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetKey(RabbitCaptainConversationType)

```csharp
public static string GetKey(RabbitCaptainConversationType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitCaptainConversationType` |  |

#### Returns

**Type:** System.String

### GetText(RabbitCaptainConversationType)

```csharp
public static string GetText(RabbitCaptainConversationType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitCaptainConversationType` |  |

#### Returns

**Type:** System.String
