---
uid: Global.EffectInfo
canonical_path: /api/Global/Info/EffectInfo
---

# Class EffectInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EffectInfo
```
Has information about a damage effect and provides static methods to invoke the effect.

Used by [DamageInfo](/api/Global/Info/DamageInfo) and [WeaponModel](/api/Global/Model/WeaponModel)s.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EffectInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EffectInfo()

```csharp
public EffectInfo()
```

## Fields

### EffectPrefix

```csharp
public const string EffectPrefix = "DamageInfo/"
```
#INC


#### Field Value

**Type:** System.String

### effectSrc

```csharp
public string effectSrc
```
#INC


#### Field Value

**Type:** System.String

### effectType

```csharp
public DamageInfo_EffectType effectType
```
#INC


#### Field Value

**Type:** Global.DamageInfo_EffectType

### invokedUnit

```csharp
public EffectInvokedUnit invokedUnit
```
#INC


#### Field Value

**Type:** Global.EffectInvokedUnit

### invokeOnce

```csharp
public bool invokeOnce
```
#INC


#### Field Value

**Type:** System.Boolean

### lifetime

```csharp
public float lifetime
```
#INC


#### Field Value

**Type:** System.Single

### relativePosition

```csharp
public Vector3 relativePosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### rotation

```csharp
public float rotation
```
#INC


#### Field Value

**Type:** System.Single

### unscaled

```csharp
public bool unscaled
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### MakeEffect(EffectInfo, MovableObjectNode)

```csharp
public static EffectInvoker MakeEffect(EffectInfo info, MovableObjectNode mov)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EffectInfo` |  |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.EffectInvoker

### MakeEffect(MovableObjectNode)

```csharp
public EffectInvoker MakeEffect(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.EffectInvoker
