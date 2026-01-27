---
uid: Global.EGOGiftRegionKey
canonical_path: /api/Global/Key/EGOGiftRegionKey
---

# Class EGOGiftRegionKey

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class EGOGiftRegionKey
```
Converts between the [EGOgiftAttachRegion](/api/Global/Misc/EGOgiftAttachRegion) enum and string.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EGOGiftRegionKey

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### back

```csharp
public static string back
```
#INC


#### Field Value

**Type:** System.String

### body_up

```csharp
public static string body_up
```
#INC


#### Field Value

**Type:** System.String

### eye

```csharp
public static string eye
```
#INC


#### Field Value

**Type:** System.String

### face

```csharp
public static string face
```
#INC


#### Field Value

**Type:** System.String

### hair

```csharp
public static string hair
```
#INC


#### Field Value

**Type:** System.String

### head

```csharp
public static string head
```
#INC


#### Field Value

**Type:** System.String

### lefthand

```csharp
public static string lefthand
```
#INC


#### Field Value

**Type:** System.String

### mouth

```csharp
public static string mouth
```
#INC


#### Field Value

**Type:** System.String

### region

```csharp
public static string[] region
```
#INC


#### Field Value

**Type:** System.String[]

### righthand

```csharp
public static string righthand
```
#INC


#### Field Value

**Type:** System.String

## Methods

### GetRegion(string)

```csharp
public static EGOgiftAttachRegion GetRegion(string name)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.EGOgiftAttachRegion

### GetRegionKey(EGOgiftAttachRegion, out string, out string)

```csharp
public static bool GetRegionKey(EGOgiftAttachRegion region, out string slot, out string attach)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Global.EGOgiftAttachRegion` |  |
| `slot` | `System.String` |  |
| `attach` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### ParseRegion(string, out EGOgiftAttachRegion)

```csharp
public static bool ParseRegion(string name, out EGOgiftAttachRegion region)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `region` | `Global.EGOgiftAttachRegion` |  |

#### Returns

**Type:** System.Boolean
