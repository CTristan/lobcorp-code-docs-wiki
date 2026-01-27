---
uid: Global.BoomerCircusEvent
canonical_path: /api/Global/Event/BoomerCircusEvent
---

# Class BoomerCircusEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BoomerCircusEvent : RandomEventBase
```
The Noon of Crimson, The Harmony of Skin. I think. #INC 

No, wait, that would be [CircusNoon](/api/Global/Misc/CircusNoon). Uh. Hm. Older version?

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Misc/RandomEventBase) → BoomerCircusEvent

## Inherited Members
[rootObjectSrc](/api/Global/Misc/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Misc/RandomEventBase#rootobjectid), [type](/api/Global/Misc/RandomEventBase#type), [rank](/api/Global/Misc/RandomEventBase#rank), [metaInfo](/api/Global/Misc/RandomEventBase#metainfo), [rootGameObject](/api/Global/Misc/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Misc/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Misc/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Misc/RandomEventBase#instanceid), [_isEnabled](/api/Global/Misc/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Misc/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Misc/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Misc/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Misc/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Misc/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Misc/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Misc/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Misc/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Misc/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Misc/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Misc/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Misc/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Misc/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Misc/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Misc/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Misc/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Misc/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Misc/RandomEventBase#roottransform), [HasRootObject](/api/Global/Misc/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Misc/RandomEventBase#metadataid), [IsEnabled](/api/Global/Misc/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BoomerCircusEvent()

```csharp
public BoomerCircusEvent()
```

## Fields

### boomerId

```csharp
public const long boomerId = 10052
```
#INC


#### Field Value

**Type:** System.Int64

### boomerMax

```csharp
public static int boomerMax
```
#INC


#### Field Value

**Type:** System.Int32

### boomers

```csharp
private List<CircusBoomer> boomers
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CircusBoomer}

### boomerSrc

```csharp
public const string boomerSrc = "StandingItem/BoomerCircus/CircusBoomer"
```
#INC


#### Field Value

**Type:** System.String

### circusBgm

```csharp
public const string circusBgm = ""
```
#INC


#### Field Value

**Type:** System.String

### numOfBoomers

```csharp
private int numOfBoomers
```
#INC


#### Field Value

**Type:** System.Int32

### numOfTents

```csharp
private int numOfTents
```
#INC


#### Field Value

**Type:** System.Int32

### tentId

```csharp
public const long tentId = 10051
```
#INC


#### Field Value

**Type:** System.Int64

### tentMax

```csharp
public static int tentMax
```
#INC


#### Field Value

**Type:** System.Int32

### tents

```csharp
private List<CircusTent> tents
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CircusTent}

### tentSrc

```csharp
public const string tentSrc = "StandingItem/BoomerCircus/CircusTent"
```
#INC


#### Field Value

**Type:** System.String

## Methods

### DisableCircus(BoomerCircusScript)

```csharp
public void DisableCircus(BoomerCircusScript script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BoomerCircusScript` |  |

### EnableCircus(CircusType, MapNode)

```csharp
public void EnableCircus(BoomerCircusScript.CircusType type, MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.BoomerCircusScript.CircusType` |  |
| `node` | `Global.MapNode` |  |

### LoadCircus(string, long, out BoomerCircusScript)

```csharp
public GameObject LoadCircus(string src, long metaId, out BoomerCircusScript script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `metaId` | `System.Int64` |  |
| `script` | `Global.BoomerCircusScript` |  |

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

