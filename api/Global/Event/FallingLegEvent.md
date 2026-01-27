---
uid: Global.FallingLegEvent
canonical_path: /api/Global/Event/FallingLegEvent
---

# Class FallingLegEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FallingLegEvent : RandomEventBase
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Misc/RandomEventBase) → FallingLegEvent

## Inherited Members
[rootObjectSrc](/api/Global/Misc/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Misc/RandomEventBase#rootobjectid), [type](/api/Global/Misc/RandomEventBase#type), [rank](/api/Global/Misc/RandomEventBase#rank), [metaInfo](/api/Global/Misc/RandomEventBase#metainfo), [rootGameObject](/api/Global/Misc/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Misc/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Misc/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Misc/RandomEventBase#instanceid), [_isEnabled](/api/Global/Misc/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Misc/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Misc/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Misc/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Misc/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Misc/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Misc/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Misc/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Misc/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Misc/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Misc/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Misc/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Misc/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Misc/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Misc/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Misc/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Misc/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Misc/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Misc/RandomEventBase#roottransform), [HasRootObject](/api/Global/Misc/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Misc/RandomEventBase#metadataid), [IsEnabled](/api/Global/Misc/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FallingLegEvent()

```csharp
public FallingLegEvent()
```

## Fields

### animSrc

```csharp
private const string animSrc = "StandingItem/ChopLeg"
```
#INC


#### Field Value

**Type:** System.String

### animSrcA

```csharp
private const string animSrcA = "StandingItem/ChopLegA"
```
#INC


#### Field Value

**Type:** System.String

### animSrcB

```csharp
private const string animSrcB = "StandingItem/ChopLegB"
```
#INC


#### Field Value

**Type:** System.String

### animSrcC

```csharp
private const string animSrcC = "StandingItem/ChopLegC"
```
#INC


#### Field Value

**Type:** System.String

### AttackFreq

```csharp
public const float AttackFreq = 3
```
#INC


#### Field Value

**Type:** System.Single

### disableCheck

```csharp
private bool disableCheck
```
#INC


#### Field Value

**Type:** System.Boolean

### disableTime

```csharp
private const float disableTime = 120
```
#INC


#### Field Value

**Type:** System.Single

### disableTimer

```csharp
public Timer disableTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### legId

```csharp
private const long legId = 1002
```
#INC


#### Field Value

**Type:** System.Int64

### legs

```csharp
private List<StandingItemModel> legs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{StandingItemModel}

### management

```csharp
public List<FallingLegEvent.SefiraManagement> management
```

#### Field Value

**Type:** System.Collections.Generic.List{FallingLegEvent.SefiraManagement}

## Methods

### DelayedDisable()

```csharp
private void DelayedDisable()
```
#INC


### DisableLeb(string)

```csharp
public void DisableLeb(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### EnableLeg(string)

```csharp
public void EnableLeg(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### GetLegType()

```csharp
public ChopLeg.LegType GetLegType()
```
#INC


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
#INC


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
#INC


### OnEnable()

```csharp
public override void OnEnable()
```
#INC


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
#code-generated

