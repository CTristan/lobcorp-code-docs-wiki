# Class CircusDawnOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusDawnOrdeal : CircusOrdeal
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/OrdealBase) → [CircusOrdeal](/api/CircusOrdeal) → CircusDawnOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/CircusOrdeal#curordealcreaturelist), [_color](/api/CircusOrdeal#color), [_ordealName](/api/CircusOrdeal#ordealname), [GetRiskLevel(OrdealCreatureModel)](/api/CircusOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/CircusOrdeal#ordealnametext-ordealcreaturemodel), [MakeOrdealCreature(OrdealLevel, MapNode)](/api/CircusOrdeal#makeordealcreature-ordeallevel-mapnode), [AddChildCircus(OrdealCreatureModel)](/api/CircusOrdeal#addchildcircus-ordealcreaturemodel), [FixedUpdate()](/api/CircusOrdeal#fixedupdate), [CheckCloseCondition()](/api/CircusOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/CircusOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/CircusOrdeal#ordealend), [level](/api/OrdealBase#level), [ordealRewards](/api/OrdealBase#ordealrewards), [startTime](/api/OrdealBase#starttime), [isStarted](/api/OrdealBase#isstarted), [OrdealColor](/api/OrdealBase#ordealcolor), [OnGameInit()](/api/OrdealBase#ongameinit), [OnDestroy()](/api/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/OrdealBase#ordealtypo-string-color-bool-int), [SetRiskLevel(RiskLevel)](/api/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/OrdealBase#cantakerewards), [OrdealTypeText](/api/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CircusDawnOrdeal()

```csharp
public CircusDawnOrdeal()
```

## Methods

### GetTarget(out bool)

```csharp
public CreatureModel GetTarget(out bool hasError)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hasError` | `System.Boolean` |  |

#### Returns

**Type:** Global.CreatureModel

### GetTeleportNode()

```csharp
public MapNode GetTeleportNode()
```

#### Returns

**Type:** Global.MapNode

### IsStartable()

```csharp
public override bool IsStartable()
```

#### Returns

**Type:** System.Boolean

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```

### ReadyForTeleport()

```csharp
public bool ReadyForTeleport()
```

#### Returns

**Type:** System.Boolean
