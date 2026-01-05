# Class HordeOfBugs

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HordeOfBugs : RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/RandomEventBase) → HordeOfBugs

## Inherited Members
[rootObjectSrc](/api/RandomEventBase#rootobjectsrc), [rootObjectId](/api/RandomEventBase#rootobjectid), [type](/api/RandomEventBase#type), [rank](/api/RandomEventBase#rank), [metaInfo](/api/RandomEventBase#metainfo), [rootGameObject](/api/RandomEventBase#rootgameobject), [rootStanding](/api/RandomEventBase#rootstanding), [enableCheckConditions](/api/RandomEventBase#enablecheckconditions), [instanceId](/api/RandomEventBase#instanceid), [_isEnabled](/api/RandomEventBase#isenabled), [GenerateCondition()](/api/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/RandomEventBase#ondestroy), [OnEnd()](/api/RandomEventBase#onend), [IsDuplicatable()](/api/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/RandomEventBase#checkcondition), [ManualDisable(string)](/api/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/RandomEventBase#generatetypo-string), [OnUpdate()](/api/RandomEventBase#onupdate), [GetCondition(string)](/api/RandomEventBase#getcondition-string), [MakeRootObject()](/api/RandomEventBase#makerootobject), [GetTimerCondition()](/api/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/RandomEventBase#roottransform), [HasRootObject](/api/RandomEventBase#hasrootobject), [MetaDataId](/api/RandomEventBase#metadataid), [IsEnabled](/api/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### HordeOfBugs()

```csharp
public HordeOfBugs()
```

## Fields

### daughterBugSrc

```csharp
public const string daughterBugSrc = "StandingItem/DaughterBugAnim"
```

#### Field Value

**Type:** System.String

### daughterId

```csharp
public const long daughterId = 10043
```

#### Field Value

**Type:** System.Int64

### daughterMax

```csharp
public const int daughterMax = 100
```

#### Field Value

**Type:** System.Int32

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

### grandBugSrc

```csharp
public const string grandBugSrc = "StandingItem/TastyBugs/GrandBug"
```

#### Field Value

**Type:** System.String

### grandmaId

```csharp
public const long grandmaId = 10041
```

#### Field Value

**Type:** System.Int64

### hordeBgm

```csharp
public const string hordeBgm = ""
```

#### Field Value

**Type:** System.String

### motherBugSrc

```csharp
public const string motherBugSrc = "StandingItem/HordeOfBugs/MotherBug"
```

#### Field Value

**Type:** System.String

### motherId

```csharp
public const long motherId = 10042
```

#### Field Value

**Type:** System.Int64

### motherMax

```csharp
public const int motherMax = 20
```

#### Field Value

**Type:** System.Int32

### numOfDaughters

```csharp
public int numOfDaughters
```

#### Field Value

**Type:** System.Int32

### numOfMothers

```csharp
public int numOfMothers
```

#### Field Value

**Type:** System.Int32

### sefiraPassages

```csharp
public List<PassageObjectModel> sefiraPassages
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

## Methods

### EnableBugs(BugType, MapNode, params UnitDirection[])

```csharp
public void EnableBugs(HordeOfBugsScript.BugType type, MapNode node, params UnitDirection[] direction)
```

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

#### Returns

**Type:** Global.PassageObjectModel

### LoadBug(string, long, out HordeOfBugsScript)

```csharp
public GameObject LoadBug(string src, long metaId, out HordeOfBugsScript script)
```

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

### SetTime(float)

```csharp
public void SetTime(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
