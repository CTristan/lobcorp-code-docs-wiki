# Class BoomerCircusEvent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BoomerCircusEvent : RandomEventBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/RandomEventBase) → BoomerCircusEvent

## Inherited Members
[rootObjectSrc](/api/RandomEventBase#rootobjectsrc), [rootObjectId](/api/RandomEventBase#rootobjectid), [type](/api/RandomEventBase#type), [rank](/api/RandomEventBase#rank), [metaInfo](/api/RandomEventBase#metainfo), [rootGameObject](/api/RandomEventBase#rootgameobject), [rootStanding](/api/RandomEventBase#rootstanding), [enableCheckConditions](/api/RandomEventBase#enablecheckconditions), [instanceId](/api/RandomEventBase#instanceid), [_isEnabled](/api/RandomEventBase#isenabled), [GenerateCondition()](/api/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/RandomEventBase#ondestroy), [OnEnd()](/api/RandomEventBase#onend), [IsDuplicatable()](/api/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/RandomEventBase#checkcondition), [ManualDisable()](/api/RandomEventBase#manualdisable), [ManualDisable(string)](/api/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/RandomEventBase#generatetypo-string), [OnUpdate()](/api/RandomEventBase#onupdate), [GetCondition(string)](/api/RandomEventBase#getcondition-string), [MakeRootObject()](/api/RandomEventBase#makerootobject), [GetTimerCondition()](/api/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/RandomEventBase#roottransform), [HasRootObject](/api/RandomEventBase#hasrootobject), [MetaDataId](/api/RandomEventBase#metadataid), [IsEnabled](/api/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Int64

### boomerMax

```csharp
public static int boomerMax
```

#### Field Value

**Type:** System.Int32

### boomerSrc

```csharp
public const string boomerSrc = "StandingItem/BoomerCircus/CircusBoomer"
```

#### Field Value

**Type:** System.String

### circusBgm

```csharp
public const string circusBgm = ""
```

#### Field Value

**Type:** System.String

### tentId

```csharp
public const long tentId = 10051
```

#### Field Value

**Type:** System.Int64

### tentMax

```csharp
public static int tentMax
```

#### Field Value

**Type:** System.Int32

### tentSrc

```csharp
public const string tentSrc = "StandingItem/BoomerCircus/CircusTent"
```

#### Field Value

**Type:** System.String

## Methods

### DisableCircus(BoomerCircusScript)

```csharp
public void DisableCircus(BoomerCircusScript script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BoomerCircusScript` |  |

### EnableCircus(CircusType, MapNode)

```csharp
public void EnableCircus(BoomerCircusScript.CircusType type, MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.BoomerCircusScript.CircusType` |  |
| `node` | `Global.MapNode` |  |

### LoadCircus(string, long, out BoomerCircusScript)

```csharp
public GameObject LoadCircus(string src, long metaId, out BoomerCircusScript script)
```

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
