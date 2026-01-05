# Class ResearchItemModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ResearchItemModel()

```csharp
public ResearchItemModel()
```

## Fields

### curLevel

```csharp
public int curLevel
```

#### Field Value

**Type:** System.Int32

### info

```csharp
public ResearchItemTypeInfo info
```

#### Field Value

**Type:** Global.ResearchItemTypeInfo

## Methods

### CompareById(ResearchItemModel, ResearchItemModel)

```csharp
public static int CompareById(ResearchItemModel a, ResearchItemModel b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.ResearchItemModel` |  |
| `b` | `Global.ResearchItemModel` |  |

#### Returns

**Type:** System.Int32

### GetCurrentUpgradeInfo()

```csharp
public ResearchUpgradeInfo GetCurrentUpgradeInfo()
```

#### Returns

**Type:** Global.ResearchUpgradeInfo

### GetNextUpgradeInfo()

```csharp
public ResearchUpgradeInfo GetNextUpgradeInfo()
```

#### Returns

**Type:** Global.ResearchUpgradeInfo

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
