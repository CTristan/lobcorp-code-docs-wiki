---
uid: Global.BugOrdeal
canonical_path: /api/Global/Misc/BugOrdeal
---

# Class BugOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugOrdeal : OrdealBase
```

Amber ordeal parent class.

(Seems to think there should be a bug noon... It's wrong.)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → BugOrdeal

## Derived
[BugDawnOrdeal](/api/Global/Misc/BugDawnOrdeal), [BugDuskOrdeal](/api/Global/Misc/BugDuskOrdeal), [BugMidnightOrdeal](/api/Global/Misc/BugMidnightOrdeal)

## Inherited Members
[level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugOrdeal()

```csharp
public BugOrdeal()
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

### names

```csharp
private static string[] names
```
#INC


#### Field Value

**Type:** System.String[]

### risks

```csharp
private static RiskLevel[] risks
```
#INC


#### Field Value

**Type:** Global.RiskLevel[]

## Methods

### AddChildBug(OrdealCreatureModel)

```csharp
public void AddChildBug(OrdealCreatureModel child)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.OrdealCreatureModel` |  |

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


### GetRiskLevel(OrdealCreatureModel)

```csharp
public override RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```
#INC
#code-generated


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


### OrdealNameText(OrdealCreatureModel)

```csharp
public override string OrdealNameText(OrdealCreatureModel ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** System.String

### SetColor()

```csharp
private void SetColor()
```
#INC

