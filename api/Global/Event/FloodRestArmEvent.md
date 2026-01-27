---
uid: Global.FloodRestArmEvent
canonical_path: /api/Global/Event/FloodRestArmEvent
---

# Class FloodRestArmEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FloodRestArmEvent : RandomEventBase
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Misc/RandomEventBase) → FloodRestArmEvent

## Inherited Members
[rootObjectSrc](/api/Global/Misc/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Misc/RandomEventBase#rootobjectid), [type](/api/Global/Misc/RandomEventBase#type), [rank](/api/Global/Misc/RandomEventBase#rank), [metaInfo](/api/Global/Misc/RandomEventBase#metainfo), [rootGameObject](/api/Global/Misc/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Misc/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Misc/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Misc/RandomEventBase#instanceid), [_isEnabled](/api/Global/Misc/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Misc/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Misc/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Misc/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Misc/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Misc/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Misc/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Misc/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Misc/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Misc/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Misc/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Misc/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Misc/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Misc/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Misc/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Misc/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Misc/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Misc/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Misc/RandomEventBase#roottransform), [HasRootObject](/api/Global/Misc/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Misc/RandomEventBase#metadataid), [IsEnabled](/api/Global/Misc/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FloodRestArmEvent()

```csharp
public FloodRestArmEvent()
```

## Fields

### DelayEnableMax

```csharp
public const float DelayEnableMax = 3
```
#INC


#### Field Value

**Type:** System.Single

### DelayEnableMin

```csharp
public const float DelayEnableMin = 1
```
#INC


#### Field Value

**Type:** System.Single

### GenerateCount

```csharp
public const int GenerateCount = 1
```
#INC


#### Field Value

**Type:** System.Int32

### GenerateFrequency

```csharp
public const float GenerateFrequency = 10
```
#INC


#### Field Value

**Type:** System.Single

### generatorTimer

```csharp
private Timer generatorTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### InitialObjectCountPerSefira

```csharp
public const int InitialObjectCountPerSefira = 15
```
#INC


#### Field Value

**Type:** System.Int32

### management

```csharp
public List<FloodRestArmEvent.SefiraManagement> management
```

#### Field Value

**Type:** System.Collections.Generic.List{FloodRestArmEvent.SefiraManagement}

### MaximumObjectCountPerSefira

```csharp
public const int MaximumObjectCountPerSefira = 15
```
#INC


#### Field Value

**Type:** System.Int32

### rootScale

```csharp
public const float rootScale = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### sefiraLists

```csharp
public Dictionary<string, List<FloodTentacle>> sefiraLists
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{FloodTentacle}}

### tentacleBgm

```csharp
public const string tentacleBgm = "RandomEvent/Tentacle_Bgm"
```
#INC


#### Field Value

**Type:** System.String

### tentacleID

```csharp
public const long tentacleID = 1001
```
#INC


#### Field Value

**Type:** System.Int64

### tentacles

```csharp
private List<StandingItemModel> tentacles
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{StandingItemModel}

### tentacleSrcA

```csharp
public const string tentacleSrcA = "StandingItem/FloodRestTentacle_A"
```
#INC


#### Field Value

**Type:** System.String

### tentacleSrcB

```csharp
public const string tentacleSrcB = "StandingItem/FloodRestTentacle_B"
```
#INC


#### Field Value

**Type:** System.String

### tentacleSrcC

```csharp
public const string tentacleSrcC = "StandingItem/FloodRestTentacle_C"
```
#INC


#### Field Value

**Type:** System.String

## Methods

### DisableTentacle(FloodTentacle)

```csharp
public void DisableTentacle(FloodTentacle script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FloodTentacle` |  |

### EnableTentacle(SefiraManagement, int)

```csharp
public void EnableTentacle(FloodRestArmEvent.SefiraManagement sefira, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.FloodRestArmEvent.SefiraManagement` |  |
| `count` | `System.Int32` |  |

### GetSefiraManagement(string)

```csharp
public FloodRestArmEvent.SefiraManagement GetSefiraManagement(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** Global.FloodRestArmEvent.SefiraManagement

### GetSefiraTentacles(string)

```csharp
public List<FloodTentacle> GetSefiraTentacles(string area)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{FloodTentacle}

### GetTentacleType()

```csharp
private FloodTentacle.TentacleType GetTentacleType()
```
#INC


#### Returns

**Type:** Global.FloodTentacle.TentacleType

### LoadTentacle(TentacleType, out FloodTentacle)

```csharp
public GameObject LoadTentacle(FloodTentacle.TentacleType type, out FloodTentacle script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.FloodTentacle.TentacleType` |  |
| `script` | `Global.FloodTentacle` |  |

#### Returns

**Type:** UnityEngine.GameObject

### OnDisable()

```csharp
public override void OnDisable()
```
#INC


### OnEnable()

```csharp
public override void OnEnable()
```
#INC
#code-generated


### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


### OnInit()

```csharp
public override void OnInit()
```
#INC


### SetTentacleType(FloodTentacle, StandingItemUnit, TentacleType)

```csharp
public void SetTentacleType(FloodTentacle script, StandingItemUnit unit, FloodTentacle.TentacleType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FloodTentacle` |  |
| `unit` | `Global.StandingItemUnit` |  |
| `type` | `Global.FloodTentacle.TentacleType` |  |
