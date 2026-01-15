---
uid: Global.ReverseClockAnim.ClockLamp
canonical_path: /api/Global/Misc/ReverseClockAnimClockLamp
---

# Class ReverseClockAnim.ClockLamp

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ReverseClockAnim.ClockLamp
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ReverseClockAnim.ClockLamp

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ClockLamp()

```csharp
public ClockLamp()
```

## Fields

### isActivated

```csharp
public bool isActivated
```

#### Field Value

**Type:** System.Boolean

### lamp

```csharp
[SpineSlot("", "", false, true)]
public string[] lamp
```

#### Field Value

**Type:** System.String[]

### lampAttach

```csharp
[SpineAttachment(true, false, false, "", "", "", true)]
public string[] lampAttach
```

#### Field Value

**Type:** System.String[]

### number

```csharp
public SpriteRenderer number
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### particleObj

```csharp
public GameObject particleObj
```

#### Field Value

**Type:** UnityEngine.GameObject

## Methods

### TurnOff(SkeletonAnimator)

```csharp
public void TurnOff(SkeletonAnimator skel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skel` | `Spine.Unity.SkeletonAnimator` |  |

### TurnOn(SkeletonAnimator, Sprite)

```csharp
public void TurnOn(SkeletonAnimator skel, Sprite s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skel` | `Spine.Unity.SkeletonAnimator` |  |
| `s` | `UnityEngine.Sprite` |  |
