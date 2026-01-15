---
uid: Global.FallingLegEvent.SefiraManagement
canonical_path: /api/Global/Misc/FallingLegEventSefiraManagement
---

# Class FallingLegEvent.SefiraManagement

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FallingLegEvent.SefiraManagement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FallingLegEvent.SefiraManagement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraManagement()

```csharp
public SefiraManagement()
```

## Fields

### _sefira

```csharp
public string _sefira
```

#### Field Value

**Type:** System.String

### activated

```csharp
public bool activated
```

#### Field Value

**Type:** System.Boolean

### centerNode

```csharp
public MapNode centerNode
```

#### Field Value

**Type:** Global.MapNode

### isEnabled

```csharp
public bool isEnabled
```

#### Field Value

**Type:** System.Boolean

### Legs

```csharp
public List<ChopLeg> Legs
```

#### Field Value

**Type:** System.Collections.Generic.List{ChopLeg}

### passages

```csharp
public List<PassageObjectModel> passages
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### script

```csharp
public FallingLegEvent script
```

#### Field Value

**Type:** Global.FallingLegEvent

## Properties

### sefira

```csharp
public Sefira sefira { get; }
```

#### Property Value

**Type:** Global.Sefira

## Methods

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### Init(FallingLegEvent)

```csharp
public void Init(FallingLegEvent script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FallingLegEvent` |  |

### IsReadyForDisable()

```csharp
public bool IsReadyForDisable()
```

#### Returns

**Type:** System.Boolean

### SetActivate(bool)

```csharp
public void SetActivate(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
