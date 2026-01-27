---
uid: Global.OrdealBase
canonical_path: /api/Global/Misc/OrdealBase
---

# Class OrdealBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OrdealBase
```
Base class for ordeals.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OrdealBase

## Derived
[BugOrdeal](/api/Global/Misc/BugOrdeal), [CircusOrdeal](/api/Global/Misc/CircusOrdeal), [FixerOrdeal](/api/Global/Misc/FixerOrdeal), [MachineOrdeal](/api/Global/Misc/MachineOrdeal), [OutterGodOrdeal](/api/Global/Misc/OutterGodOrdeal), [ScavengerOrdeal](/api/Global/Misc/ScavengerOrdeal)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OrdealBase()

```csharp
public OrdealBase()
```

## Fields

### _canTakeRewards

```csharp
private bool _canTakeRewards
```
#INC


#### Field Value

**Type:** System.Boolean

### _ordeal_name

```csharp
private string _ordeal_name
```
#INC


#### Field Value

**Type:** System.String

### isStarted

```csharp
public bool isStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### level

```csharp
public OrdealLevel level
```
#INC


#### Field Value

**Type:** Global.OrdealLevel

### OrdealColor

```csharp
public Color OrdealColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### ordealRewards

```csharp
public readonly int[] ordealRewards
```
#INC


#### Field Value

**Type:** System.Int32[]

### riskLevel

```csharp
private RiskLevel riskLevel
```
#INC


#### Field Value

**Type:** Global.RiskLevel

### startTime

```csharp
public int startTime
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### canTakeRewards

```csharp
public bool canTakeRewards { protected get; set; }
```

#### Property Value

**Type:** System.Boolean

### OrdealTypeText

```csharp
public virtual string OrdealTypeText { get; }
```

#### Property Value

**Type:** System.String

## Methods

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### GetRiskLevel(OrdealCreatureModel)

```csharp
public virtual RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** Global.RiskLevel

### IsStartable()

```csharp
public virtual bool IsStartable()
```
#INC


#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnGameInit()

```csharp
public virtual void OnGameInit()
```
#INC


### OnOrdealStart()

```csharp
public virtual void OnOrdealStart()
```
#INC


### OrdealEnd()

```csharp
public virtual void OrdealEnd()
```
#INC


### OrdealNameText(OrdealCreatureModel)

```csharp
public virtual string OrdealNameText(OrdealCreatureModel ordeal)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |

#### Returns

**Type:** System.String

### OrdealTypo(string, Color, bool, int)

```csharp
public virtual void OrdealTypo(string ordealName, Color color, bool isStart = true, int reward = 0)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordealName` | `System.String` |  |
| `color` | `UnityEngine.Color` |  |
| `isStart` | `System.Boolean` |  |
| `reward` | `System.Int32` |  |

### SetRiskLevel(RiskLevel)

```csharp
public void SetRiskLevel(RiskLevel value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `Global.RiskLevel` |  |
