---
uid: Global.SefiraPanel.SefiraPanelButton
canonical_path: /api/Global/Misc/SefiraPanelSefiraPanelButton
---

# Class SefiraPanel.SefiraPanelButton

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraPanel.SefiraPanelButton
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SefiraPanel.SefiraPanelButton

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraPanelButton()

```csharp
public SefiraPanelButton()
```

## Fields

### Disabled

```csharp
public Image Disabled
```

#### Field Value

**Type:** UnityEngine.UI.Image

### fadeIn

```csharp
private bool fadeIn
```

#### Field Value

**Type:** System.Boolean

### isEnabled

```csharp
public bool isEnabled
```

#### Field Value

**Type:** System.Boolean

### Overlay

```csharp
public Image Overlay
```

#### Field Value

**Type:** UnityEngine.UI.Image

### startRate

```csharp
private float startRate
```

#### Field Value

**Type:** System.Single

### transitionTime

```csharp
public float transitionTime
```

#### Field Value

**Type:** System.Single

### transTimer

```csharp
private UnscaledTimer transTimer
```

#### Field Value

**Type:** Global.UnscaledTimer

## Methods

### Init()

```csharp
public void Init()
```

### OnEnter()

```csharp
public void OnEnter()
```

### OnExit()

```csharp
public void OnExit()
```

### SetColor(float)

```csharp
private void SetColor(float rate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

### Update()

```csharp
public void Update()
```
