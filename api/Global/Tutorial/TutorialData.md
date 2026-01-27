---
uid: Global.TutorialData
canonical_path: /api/Global/Tutorial/TutorialData
---

# Class TutorialData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialData
```
Holds a tutorial, as a list of steps.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TutorialData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TutorialData()

```csharp
public TutorialData()
```

## Fields

### steps

```csharp
private List<TutorialData.TutorialStep> steps
```

#### Field Value

**Type:** System.Collections.Generic.List{TutorialData.TutorialStep}

## Methods

### GetTutorialByStep(int)

```csharp
public TutorialData.TutorialStep GetTutorialByStep(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.TutorialData.TutorialStep

### Init(List<TutorialStep>)

```csharp
public void Init(List<TutorialData.TutorialStep> steps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `steps` | `System.Collections.Generic.List{TutorialData.TutorialStep}` |  |
