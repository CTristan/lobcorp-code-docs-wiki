# Class FixerOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerOrdeal : OrdealBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/OrdealBase) → FixerOrdeal

## Inherited Members
[level](/api/OrdealBase#level), [ordealRewards](/api/OrdealBase#ordealrewards), [startTime](/api/OrdealBase#starttime), [isStarted](/api/OrdealBase#isstarted), [OrdealColor](/api/OrdealBase#ordealcolor), [OnGameInit()](/api/OrdealBase#ongameinit), [OnDestroy()](/api/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/OrdealBase#cantakerewards), [OrdealTypeText](/api/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FixerOrdeal(OrdealLevel)

```csharp
public FixerOrdeal(OrdealLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

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

### MakeOrdealCreature(RwbpType, MapNode)

```csharp
public FixerCreature MakeOrdealCreature(RwbpType type, MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.FixerCreature

### MakeOrdealCreature_Midnight(MapNode)

```csharp
public FixerCreature MakeOrdealCreature_Midnight(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.FixerCreature

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

### SetColor()

```csharp
protected void SetColor()
```
