---
uid: Global.ResultScreen.Report.ClearedMissionBoard
canonical_path: /api/Global/Misc/ResultScreenReportClearedMissionBoard
---

# Class ResultScreen.Report.ClearedMissionBoard

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResultScreen.Report.ClearedMissionBoard
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResultScreen.Report.ClearedMissionBoard

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ClearedMissionBoard()

```csharp
public ClearedMissionBoard()
```

## Fields

### Arrow_Down

```csharp
public GameObject Arrow_Down
```

#### Field Value

**Type:** UnityEngine.GameObject

### Arrow_Up

```csharp
public GameObject Arrow_Up
```

#### Field Value

**Type:** UnityEngine.GameObject

### defaultX

```csharp
public float defaultX
```

#### Field Value

**Type:** System.Single

### defaultY

```csharp
public float defaultY
```

#### Field Value

**Type:** System.Single

### listParent

```csharp
public RectTransform listParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### missions

```csharp
private List<MissionSlot> missions
```

#### Field Value

**Type:** System.Collections.Generic.List{MissionSlot}

### scroll

```csharp
public ScrollRect scroll
```

#### Field Value

**Type:** UnityEngine.UI.ScrollRect

### scrollSpace

```csharp
private const float scrollSpace = 2
```

#### Field Value

**Type:** System.Single

### Spacing

```csharp
public Vector2 Spacing
```

#### Field Value

**Type:** UnityEngine.Vector2

## Properties

### scrollRect

```csharp
private RectTransform scrollRect { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

## Methods

### Make(List<Mission>)

```csharp
public void Make(List<Mission> cleared)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cleared` | `System.Collections.Generic.List{Mission}` |  |

### SetList()

```csharp
public void SetList()
```

### Update()

```csharp
public void Update()
```
