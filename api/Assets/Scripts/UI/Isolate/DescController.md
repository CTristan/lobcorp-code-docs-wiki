---
uid: Assets.Scripts.UI.Isolate.DescController
canonical_path: /api/Assets/Scripts/UI/Isolate/DescController
---

# Class DescController

**Namespace:** Assets . Scripts . UI . [Isolate](/api/Assets/Scripts/UI/Isolate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DescController
```
Controller for one side of the containment unit, for displaying [IsolateDescription](/api/Assets/Scripts/UI/Isolate/IsolateDescription)s.

See also [IsolateDescManager](/api/Global/Misc/IsolateDescManager).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DescController

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DescController()

```csharp
public DescController()
```

## Fields

### ctrl

```csharp
private IsolateDescController ctrl
```
#INC


#### Field Value

**Type:** Assets.Scripts.UI.Isolate.IsolateDescController

### descList

```csharp
public List<IsolateDescription> descList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Assets.Scripts.UI.Isolate.IsolateDescription}

### disabled

```csharp
private List<IsolateDescription> disabled
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Assets.Scripts.UI.Isolate.IsolateDescription}

### enabled

```csharp
private List<IsolateDescription> enabled
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Assets.Scripts.UI.Isolate.IsolateDescription}

### maxmimumFont

```csharp
public int maxmimumFont
```
#INC


#### Field Value

**Type:** System.Int32

### minimumFont

```csharp
public int minimumFont
```
#INC


#### Field Value

**Type:** System.Int32

### minimumSpacing

```csharp
public float minimumSpacing
```
#INC


#### Field Value

**Type:** System.Single

### pivot

```csharp
public RectTransform pivot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

## Properties

### IsAvailable

```csharp
public bool IsAvailable { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Init(IsolateDescController)

```csharp
public void Init(IsolateDescController ctrl)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctrl` | `Assets.Scripts.UI.Isolate.IsolateDescController` |  |

### OnDisplay(string, int)

```csharp
public void OnDisplay(string str, int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |
| `id` | `System.Int32` |  |

### OnDisplayEnd(IsolateDescription)

```csharp
public void OnDisplayEnd(IsolateDescription i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Assets.Scripts.UI.Isolate.IsolateDescription` |  |

### Terminal()

```csharp
public void Terminal()
```
#INC
#code-generated

