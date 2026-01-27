---
uid: CommandWindow.CommandWindowRegion
canonical_path: /api/CommandWindow/CommandWindowRegion
---

# Class CommandWindowRegion

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CommandWindowRegion
```
Parent class for command regions

#parent


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CommandWindowRegion

## Derived
[CreatureSuppressRegion](/api/CommandWindow/CreatureSuppressRegion), [KitCreatureRegion](/api/CommandWindow/KitCreatureRegion), [WorkAllocateRegion](/api/CommandWindow/WorkAllocateRegion), [WorkerSuppressRegion](/api/CommandWindow/WorkerSuppressRegion)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CommandWindowRegion()

```csharp
public CommandWindowRegion()
```

## Fields

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### TargetImage

```csharp
public Image TargetImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### TargetName

```csharp
public Text TargetName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### SetData(UnitModel)

```csharp
public virtual void SetData(UnitModel target)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
