---
uid: Global.ArmorCreature.StackAgent
canonical_path: /api/Global/Misc/ArmorCreatureStackAgent
---

# Class ArmorCreature.StackAgent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class ArmorCreature.StackAgent
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ArmorCreature.StackAgent

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StackAgent()

```csharp
public StackAgent()
```

## Properties

### agent

```csharp
public AgentModel agent { get; set; }
```

#### Property Value

**Type:** Global.AgentModel

### gift

```csharp
public EGOgiftModel gift { get; set; }
```

#### Property Value

**Type:** Global.EGOgiftModel

### state

```csharp
public ArmorCreature.GiftState state { get; set; }
```

#### Property Value

**Type:** Global.ArmorCreature.GiftState

## Methods

### SetFire(EGOgiftModel, GiftState)

```csharp
public void SetFire(EGOgiftModel g, ArmorCreature.GiftState s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `g` | `Global.EGOgiftModel` |  |
| `s` | `Global.ArmorCreature.GiftState` |  |
