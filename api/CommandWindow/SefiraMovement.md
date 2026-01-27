---
uid: CommandWindow.SefiraMovement
canonical_path: /api/CommandWindow/SefiraMovement
---

# Class SefiraMovement

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraMovement
```
UI element for showing and changing the department in the management and suppression windows.

Used by [CommandWindow](/api/CommandWindow)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraMovement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraMovement()

```csharp
public SefiraMovement()
```

## Fields

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### AreaName

```csharp
public Text AreaName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### FrameControl

```csharp
public Image FrameControl
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### LeftArrow

```csharp
public Image LeftArrow
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Max

```csharp
private int Max
```
#INC


#### Field Value

**Type:** System.Int32

### Opened

```csharp
private List<SefiraEnum> Opened
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraEnum}

### RightArrow

```csharp
public Image RightArrow
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### SefiraColor

```csharp
public List<Image> SefiraColor
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Image}

## Methods

### AreaInit()

```csharp
public void AreaInit()
```
#INC


### CheckContains(SefiraEnum)

```csharp
public bool CheckContains(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### MoveNextSefira(SefiraEnum, out SefiraEnum)

```csharp
public bool MoveNextSefira(SefiraEnum current, out SefiraEnum moved)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
| `moved` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### MovePrevSefira(SefiraEnum, out SefiraEnum)

```csharp
public bool MovePrevSefira(SefiraEnum current, out SefiraEnum moved)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
| `moved` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### SetCurrentSefira(SefiraEnum)

```csharp
public void SetCurrentSefira(SefiraEnum current)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |
