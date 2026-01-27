---
uid: Global.FixerOrdeal
canonical_path: /api/Global/Misc/FixerOrdeal
---

# Class FixerOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerOrdeal : OrdealBase
```

Ordeals of White.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Misc/OrdealBase) → FixerOrdeal

## Inherited Members
[level](/api/Global/Misc/OrdealBase#level), [riskLevel](/api/Global/Misc/OrdealBase#risklevel), [ordealRewards](/api/Global/Misc/OrdealBase#ordealrewards), [startTime](/api/Global/Misc/OrdealBase#starttime), [isStarted](/api/Global/Misc/OrdealBase#isstarted), [_ordeal_name](/api/Global/Misc/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Misc/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Misc/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Misc/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Misc/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Misc/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Misc/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Misc/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Misc/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FixerOrdeal(OrdealLevel)

```csharp
public FixerOrdeal(OrdealLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

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

### _spawn_dawn

```csharp
private const int _spawn_dawn = 1
```
#INC


#### Field Value

**Type:** System.Int32

### _spawn_dusk

```csharp
private const int _spawn_dusk = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _spawn_noon

```csharp
private const int _spawn_noon = 2
```
#INC


#### Field Value

**Type:** System.Int32

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
#code-generated


### GetRiskLevel(OrdealCreatureModel)

```csharp
public override RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** Global.RiskLevel

### GetTargetNodes()

```csharp
private List<MapNode> GetTargetNodes()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{MapNode}

### MakeClaw()

```csharp
private void MakeClaw()
```
#INC


### MakeFixers()

```csharp
private void MakeFixers()
```
#INC


### MakeOrdealCreature(RwbpType, MapNode)

```csharp
public FixerCreature MakeOrdealCreature(RwbpType type, MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.FixerCreature

### MakeOrdealCreature_Midnight(MapNode)

```csharp
public FixerCreature MakeOrdealCreature_Midnight(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.FixerCreature

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
protected void SetColor()
```
#INC

