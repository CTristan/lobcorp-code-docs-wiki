---
uid: Global.BugMidnightOrdeal
canonical_path: /api/Global/Misc/BugMidnightOrdeal
---

# Class BugMidnightOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightOrdeal : BugOrdeal
```

Midnight of Amber ordeal; The Eternal Meal. Spawns a few [BugMidnights](/api/Global/Misc/BugMidnight).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → [BugOrdeal](/api/Global/Misc/BugOrdeal) → BugMidnightOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/Global/Misc/BugOrdeal#curordealcreaturelist), [_color](/api/Global/Misc/BugOrdeal#color), [ids](/api/Global/Misc/BugOrdeal#ids), [risks](/api/Global/Misc/BugOrdeal#risks), [names](/api/Global/Misc/BugOrdeal#names), [_ordealName](/api/Global/Misc/BugOrdeal#ordealname), [SetColor()](/api/Global/Misc/BugOrdeal#setcolor), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/BugOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/BugOrdeal#ordealnametext-ordealcreaturemodel), [AddChildBug(OrdealCreatureModel)](/api/Global/Misc/BugOrdeal#addchildbug-ordealcreaturemodel), [FixedUpdate()](/api/Global/Misc/BugOrdeal#fixedupdate), [CheckCloseCondition()](/api/Global/Misc/BugOrdeal#checkclosecondition), [OrdealEnd()](/api/Global/Misc/BugOrdeal#ordealend), [level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugMidnightOrdeal()

```csharp
public BugMidnightOrdeal()
```
#INC


## Fields

### _spawnNum

```csharp
private const int _spawnNum = 2
```
#INC


#### Field Value

**Type:** System.Int32

### managers

```csharp
private List<BugMidnightOrdeal.BugMidnightManager> managers
```

#### Field Value

**Type:** System.Collections.Generic.List{BugMidnightOrdeal.BugMidnightManager}

## Methods

### GetTargetNode()

```csharp
public MapNode GetTargetNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### MakeBug()

```csharp
private void MakeBug()
```
#INC


### MakeOrdealCreature(OrdealLevel, MapNode, BugMidnight, params UnitDirection[])

```csharp
public override BugOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, BugMidnight midnight, params UnitDirection[] direction)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
#INC
#code-generated


### OnTeleport(MapNode, BugMidnight)

```csharp
public void OnTeleport(MapNode node, BugMidnight midnight)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `midnight` | `Global.BugMidnight` |  |
