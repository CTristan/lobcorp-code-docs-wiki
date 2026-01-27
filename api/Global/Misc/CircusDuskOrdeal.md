---
uid: Global.CircusDuskOrdeal
canonical_path: /api/Global/Misc/CircusDuskOrdeal
---

# Class CircusDuskOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusDuskOrdeal : CircusOrdeal
```

Dusk of Crimson, The Struggle at the Climax. Spawns a couple [CircusDusks](/api/Global/Misc/CircusDusk).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → [CircusOrdeal](/api/Global/Misc/CircusOrdeal) → CircusDuskOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/Global/Misc/CircusOrdeal#curordealcreaturelist), [_color](/api/Global/Misc/CircusOrdeal#color), [ids](/api/Global/Misc/CircusOrdeal#ids), [risks](/api/Global/Misc/CircusOrdeal#risks), [names](/api/Global/Misc/CircusOrdeal#names), [_ordealName](/api/Global/Misc/CircusOrdeal#ordealname), [SetColor()](/api/Global/Misc/CircusOrdeal#setcolor), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#ordealnametext-ordealcreaturemodel), [MakeOrdealCreature(OrdealLevel, MapNode)](/api/Global/Misc/CircusOrdeal#makeordealcreature-ordeallevel-mapnode), [AddChildCircus(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#addchildcircus-ordealcreaturemodel), [FixedUpdate()](/api/Global/Misc/CircusOrdeal#fixedupdate), [CheckCloseCondition()](/api/Global/Misc/CircusOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/Global/Misc/CircusOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/Global/Misc/CircusOrdeal#ordealend), [level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CircusDuskOrdeal()

```csharp
public CircusDuskOrdeal()
```
#INC


## Fields

### _spawnCnt

```csharp
private const int _spawnCnt = 2
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### MakeDusk()

```csharp
private void MakeDusk()
```
#INC


### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
#INC
#code-generated

