---
uid: Global.SkillTrigger
canonical_path: /api/Global/Misc/SkillTrigger
---

# Class SkillTrigger

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTrigger
```
Stores the event to call when called by [SkillTriggerCheck](/api/Global/Misc/SkillTriggerCheck).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTrigger

## Derived
[UseSkillTrigger](/api/Global/Misc/UseSkillTrigger)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkillTrigger()

```csharp
public SkillTrigger()
```

## Fields

### _ClearOnActivated

```csharp
public SkillTrigger.ClearEvent _ClearOnActivated
```

#### Field Value

**Type:** Global.SkillTrigger.ClearEvent

### _ClearOnFalse

```csharp
public SkillTrigger.ClearEvent _ClearOnFalse
```

#### Field Value

**Type:** Global.SkillTrigger.ClearEvent

### calledEvent

```csharp
public List<SkillTrigger.CalledEvent> calledEvent
```

#### Field Value

**Type:** System.Collections.Generic.List{SkillTrigger.CalledEvent}

### check

```csharp
public bool check
```
#INC


#### Field Value

**Type:** System.Boolean

### clearOnActivated

```csharp
public bool clearOnActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### clearOnFalse

```csharp
public bool clearOnFalse
```
#INC


#### Field Value

**Type:** System.Boolean

### commonClearEvent

```csharp
public List<SkillTrigger.CalledEvent> commonClearEvent
```

#### Field Value

**Type:** System.Collections.Generic.List{SkillTrigger.CalledEvent}

### currentCount

```csharp
public int currentCount
```
#INC


#### Field Value

**Type:** System.Int32

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### maxCount

```csharp
public int maxCount
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### Init()

```csharp
public virtual void Init()
```
#INC


### isActivated(object)

```csharp
public virtual bool isActivated(object checkedTarget)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `checkedTarget` | `System.Object` |  |

#### Returns

**Type:** System.Boolean

### OnSkillActivated()

```csharp
public virtual void OnSkillActivated()
```
#INC

