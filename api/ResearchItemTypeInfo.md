# Class ResearchItemTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.String

### cost

```csharp
public int[] cost
```

#### Field Value

**Type:** System.Int32[]

### desc

```csharp
public Dictionary<string, ResearchItemDesc> desc
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,ResearchItemDesc}

### icon

```csharp
public string icon
```

#### Field Value

**Type:** System.String

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### maxLevel

```csharp
public int maxLevel
```

#### Field Value

**Type:** System.Int32

### prevResearch

```csharp
public List<int> prevResearch
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### sephira

```csharp
public string sephira
```

#### Field Value

**Type:** System.String

### type

```csharp
public ResearchType type
```

#### Field Value

**Type:** Global.ResearchType

### upgradeInfos

```csharp
public ResearchUpgradeInfo[] upgradeInfos
```

#### Field Value

**Type:** Global.ResearchUpgradeInfo[]

## Methods

### CompareById(ResearchItemTypeInfo, ResearchItemTypeInfo)

```csharp
public static int CompareById(ResearchItemTypeInfo a, ResearchItemTypeInfo b)
```

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

#### Returns

**Type:** Global.ResearchItemDesc

### GetIcon()

```csharp
public Sprite GetIcon()
```

#### Returns

**Type:** UnityEngine.Sprite
