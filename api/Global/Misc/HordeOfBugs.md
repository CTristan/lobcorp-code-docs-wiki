---
uid: Global.HordeOfBugs
canonical_path: /api/Global/Misc/HordeOfBugs
---

# Class HordeOfBugs

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HordeOfBugs : RandomEventBase
```

Unused random event.

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Misc/RandomEventBase) → HordeOfBugs

## Inherited Members
[rootObjectSrc](/api/Global/Misc/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Misc/RandomEventBase#rootobjectid), [type](/api/Global/Misc/RandomEventBase#type), [rank](/api/Global/Misc/RandomEventBase#rank), [metaInfo](/api/Global/Misc/RandomEventBase#metainfo), [rootGameObject](/api/Global/Misc/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Misc/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Misc/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Misc/RandomEventBase#instanceid), [_isEnabled](/api/Global/Misc/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Misc/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Misc/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Misc/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Misc/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Misc/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Misc/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Misc/RandomEventBase#checkcondition), [ManualDisable(string)](/api/Global/Misc/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Misc/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Misc/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Misc/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Misc/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Misc/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Misc/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Misc/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Misc/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Misc/RandomEventBase#roottransform), [HasRootObject](/api/Global/Misc/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Misc/RandomEventBase#metadataid), [IsEnabled](/api/Global/Misc/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### HordeOfBugs()

```csharp
public HordeOfBugs()
```

## Fields

### bugs

```csharp
private List<TastyBug> bugs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{TastyBug}

### daughterBugs

```csharp
private List<DaughterBug> daughterBugs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{DaughterBug}

### daughterBugSrc

```csharp
public const string daughterBugSrc = "StandingItem/DaughterBugAnim"
```
#INC


#### Field Value

**Type:** System.String

### daughterId

```csharp
public const long daughterId = 10043
```
#INC


#### Field Value

**Type:** System.Int64

### daughterMax

```csharp
public const int daughterMax = 100
```
#INC


#### Field Value

**Type:** System.Int32

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

### grandBug

```csharp
private GrandmaBug grandBug
```
#INC


#### Field Value

**Type:** Global.GrandmaBug

### grandBugSrc

```csharp
public const string grandBugSrc = "StandingItem/TastyBugs/GrandBug"
```
#INC


#### Field Value

**Type:** System.String

### grandmaId

```csharp
public const long grandmaId = 10041
```
#INC


#### Field Value

**Type:** System.Int64

### hordeBgm

```csharp
public const string hordeBgm = ""
```
#INC


#### Field Value

**Type:** System.String

### motherBugs

```csharp
private List<MotherBug> motherBugs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MotherBug}

### motherBugSrc

```csharp
public const string motherBugSrc = "StandingItem/HordeOfBugs/MotherBug"
```
#INC


#### Field Value

**Type:** System.String

### motherId

```csharp
public const long motherId = 10042
```
#INC


#### Field Value

**Type:** System.Int64

### motherMax

```csharp
public const int motherMax = 20
```
#INC


#### Field Value

**Type:** System.Int32

### numOfDaughters

```csharp
public int numOfDaughters
```
#INC


#### Field Value

**Type:** System.Int32

### numOfMothers

```csharp
public int numOfMothers
```
#INC


#### Field Value

**Type:** System.Int32

### sefiraPassages

```csharp
public List<PassageObjectModel> sefiraPassages
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

## Methods

### EnableBugs(BugType, MapNode, params UnitDirection[])

```csharp
public void EnableBugs(HordeOfBugsScript.BugType type, MapNode node, params UnitDirection[] direction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.HordeOfBugsScript.BugType` |  |
| `node` | `Global.MapNode` |  |
| `direction` | `Global.UnitDirection[]` |  |

### GetOtherpassage(PassageObjectModel)

```csharp
public PassageObjectModel GetOtherpassage(PassageObjectModel current)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.PassageObjectModel

### GetRandomTargetPassage()

```csharp
public PassageObjectModel GetRandomTargetPassage()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### LoadBug(string, long, out HordeOfBugsScript)

```csharp
public GameObject LoadBug(string src, long metaId, out HordeOfBugsScript script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `metaId` | `System.Int64` |  |
| `script` | `Global.HordeOfBugsScript` |  |

#### Returns

**Type:** UnityEngine.GameObject

### ManualDisable()

```csharp
public override void ManualDisable()
```
#INC


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


### SetTime(float)

```csharp
public void SetTime(float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
