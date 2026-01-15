---
uid: Spine.Unity.MeshRendererBuffers
canonical_path: /api/Spine/Unity/MeshRendererBuffers
---

# Class MeshRendererBuffers

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshRendererBuffers : IDisposable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MeshRendererBuffers

## Implements
[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MeshRendererBuffers()

```csharp
public MeshRendererBuffers()
```

## Fields

### doubleBufferedMesh

```csharp
private DoubleBuffered<MeshRendererBuffers.SmartMesh> doubleBufferedMesh
```

#### Field Value

**Type:** Spine.Unity.DoubleBuffered{Spine.Unity.MeshRendererBuffers.SmartMesh}

### sharedMaterials

```csharp
internal Material[] sharedMaterials
```

#### Field Value

**Type:** UnityEngine.Material[]

### submeshMaterials

```csharp
internal readonly ExposedList<Material> submeshMaterials
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Material}

## Methods

### Clear()

```csharp
public void Clear()
```

### Dispose()

```csharp
public void Dispose()
```

### GetNextMesh()

```csharp
public MeshRendererBuffers.SmartMesh GetNextMesh()
```

#### Returns

**Type:** Spine.Unity.MeshRendererBuffers.SmartMesh

### GetUpdatedShaderdMaterialsArray()

```csharp
public Material[] GetUpdatedShaderdMaterialsArray()
```

#### Returns

**Type:** UnityEngine.Material[]

### Initialize()

```csharp
public void Initialize()
```

### MaterialsChangedInLastUpdate()

```csharp
public bool MaterialsChangedInLastUpdate()
```

#### Returns

**Type:** System.Boolean

### UpdateSharedMaterials(ExposedList<SubmeshInstruction>)

```csharp
public void UpdateSharedMaterials(ExposedList<SubmeshInstruction> instructions)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instructions` | `Spine.ExposedList{Spine.Unity.SubmeshInstruction}` |  |
