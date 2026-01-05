# Class FallingLegEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FallingLegEvent : RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/RandomEventBase) → FallingLegEvent

## Inherited Members
[rootObjectSrc](/api/RandomEventBase#rootobjectsrc), [rootObjectId](/api/RandomEventBase#rootobjectid), [type](/api/RandomEventBase#type), [rank](/api/RandomEventBase#rank), [metaInfo](/api/RandomEventBase#metainfo), [rootGameObject](/api/RandomEventBase#rootgameobject), [rootStanding](/api/RandomEventBase#rootstanding), [enableCheckConditions](/api/RandomEventBase#enablecheckconditions), [instanceId](/api/RandomEventBase#instanceid), [_isEnabled](/api/RandomEventBase#isenabled), [GenerateCondition()](/api/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/RandomEventBase#ondestroy), [OnEnd()](/api/RandomEventBase#onend), [IsDuplicatable()](/api/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/RandomEventBase#checkcondition), [ManualDisable()](/api/RandomEventBase#manualdisable), [ManualDisable(string)](/api/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/RandomEventBase#generatetypo-string), [OnUpdate()](/api/RandomEventBase#onupdate), [GetCondition(string)](/api/RandomEventBase#getcondition-string), [MakeRootObject()](/api/RandomEventBase#makerootobject), [GetTimerCondition()](/api/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/RandomEventBase#roottransform), [HasRootObject](/api/RandomEventBase#hasrootobject), [MetaDataId](/api/RandomEventBase#metadataid), [IsEnabled](/api/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FallingLegEvent()

```csharp
public FallingLegEvent()
```

## Fields

### AttackFreq

```csharp
public const float AttackFreq = 3
```

#### Field Value

**Type:** System.Single

### disableTimer

```csharp
public Timer disableTimer
```

#### Field Value

**Type:** Global.Timer

### management

```csharp
public List<FallingLegEvent.SefiraManagement> management
```

#### Field Value

**Type:** System.Collections.Generic.List{FallingLegEvent.SefiraManagement}

## Methods

### DisableLeb(string)

```csharp
public void DisableLeb(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### EnableLeg(string)

```csharp
public void EnableLeg(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### GetLegType()

```csharp
public ChopLeg.LegType GetLegType()
```

#### Returns

**Type:** Global.ChopLeg.LegType

### GetSefiraManagement(string)

```csharp
public FallingLegEvent.SefiraManagement GetSefiraManagement(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** Global.FallingLegEvent.SefiraManagement

### LoadLeg(out ChopLeg)

```csharp
public GameObject LoadLeg(out ChopLeg leg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `leg` | `Global.ChopLeg` |  |

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
