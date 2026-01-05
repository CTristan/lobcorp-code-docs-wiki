# Class BugsForFoodEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugsForFoodEvent : RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/RandomEventBase) → BugsForFoodEvent

## Inherited Members
[rootObjectSrc](/api/RandomEventBase#rootobjectsrc), [rootObjectId](/api/RandomEventBase#rootobjectid), [type](/api/RandomEventBase#type), [rank](/api/RandomEventBase#rank), [metaInfo](/api/RandomEventBase#metainfo), [rootGameObject](/api/RandomEventBase#rootgameobject), [rootStanding](/api/RandomEventBase#rootstanding), [enableCheckConditions](/api/RandomEventBase#enablecheckconditions), [instanceId](/api/RandomEventBase#instanceid), [_isEnabled](/api/RandomEventBase#isenabled), [GenerateCondition()](/api/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/RandomEventBase#ondestroy), [OnEnd()](/api/RandomEventBase#onend), [IsDuplicatable()](/api/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/RandomEventBase#checkcondition), [ManualDisable()](/api/RandomEventBase#manualdisable), [ManualDisable(string)](/api/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/RandomEventBase#generatetypo-string), [OnUpdate()](/api/RandomEventBase#onupdate), [GetCondition(string)](/api/RandomEventBase#getcondition-string), [MakeRootObject()](/api/RandomEventBase#makerootobject), [GetTimerCondition()](/api/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/RandomEventBase#roottransform), [HasRootObject](/api/RandomEventBase#hasrootobject), [MetaDataId](/api/RandomEventBase#metadataid), [IsEnabled](/api/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.String

### bugID

```csharp
public const long bugID = 1003
```

#### Field Value

**Type:** System.Int64

### bugsPerPassageMax

```csharp
public const int bugsPerPassageMax = 4
```

#### Field Value

**Type:** System.Int32

### bugsPerPassageMin

```csharp
public const int bugsPerPassageMin = 3
```

#### Field Value

**Type:** System.Int32

### bugSrcA

```csharp
public const string bugSrcA = "StandingItem/TastyBugs/TastyBug_A"
```

#### Field Value

**Type:** System.String

### bugSrcB

```csharp
public const string bugSrcB = "StandingItem/TastyBugs/TastyBug_B"
```

#### Field Value

**Type:** System.String

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

## Methods

### DisableBugs(TastyBug)

```csharp
public void DisableBugs(TastyBug bug)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bug` | `Global.TastyBug` |  |

### GenBugsInPassage(PassageObjectModel)

```csharp
public void GenBugsInPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### LoadBug(BugType, out TastyBug)

```csharp
public GameObject LoadBug(TastyBug.BugType type, out TastyBug script)
```

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

### SetBugType(TastyBug, StandingItemUnit, BugType)

```csharp
public void SetBugType(TastyBug script, StandingItemUnit unit, TastyBug.BugType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.TastyBug` |  |
| `unit` | `Global.StandingItemUnit` |  |
| `type` | `Global.TastyBug.BugType` |  |
