# Class BugOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugOrdeal : OrdealBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/OrdealBase) → BugOrdeal

## Inherited Members
[level](/api/OrdealBase#level), [ordealRewards](/api/OrdealBase#ordealrewards), [startTime](/api/OrdealBase#starttime), [isStarted](/api/OrdealBase#isstarted), [OrdealColor](/api/OrdealBase#ordealcolor), [OnGameInit()](/api/OrdealBase#ongameinit), [OnDestroy()](/api/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/OrdealBase#cantakerewards), [OrdealTypeText](/api/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BugOrdeal()

```csharp
public BugOrdeal()
```

## Fields

### _color

```csharp
protected Color _color
```

#### Field Value

**Type:** UnityEngine.Color

### _curOrdealCreatureList

```csharp
protected List<OrdealCreatureModel> _curOrdealCreatureList
```

#### Field Value

**Type:** System.Collections.Generic.List{OrdealCreatureModel}

### _ordealName

```csharp
protected string _ordealName
```

#### Field Value

**Type:** System.String

## Methods

### AddChildBug(OrdealCreatureModel)

```csharp
public void AddChildBug(OrdealCreatureModel child)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.OrdealCreatureModel` |  |

### CheckCloseCondition()

```csharp
protected virtual bool CheckCloseCondition()
```

#### Returns

**Type:** System.Boolean

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### GetRiskLevel(OrdealCreatureModel)

```csharp
public override RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** Global.RiskLevel

### MakeOrdealCreature(OrdealLevel, MapNode, BugMidnight, params UnitDirection[])

```csharp
public virtual BugOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, BugMidnight midnight, params UnitDirection[] direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |
| `midnight` | `Global.BugMidnight` |  |
| `direction` | `Global.UnitDirection[]` |  |

#### Returns

**Type:** Global.BugOrdealCreature

### OnDie(OrdealCreatureModel)

```csharp
public virtual void OnDie(OrdealCreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```

### OrdealEnd()

```csharp
public override void OrdealEnd()
```

### OrdealNameText(OrdealCreatureModel)

```csharp
public override string OrdealNameText(OrdealCreatureModel ordeal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** System.String
