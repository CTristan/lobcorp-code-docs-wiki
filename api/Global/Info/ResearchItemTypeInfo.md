---
uid: Global.ResearchItemTypeInfo
canonical_path: /api/Global/Info/ResearchItemTypeInfo
---

# Class ResearchItemTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemTypeInfo
```
Holds information about a type of [research](/api/Global/Model/ResearchItemModel).

See also [ResearchItemTypeList](/api/Global/List/ResearchItemTypeList)

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchItemTypeInfo()

```csharp
public ResearchItemTypeInfo()
```

## Fields

### atlas

```csharp
public string atlas
```
#INC


#### Field Value

**Type:** System.String

### cost

```csharp
public int[] cost
```
#INC


#### Field Value

**Type:** System.Int32[]

### desc

```csharp
public Dictionary<string, ResearchItemDesc> desc
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,ResearchItemDesc}

### icon

```csharp
public string icon
```
#INC


#### Field Value

**Type:** System.String

### iconDefSrc

```csharp
private const string iconDefSrc = "Sprites/UI/Icons/Research/"
```
#INC


#### Field Value

**Type:** System.String

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### maxLevel

```csharp
public int maxLevel
```
#INC


#### Field Value

**Type:** System.Int32

### prevResearch

```csharp
public List<int> prevResearch
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### sephira

```csharp
public string sephira
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public ResearchType type
```
#INC


#### Field Value

**Type:** Global.ResearchType

### upgradeInfos

```csharp
public ResearchUpgradeInfo[] upgradeInfos
```
#INC


#### Field Value

**Type:** Global.ResearchUpgradeInfo[]

## Methods

### CompareById(ResearchItemTypeInfo, ResearchItemTypeInfo)

```csharp
public static int CompareById(ResearchItemTypeInfo a, ResearchItemTypeInfo b)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.ResearchItemTypeInfo` |  |
| `b` | `Global.ResearchItemTypeInfo` |  |

#### Returns

**Type:** System.Int32

### GetDesc()

```csharp
public ResearchItemDesc GetDesc()
```
#INC


#### Returns

**Type:** Global.ResearchItemDesc

### GetIcon()

```csharp
public Sprite GetIcon()
```
#INC


#### Returns

**Type:** UnityEngine.Sprite
