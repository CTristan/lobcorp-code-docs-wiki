---
uid: Global.WorkerSpriteDataLoader
canonical_path: /api/Global/Loader/WorkerSpriteDataLoader
---

# Class WorkerSpriteDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpriteDataLoader
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpriteDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpriteDataLoader()

```csharp
private WorkerSpriteDataLoader()
```

## Fields

### _loader

```csharp
private static WorkerSpriteDataLoader _loader
```

#### Field Value

**Type:** Global.WorkerSpriteDataLoader

### basic

```csharp
public WorkerBasicSpriteController basic
```

#### Field Value

**Type:** WorkerSprite.WorkerBasicSpriteController

### colorLoaded

```csharp
public List<WorkerColorPreset> colorLoaded
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSpine.WorkerColorPreset}

### equip

```csharp
public WorkerEquipmentSpriteController equip
```

#### Field Value

**Type:** WorkerSprite.WorkerEquipmentSpriteController

## Properties

### Loader

```csharp
public static WorkerSpriteDataLoader Loader { get; }
```

#### Property Value

**Type:** Global.WorkerSpriteDataLoader

## Methods

### LoadBasicData()

```csharp
private void LoadBasicData()
```

### LoadColorPreset()

```csharp
private void LoadColorPreset()
```

### LoadEquipmentData()

```csharp
private void LoadEquipmentData()
```

### LoadnPrint()

```csharp
public void LoadnPrint()
```
