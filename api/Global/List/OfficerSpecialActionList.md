---
uid: Global.OfficerSpecialActionList
canonical_path: /api/Global/List/OfficerSpecialActionList
---

# Class OfficerSpecialActionList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerSpecialActionList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OfficerSpecialActionList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OfficerSpecialActionList()

```csharp
public OfficerSpecialActionList()
```

## Fields

### _list

```csharp
private List<OfficerSpecialAction> _list
```

#### Field Value

**Type:** System.Collections.Generic.List{OfficerSpecialAction}

### currentAvaialbe

```csharp
public List<OfficerSpecialAction> currentAvaialbe
```

#### Field Value

**Type:** System.Collections.Generic.List{OfficerSpecialAction}

### sefira

```csharp
public int sefira
```

#### Field Value

**Type:** System.Int32

## Properties

### list

```csharp
public List<OfficerSpecialAction> list { get; }
```

#### Property Value

**Type:** System.Collections.Generic.List{OfficerSpecialAction}

## Methods

### AddList(OfficerSpecialAction)

```csharp
public void AddList(OfficerSpecialAction osa)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `osa` | `Global.OfficerSpecialAction` |  |

### GetRandomAction()

```csharp
public OfficerSpecialAction GetRandomAction()
```

#### Returns

**Type:** Global.OfficerSpecialAction

### ResetAction(OfficerSpecialAction)

```csharp
public void ResetAction(OfficerSpecialAction osa)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `osa` | `Global.OfficerSpecialAction` |  |

### ResetActionAll()

```csharp
public void ResetActionAll()
```
