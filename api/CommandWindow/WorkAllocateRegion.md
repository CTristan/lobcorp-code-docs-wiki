---
uid: CommandWindow.WorkAllocateRegion
canonical_path: /api/CommandWindow/WorkAllocateRegion
---

# Class WorkAllocateRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkAllocateRegion : CommandWindowRegion
```

UI element (actually, more like data for one...) for work assignment region and abnormality information (i.e., name, portrait, number, grade, max boxes, outcome ranges, work damage).

See also [CommandWindow](/api/CommandWindow)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CommandWindowRegion](/api/CommandWindow/CommandWindowRegion) → WorkAllocateRegion

## Inherited Members
[ActiveControl](/api/CommandWindow/CommandWindowRegion#activecontrol), [TargetImage](/api/CommandWindow/CommandWindowRegion#targetimage), [TargetName](/api/CommandWindow/CommandWindowRegion#targetname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkAllocateRegion()

```csharp
public WorkAllocateRegion()
```

## Fields

### _currentModel

```csharp
private CreatureModel _currentModel
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### CodeNo

```csharp
public Text CodeNo
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### listParent

```csharp
public RectTransform listParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### MaximumCubeGenerate

```csharp
public Text MaximumCubeGenerate
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Name

```csharp
public Text Name
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Portrait

```csharp
public Image Portrait
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### RiskLevel

```csharp
public Text RiskLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### slots

```csharp
public List<CreatureInfoStatFeelingStateSlot> slots
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureInfo.CreatureInfoStatFeelingStateSlot}

### unknown

```csharp
private static string unknown
```
#INC


#### Field Value

**Type:** System.String

### unknown_Text

```csharp
private static string unknown_Text
```
#INC


#### Field Value

**Type:** System.String

### WorkDamageFill

```csharp
public Image WorkDamageFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### WorkDamageRange

```csharp
public Text WorkDamageRange
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WorkDamageType

```csharp
public Text WorkDamageType
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### CurrentModel

```csharp
public CreatureModel CurrentModel { get; }
```

#### Property Value

**Type:** Global.CreatureModel

## Methods

### NonObserved(CreatureModel)

```csharp
private void NonObserved(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnObserved(CreatureModel)

```csharp
private void OnObserved(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### SetData(UnitModel)

```csharp
public override void SetData(UnitModel target)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
