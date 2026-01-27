---
uid: Global.ScavengerOrdeal
canonical_path: /api/Global/Misc/ScavengerOrdeal
---

# Class ScavengerOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ScavengerOrdeal : OrdealBase
```

Parent class for Indigo Ordeals. There is just one: [Indigo Noon](/api/Global/Misc/ScavengerNoonOrdeal).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → ScavengerOrdeal

## Derived
[ScavengerNoonOrdeal](/api/Global/Misc/ScavengerNoonOrdeal)

## Inherited Members
[level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealNameText(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#ordealnametext-ordealcreaturemodel), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Misc/OrdealBase#getrisklevel-ordealcreaturemodel), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ScavengerOrdeal()

```csharp
public ScavengerOrdeal()
```
#INC


## Fields

### _color

```csharp
protected Color _color
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### _curOrdealCreatureList

```csharp
protected List<OrdealCreatureModel> _curOrdealCreatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OrdealCreatureModel}

### _ordealName

```csharp
protected string _ordealName
```
#INC


#### Field Value

**Type:** System.String

### ids

```csharp
private static int[] ids
```
#INC


#### Field Value

**Type:** System.Int32[]

## Methods

### CheckCloseCondition()

```csharp
protected virtual bool CheckCloseCondition()
```
#INC


#### Returns

**Type:** System.Boolean

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### MakeOrdealCreature(OrdealLevel, MapNode, params UnitDirection[])

```csharp
public ScavengerOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, params UnitDirection[] direction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |
| `direction` | `Global.UnitDirection[]` |  |

#### Returns

**Type:** Global.ScavengerOrdealCreature

### OnDie(OrdealCreatureModel)

```csharp
public virtual void OnDie(OrdealCreatureModel model)
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


### OrdealEnd()

```csharp
public override void OrdealEnd()
```
#INC


### SetColor()

```csharp
protected void SetColor()
```
#INC

