---
uid: Global.MachineOrdeal
canonical_path: /api/Global/Misc/MachineOrdeal
---

# Class MachineOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MachineOrdeal : OrdealBase
```

Parent class for the Ordeals of Green.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → MachineOrdeal

## Derived
[MachineDawnOrdeal](/api/Global/Machine/MachineDawnOrdeal), [MachineDuskOrdeal](/api/Global/Machine/MachineDuskOrdeal), [MachineMidnightOrdeal](/api/Global/Machine/MachineMidnightOrdeal), [MachineNoonOrdeal](/api/Global/Machine/MachineNoonOrdeal)

## Inherited Members
[level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MachineOrdeal()

```csharp
public MachineOrdeal()
```

## Fields

### _color

```csharp
protected readonly Color _color
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

### MakeOrdealCreature(OrdealLevel, MapNode)

```csharp
public virtual MachineOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.MachineOrdealCreature

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
