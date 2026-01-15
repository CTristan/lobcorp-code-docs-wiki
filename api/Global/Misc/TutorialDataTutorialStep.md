---
uid: Global.TutorialData.TutorialStep
canonical_path: /api/Global/Misc/TutorialDataTutorialStep
---

# Class TutorialData.TutorialStep

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialData.TutorialStep
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TutorialData.TutorialStep

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TutorialStep()

```csharp
public TutorialStep()
```

## Fields

### _nodes

```csharp
private List<TutorialData.TutorialNode> _nodes
```

#### Field Value

**Type:** System.Collections.Generic.List{TutorialData.TutorialNode}

### _step

```csharp
private int _step
```

#### Field Value

**Type:** System.Int32

## Properties

### Step

```csharp
public int Step { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetTutorialNodeByIdx(int)

```csharp
public TutorialData.TutorialNode GetTutorialNodeByIdx(int idx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |

#### Returns

**Type:** Global.TutorialData.TutorialNode

### GetTutorialNodes()

```csharp
public List<TutorialData.TutorialNode> GetTutorialNodes()
```

#### Returns

**Type:** System.Collections.Generic.List{TutorialData.TutorialNode}

### Init(int, List<TutorialNode>)

```csharp
public void Init(int step, List<TutorialData.TutorialNode> nodes)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `step` | `System.Int32` |  |
| `nodes` | `System.Collections.Generic.List{TutorialData.TutorialNode}` |  |
