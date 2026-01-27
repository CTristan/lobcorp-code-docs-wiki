---
uid: Global.TransitionEffect
canonical_path: /api/Global/Effect/TransitionEffect
---

# Class TransitionEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TransitionEffect
```
#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TransitionEffect

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TransitionEffect()

```csharp
public TransitionEffect()
```

## Fields

### _isBigger

```csharp
private bool _isBigger
```
#INC


#### Field Value

**Type:** System.Boolean

### bicScale

```csharp
public float bicScale
```
#INC


#### Field Value

**Type:** System.Single

### smallScale

```csharp
public float smallScale
```
#INC


#### Field Value

**Type:** System.Single

### TransitionCurve

```csharp
public AnimationCurve TransitionCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### TransitionTime

```csharp
public float TransitionTime
```
#INC


#### Field Value

**Type:** System.Single

### TransitionTimer

```csharp
public Timer TransitionTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Properties

### IsBigger

```csharp
public bool IsBigger { get; private set; }
```

#### Property Value

**Type:** System.Boolean

### IsTrans

```csharp
public bool IsTrans { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### StartTransition(bool)

```csharp
public void StartTransition(bool isBigger)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isBigger` | `System.Boolean` |  |

### Update()

```csharp
public void Update()
```
#INC

