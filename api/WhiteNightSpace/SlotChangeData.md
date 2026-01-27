---
uid: WhiteNightSpace.SlotChangeData
canonical_path: /api/WhiteNightSpace/SlotChangeData
---

# Class SlotChangeData

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlotChangeData
```
Data for changing [Plague Doctor's parts](/api/WhiteNightSpace/ActivateParts) and their [region](/api/WhiteNightSpace/PlagueDocAnimRegion) for coloring

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SlotChangeData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlotChangeData()

```csharp
public SlotChangeData()
```

## Fields

### alterColor

```csharp
public Color alterColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### initialColor

```csharp
[Header("Not Apply")]
public Color initialColor
```

#### Field Value

**Type:** UnityEngine.Color

### RegionName

```csharp
public string RegionName
```
#INC
#code-generated


#### Field Value

**Type:** System.String

### regionType

```csharp
public PlagueDocAnimRegion regionType
```
#INC


#### Field Value

**Type:** WhiteNightSpace.PlagueDocAnimRegion

### slotList

```csharp
[SpineSlot("", "", false, true)]
public List<string> slotList
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}
