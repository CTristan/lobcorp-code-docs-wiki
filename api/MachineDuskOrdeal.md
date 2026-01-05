# Class MachineDuskOrdeal

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MachineDuskOrdeal : MachineOrdeal
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/OrdealBase) → [MachineOrdeal](/api/MachineOrdeal) → MachineDuskOrdeal

## Inherited Members
[_curOrdealCreatureList](/api/MachineOrdeal#curordealcreaturelist), [_color](/api/MachineOrdeal#color), [_ordealName](/api/MachineOrdeal#ordealname), [GetRiskLevel(OrdealCreatureModel)](/api/MachineOrdeal#getrisklevel-ordealcreaturemodel), [OrdealNameText(OrdealCreatureModel)](/api/MachineOrdeal#ordealnametext-ordealcreaturemodel), [CheckCloseCondition()](/api/MachineOrdeal#checkclosecondition), [OnDie(OrdealCreatureModel)](/api/MachineOrdeal#ondie-ordealcreaturemodel), [OrdealEnd()](/api/MachineOrdeal#ordealend), [level](/api/OrdealBase#level), [ordealRewards](/api/OrdealBase#ordealrewards), [startTime](/api/OrdealBase#starttime), [isStarted](/api/OrdealBase#isstarted), [OrdealColor](/api/OrdealBase#ordealcolor), [OnGameInit()](/api/OrdealBase#ongameinit), [OnDestroy()](/api/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/OrdealBase#cantakerewards), [OrdealTypeText](/api/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MachineDuskOrdeal()

```csharp
public MachineDuskOrdeal()
```

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### MakeOrdealCreature(OrdealLevel, MapNode)

```csharp
public override MachineOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.MachineOrdealCreature

### OnOrdealStart()

```csharp
public override void OnOrdealStart()
```
