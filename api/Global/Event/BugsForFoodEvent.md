---
uid: Global.BugsForFoodEvent
canonical_path: /api/Global/Event/BugsForFoodEvent
---

# Class BugsForFoodEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugsForFoodEvent : RandomEventBase
```
Old version of amber ordeal?
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Misc/RandomEventBase) → BugsForFoodEvent

## Inherited Members
[rootObjectSrc](/api/Global/Misc/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Misc/RandomEventBase#rootobjectid), [type](/api/Global/Misc/RandomEventBase#type), [rank](/api/Global/Misc/RandomEventBase#rank), [metaInfo](/api/Global/Misc/RandomEventBase#metainfo), [rootGameObject](/api/Global/Misc/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Misc/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Misc/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Misc/RandomEventBase#instanceid), [_isEnabled](/api/Global/Misc/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Misc/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Misc/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Misc/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Misc/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Misc/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Misc/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Misc/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Misc/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Misc/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Misc/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Misc/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Misc/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Misc/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Misc/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Misc/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Misc/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Misc/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Misc/RandomEventBase#roottransform), [HasRootObject](/api/Global/Misc/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Misc/RandomEventBase#metadataid), [IsEnabled](/api/Global/Misc/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugsForFoodEvent()

```csharp
public BugsForFoodEvent()
```

## Fields

### bugBgm

```csharp
public const string bugBgm = ""
```
#INC


#### Field Value

**Type:** System.String

### bugID

```csharp
public const long bugID = 1003
```
#INC


#### Field Value

**Type:** System.Int64

### bugs

```csharp
private List<TastyBug> bugs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{TastyBug}

### bugsPerPassageMax

```csharp
public const int bugsPerPassageMax = 4
```
#INC


#### Field Value

**Type:** System.Int32

### bugsPerPassageMin

```csharp
public const int bugsPerPassageMin = 3
```
#INC


#### Field Value

**Type:** System.Int32

### bugSrcA

```csharp
public const string bugSrcA = "StandingItem/TastyBugs/TastyBug_A"
```
#INC


#### Field Value

**Type:** System.String

### bugSrcB

```csharp
public const string bugSrcB = "StandingItem/TastyBugs/TastyBug_B"
```
#INC


#### Field Value

**Type:** System.String

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

## Methods

### DisableBugs(TastyBug)

```csharp
public void DisableBugs(TastyBug bug)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bug` | `Global.TastyBug` |  |

### GenBugsInPassage(PassageObjectModel)

```csharp
public void GenBugsInPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### GetBugType()

```csharp
private TastyBug.BugType GetBugType()
```
#INC


#### Returns

**Type:** Global.TastyBug.BugType

### LoadBug(BugType, out TastyBug)

```csharp
public GameObject LoadBug(TastyBug.BugType type, out TastyBug script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.TastyBug.BugType` |  |
| `script` | `Global.TastyBug` |  |

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


### SetBugType(TastyBug, StandingItemUnit, BugType)

```csharp
public void SetBugType(TastyBug script, StandingItemUnit unit, TastyBug.BugType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.TastyBug` |  |
| `unit` | `Global.StandingItemUnit` |  |
| `type` | `Global.TastyBug.BugType` |  |
