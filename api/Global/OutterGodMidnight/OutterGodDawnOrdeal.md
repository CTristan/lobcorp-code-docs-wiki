---
uid: Global.OutterGodDawnOrdeal
canonical_path: /api/Global/OutterGodMidnight/OutterGodDawnOrdeal
---

# Class OutterGodDawnOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OutterGodDawnOrdeal : OutterGodOrdeal
```

Dawn of Violet ordeal, The Fruit of Understanding. Spawns several [OutterGodDawn](/api/Global/OutterGodMidnight/OutterGodDawn)s.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → [OutterGodOrdeal](/api/Global/Misc/OutterGodOrdeal) → OutterGodDawnOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/Global/Misc/OutterGodOrdeal#curordealcreaturelist), [_color](/api/Global/Misc/OutterGodOrdeal#color), [ids](/api/Global/Misc/OutterGodOrdeal#ids), [_ordealName](/api/Global/Misc/OutterGodOrdeal#ordealname), [SetColor()](/api/Global/Misc/OutterGodOrdeal#setcolor), [MakeOrdealCreature(OrdealLevel, MapNode)](/api/Global/Misc/OutterGodOrdeal#makeordealcreature-ordeallevel-mapnode), [FixedUpdate()](/api/Global/Misc/OutterGodOrdeal#fixedupdate), [CheckCloseCondition()](/api/Global/Misc/OutterGodOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/Global/Misc/OutterGodOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/Global/Misc/OutterGodOrdeal#ordealend), [level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#ordealnametext-ordealcreaturemodel), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#getrisklevel-ordealcreaturemodel), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OutterGodDawnOrdeal()

```csharp
public OutterGodDawnOrdeal()
```
#INC


## Fields

### _dawnCount

```csharp
private const int _dawnCount = 1
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### MakeOutterGods()

```csharp
private void MakeOutterGods()
```
#INC


### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
#INC
#code-generated

