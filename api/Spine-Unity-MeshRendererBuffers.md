# Class MeshRendererBuffers

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshRendererBuffers : IDisposable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MeshRendererBuffers

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MeshRendererBuffers()

```csharp
public MeshRendererBuffers()
```

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
