---
uid: Global.SilentOrchestraAnim.Singer
canonical_path: /api/Global/Misc/SilentOrchestraAnimSinger
---

# Class SilentOrchestraAnim.Singer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim.Singer
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SilentOrchestraAnim.Singer

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Singer()

```csharp
public Singer()
```

## Fields

### appearAnimator

```csharp
public Animator appearAnimator
```

#### Field Value

**Type:** UnityEngine.Animator

### appearMask

```csharp
public Image appearMask
```

#### Field Value

**Type:** UnityEngine.UI.Image

### singer

```csharp
public GameObject singer
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### singerAnim

```csharp
public Animator singerAnim { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### Appear(float)

```csharp
public void Appear(float appearTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `appearTime` | `System.Single` |  |

### Init()

```csharp
public void Init()
```

### OnEndAppear()

```csharp
public void OnEndAppear()
```
