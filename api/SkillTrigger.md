# Class SkillTrigger

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTrigger
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTrigger

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.Boolean

### clearOnActivated

```csharp
public bool clearOnActivated
```

#### Field Value

**Type:** System.Boolean

### clearOnFalse

```csharp
public bool clearOnFalse
```

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

#### Field Value

**Type:** System.Int32

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

### maxCount

```csharp
public int maxCount
```

#### Field Value

**Type:** System.Int32

## Methods

### Init()

```csharp
public virtual void Init()
```

### isActivated(object)

```csharp
public virtual bool isActivated(object checkedTarget)
```

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
