# Class WorkRestrictionScript.RestrictionItem

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkRestrictionScript.RestrictionItem
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkRestrictionScript.RestrictionItem

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RestrictionItem()

```csharp
public RestrictionItem()
```

## Fields

### button

```csharp
public Toggle button
```

#### Field Value

**Type:** UnityEngine.UI.Toggle

### desc

```csharp
public Text desc
```

#### Field Value

**Type:** UnityEngine.UI.Text

### target

```csharp
[HideInInspector]
public RestrictionTable.TableElement.Restriction target
```

#### Field Value

**Type:** Global.RestrictionTable.TableElement.Restriction

## Methods

### Init(Restriction)

```csharp
public void Init(RestrictionTable.TableElement.Restriction item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `Global.RestrictionTable.TableElement.Restriction` |  |

### OnClick()

```csharp
public void OnClick()
```
