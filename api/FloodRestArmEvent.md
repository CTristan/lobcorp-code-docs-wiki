# Class FloodRestArmEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FloodRestArmEvent : RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/RandomEventBase) → FloodRestArmEvent

## Inherited Members
[rootObjectSrc](/api/RandomEventBase#rootobjectsrc), [rootObjectId](/api/RandomEventBase#rootobjectid), [type](/api/RandomEventBase#type), [rank](/api/RandomEventBase#rank), [metaInfo](/api/RandomEventBase#metainfo), [rootGameObject](/api/RandomEventBase#rootgameobject), [rootStanding](/api/RandomEventBase#rootstanding), [enableCheckConditions](/api/RandomEventBase#enablecheckconditions), [instanceId](/api/RandomEventBase#instanceid), [_isEnabled](/api/RandomEventBase#isenabled), [GenerateCondition()](/api/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/RandomEventBase#ondestroy), [OnEnd()](/api/RandomEventBase#onend), [IsDuplicatable()](/api/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/RandomEventBase#checkcondition), [ManualDisable()](/api/RandomEventBase#manualdisable), [ManualDisable(string)](/api/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/RandomEventBase#generatetypo-string), [OnUpdate()](/api/RandomEventBase#onupdate), [GetCondition(string)](/api/RandomEventBase#getcondition-string), [MakeRootObject()](/api/RandomEventBase#makerootobject), [GetTimerCondition()](/api/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/RandomEventBase#roottransform), [HasRootObject](/api/RandomEventBase#hasrootobject), [MetaDataId](/api/RandomEventBase#metadataid), [IsEnabled](/api/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Single

### DelayEnableMin

```csharp
public const float DelayEnableMin = 1
```

#### Field Value

**Type:** System.Single

### GenerateCount

```csharp
public const int GenerateCount = 1
```

#### Field Value

**Type:** System.Int32

### GenerateFrequency

```csharp
public const float GenerateFrequency = 10
```

#### Field Value

**Type:** System.Single

### InitialObjectCountPerSefira

```csharp
public const int InitialObjectCountPerSefira = 15
```

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

#### Field Value

**Type:** System.Int32

### rootScale

```csharp
public const float rootScale = 2.5
```

#### Field Value

**Type:** System.Single

### sefiraLists

```csharp
public Dictionary<string, List<FloodTentacle>> sefiraLists
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{FloodTentacle}}

### tentacleBgm

```csharp
public const string tentacleBgm = "RandomEvent/Tentacle_Bgm"
```

#### Field Value

**Type:** System.String

### tentacleID

```csharp
public const long tentacleID = 1001
```

#### Field Value

**Type:** System.Int64

### tentacleSrcA

```csharp
public const string tentacleSrcA = "StandingItem/FloodRestTentacle_A"
```

#### Field Value

**Type:** System.String

### tentacleSrcB

```csharp
public const string tentacleSrcB = "StandingItem/FloodRestTentacle_B"
```

#### Field Value

**Type:** System.String

### tentacleSrcC

```csharp
public const string tentacleSrcC = "StandingItem/FloodRestTentacle_C"
```

#### Field Value

**Type:** System.String

## Methods

### DisableTentacle(FloodTentacle)

```csharp
public void DisableTentacle(FloodTentacle script)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{FloodTentacle}

### LoadTentacle(TentacleType, out FloodTentacle)

```csharp
public GameObject LoadTentacle(FloodTentacle.TentacleType type, out FloodTentacle script)
```

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

### OnEnable()

```csharp
public override void OnEnable()
```

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnInit()

```csharp
public override void OnInit()
```

### SetTentacleType(FloodTentacle, StandingItemUnit, TentacleType)

```csharp
public void SetTentacleType(FloodTentacle script, StandingItemUnit unit, FloodTentacle.TentacleType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FloodTentacle` |  |
| `unit` | `Global.StandingItemUnit` |  |
| `type` | `Global.FloodTentacle.TentacleType` |  |
