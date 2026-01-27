---
uid: Global.OrdealManager
canonical_path: /api/Global/Misc/OrdealManager
---

# Class OrdealManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OrdealManager
```
Manages [ordeals](/api/Global/Misc/OrdealBase).

Holds a queue of ordeals from the day, as well as methods for activating ordeals, adding creatures, and behavior on start and end.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OrdealManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OrdealManager()

```csharp
public OrdealManager()
```

## Fields

### _activatedOrdeals

```csharp
private List<OrdealBase> _activatedOrdeals
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OrdealBase}

### _currentOrdealLevel

```csharp
private int _currentOrdealLevel
```
#INC


#### Field Value

**Type:** System.Int32

### _elapsedTime

```csharp
private float _elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _instance

```csharp
private static OrdealManager _instance
```
#INC


#### Field Value

**Type:** Global.OrdealManager

### _ordealList

```csharp
private List<OrdealBase> _ordealList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OrdealBase}

### _ordealQueue

```csharp
private Queue<OrdealBase> _ordealQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{OrdealBase}

### _remainTime

```csharp
private float _remainTime
```
#INC


#### Field Value

**Type:** System.Single

### _removedOrdeals

```csharp
private List<OrdealBase> _removedOrdeals
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OrdealBase}

### availableFixers

```csharp
public List<RwbpType> availableFixers
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RwbpType}

### needWorkCount

```csharp
private readonly int[] needWorkCount
```
#INC


#### Field Value

**Type:** System.Int32[]

### nextInstId

```csharp
private int nextInstId
```
#INC


#### Field Value

**Type:** System.Int32

### ordealCreatureList

```csharp
private List<OrdealCreatureModel> ordealCreatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OrdealCreatureModel}

### ordealTimer

```csharp
private readonly int[] ordealTimer
```
#INC


#### Field Value

**Type:** System.Int32[]

### ordealTimer1

```csharp
private readonly int[] ordealTimer1
```
#INC


#### Field Value

**Type:** System.Int32[]

### ordealTimer2

```csharp
private readonly int[] ordealTimer2
```
#INC


#### Field Value

**Type:** System.Int32[]

## Properties

### instance

```csharp
public static OrdealManager instance { get; }
```

#### Property Value

**Type:** Global.OrdealManager

## Methods

### ActivateOrdeal(OrdealBase, bool)

```csharp
public bool ActivateOrdeal(OrdealBase ordeal, bool remove = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |
| `remove` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### AddCreature(long, MapNode, OrdealBase)

```csharp
public OrdealCreatureModel AddCreature(long metadataId, MapNode pos, OrdealBase ordealBase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `pos` | `Global.MapNode` |  |
| `ordealBase` | `Global.OrdealBase` |  |

#### Returns

**Type:** Global.OrdealCreatureModel

### BuildCreature(OrdealCreatureModel, long)

```csharp
private void BuildCreature(OrdealCreatureModel model, long metadataId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |
| `metadataId` | `System.Int64` |  |

### CheckOrdealContains(OrdealLevel, out OrdealBase)

```csharp
public bool CheckOrdealContains(OrdealLevel level, out OrdealBase ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `ordeal` | `Global.OrdealBase` |  |

#### Returns

**Type:** System.Boolean

### ClearCreatures()

```csharp
public void ClearCreatures()
```
#INC


### GetActivatedOrdeals()

```csharp
public List<OrdealBase> GetActivatedOrdeals()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{OrdealBase}

### GetMaxOrdealLevel()

```csharp
public OrdealLevel GetMaxOrdealLevel()
```
#INC


#### Returns

**Type:** Global.OrdealLevel

### GetOrdealCreatureList()

```csharp
public OrdealCreatureModel[] GetOrdealCreatureList()
```
#INC


#### Returns

**Type:** Global.OrdealCreatureModel[]

### InitAvailableFixers()

```csharp
public void InitAvailableFixers()
```
#INC


### OnAddCreatureWorkCount()

```csharp
public void OnAddCreatureWorkCount()
```
#INC


### OnAddCreatureWorkCount(OrdealBase)

```csharp
private void OnAddCreatureWorkCount(OrdealBase ordeal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGameInit()

```csharp
public void OnGameInit()
```
#INC
#code-generated


### OnOrdealEnd(OrdealBase, bool)

```csharp
public void OnOrdealEnd(OrdealBase ordeal, bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |
| `b` | `System.Boolean` |  |

### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### UpdateOrdealUI()

```csharp
private void UpdateOrdealUI()
```
#INC

