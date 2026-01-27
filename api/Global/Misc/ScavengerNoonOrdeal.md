---
uid: Global.ScavengerNoonOrdeal
canonical_path: /api/Global/Misc/ScavengerNoonOrdeal
---

# Class ScavengerNoonOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
internal class ScavengerNoonOrdeal : ScavengerOrdeal
```

Noon of Indigo, The Sweepers. Spawns four groups of three [Sweepers](/api/Global/Misc/ScavengerNoon).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → [ScavengerOrdeal](/api/Global/Misc/ScavengerOrdeal) → ScavengerNoonOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/Global/Misc/ScavengerOrdeal#curordealcreaturelist), [_color](/api/Global/Misc/ScavengerOrdeal#color), [ids](/api/Global/Misc/ScavengerOrdeal#ids), [_ordealName](/api/Global/Misc/ScavengerOrdeal#ordealname), [SetColor()](/api/Global/Misc/ScavengerOrdeal#setcolor), [MakeOrdealCreature(OrdealLevel, MapNode, params UnitDirection[])](/api/Global/Misc/ScavengerOrdeal#makeordealcreature-ordeallevel-mapnode-params-unitdirection), [FixedUpdate()](/api/Global/Misc/ScavengerOrdeal#fixedupdate), [CheckCloseCondition()](/api/Global/Misc/ScavengerOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/Global/Misc/ScavengerOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/Global/Misc/ScavengerOrdeal#ordealend), [level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#ordealnametext-ordealcreaturemodel), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#getrisklevel-ordealcreaturemodel), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ScavengerNoonOrdeal()

```csharp
public ScavengerNoonOrdeal()
```
#INC


## Fields

### _centerDist

```csharp
private const float _centerDist = 0
```
#INC


#### Field Value

**Type:** System.Single

### _leftDist

```csharp
private const float _leftDist = -3
```
#INC


#### Field Value

**Type:** System.Single

### _maxNumOfSefira

```csharp
private const int _maxNumOfSefira = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _rightDist

```csharp
private const float _rightDist = 3
```
#INC


#### Field Value

**Type:** System.Single

### _spawnPerSefira

```csharp
private const int _spawnPerSefira = 3
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### GetNode(PassageObjectModel)

```csharp
private MapNode GetNode(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.MapNode

### GetPassages(Sefira)

```csharp
private List<PassageObjectModel> GetPassages(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns

**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetSefira(ref List<Sefira>)

```csharp
private Sefira GetSefira(ref List<Sefira> remain)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `remain` | `System.Collections.Generic.List{Sefira}` |  |

#### Returns

**Type:** Global.Sefira

### MakeNoon()

```csharp
private void MakeNoon()
```
#INC


### MakeScavengers(MapNode)

```csharp
private void MakeScavengers(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
#INC
#code-generated

