---
uid: Global.CircusDawnOrdeal
canonical_path: /api/Global/Misc/CircusDawnOrdeal
---

# Class CircusDawnOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusDawnOrdeal : CircusOrdeal
```

Dawn of Crimson ordeal, The Cheers for the Beginning. Spawns several [CircusDawns](/api/Global/Misc/CircusDawn).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → [CircusOrdeal](/api/Global/Misc/CircusOrdeal) → CircusDawnOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/Global/Misc/CircusOrdeal#curordealcreaturelist), [_color](/api/Global/Misc/CircusOrdeal#color), [ids](/api/Global/Misc/CircusOrdeal#ids), [risks](/api/Global/Misc/CircusOrdeal#risks), [names](/api/Global/Misc/CircusOrdeal#names), [_ordealName](/api/Global/Misc/CircusOrdeal#ordealname), [SetColor()](/api/Global/Misc/CircusOrdeal#setcolor), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#ordealnametext-ordealcreaturemodel), [MakeOrdealCreature(OrdealLevel, MapNode)](/api/Global/Misc/CircusOrdeal#makeordealcreature-ordeallevel-mapnode), [AddChildCircus(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#addchildcircus-ordealcreaturemodel), [FixedUpdate()](/api/Global/Misc/CircusOrdeal#fixedupdate), [CheckCloseCondition()](/api/Global/Misc/CircusOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/Global/Misc/CircusOrdeal#ordealend), [level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CircusDawnOrdeal()

```csharp
public CircusDawnOrdeal()
```
#INC


## Fields

### _currentWaitingCreature

```csharp
private CreatureModel _currentWaitingCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

## Methods

### GetTarget(out bool)

```csharp
public CreatureModel GetTarget(out bool hasError)
```
#INC


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
#INC


#### Returns

**Type:** Global.MapNode

### IsStartable()

```csharp
public override bool IsStartable()
```
#INC


#### Returns

**Type:** System.Boolean

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
#INC
#code-generated


### ReadyForTeleport()

```csharp
public bool ReadyForTeleport()
```
#INC


#### Returns

**Type:** System.Boolean
