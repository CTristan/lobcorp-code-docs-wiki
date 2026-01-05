# Class BugMidnightOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightOrdeal : BugOrdeal
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/OrdealBase) → [BugOrdeal](/api/BugOrdeal) → BugMidnightOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/BugOrdeal#curordealcreaturelist), [_color](/api/BugOrdeal#color), [_ordealName](/api/BugOrdeal#ordealname), [GetRiskLevel(OrdealCreatureModel)](/api/BugOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/BugOrdeal#ordealnametext-ordealcreaturemodel), [AddChildBug(OrdealCreatureModel)](/api/BugOrdeal#addchildbug-ordealcreaturemodel), [FixedUpdate()](/api/BugOrdeal#fixedupdate), [CheckCloseCondition()](/api/BugOrdeal#checkclosecondition), [OrdealEnd()](/api/BugOrdeal#ordealend), [level](/api/OrdealBase#level), [ordealRewards](/api/OrdealBase#ordealrewards), [startTime](/api/OrdealBase#starttime), [isStarted](/api/OrdealBase#isstarted), [OrdealColor](/api/OrdealBase#ordealcolor), [OnGameInit()](/api/OrdealBase#ongameinit), [OnDestroy()](/api/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/OrdealBase#cantakerewards), [OrdealTypeText](/api/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BugMidnightOrdeal()

```csharp
public BugMidnightOrdeal()
```

## Methods

### GetTargetNode()

```csharp
public MapNode GetTargetNode()
```

#### Returns

**Type:** Global.MapNode

### MakeOrdealCreature(OrdealLevel, MapNode, BugMidnight, params UnitDirection[])

```csharp
public override BugOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, BugMidnight midnight, params UnitDirection[] direction)
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
public override void OnDie(OrdealCreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```

### OnTeleport(MapNode, BugMidnight)

```csharp
public void OnTeleport(MapNode node, BugMidnight midnight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `midnight` | `Global.BugMidnight` |  |
