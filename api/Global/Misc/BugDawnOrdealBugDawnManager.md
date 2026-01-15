---
uid: Global.BugDawnOrdeal.BugDawnManager
canonical_path: /api/Global/Misc/BugDawnOrdealBugDawnManager
---

# Class BugDawnOrdeal.BugDawnManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugDawnOrdeal.BugDawnManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BugDawnOrdeal.BugDawnManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugDawnManager(BugDawnOrdeal)

```csharp
public BugDawnManager(BugDawnOrdeal script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BugDawnOrdeal` |  |

## Fields

### _teleportTimeMax

```csharp
private const float _teleportTimeMax = 60
```

#### Field Value

**Type:** System.Single

### _teleportTimeMin

```csharp
private const float _teleportTimeMin = 40
```

#### Field Value

**Type:** System.Single

### bugs

```csharp
private List<BugDawn> bugs
```

#### Field Value

**Type:** System.Collections.Generic.List{BugDawn}

### isAvailable

```csharp
private bool isAvailable
```

#### Field Value

**Type:** System.Boolean

### script

```csharp
private BugDawnOrdeal script
```

#### Field Value

**Type:** Global.BugDawnOrdeal

### teleportTimer

```csharp
private Timer teleportTimer
```

#### Field Value

**Type:** Global.Timer

## Properties

### teleportTime

```csharp
private static float teleportTime { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AddCreature(BugDawn)

```csharp
public void AddCreature(BugDawn bug)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bug` | `Global.BugDawn` |  |

### CheckAvailable()

```csharp
private bool CheckAvailable()
```

#### Returns

**Type:** System.Boolean

### IsAvailable()

```csharp
public bool IsAvailable()
```

#### Returns

**Type:** System.Boolean

### ReadyToTeleport()

```csharp
private void ReadyToTeleport()
```

### Run()

```csharp
public void Run()
```
