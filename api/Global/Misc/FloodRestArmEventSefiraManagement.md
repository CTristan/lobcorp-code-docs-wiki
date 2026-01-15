---
uid: Global.FloodRestArmEvent.SefiraManagement
canonical_path: /api/Global/Misc/FloodRestArmEventSefiraManagement
---

# Class FloodRestArmEvent.SefiraManagement

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FloodRestArmEvent.SefiraManagement
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FloodRestArmEvent.SefiraManagement

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraManagement()

```csharp
public SefiraManagement()
```

## Fields

### activated

```csharp
public bool activated
```

#### Field Value

**Type:** System.Boolean

### currentEnabledCount

```csharp
public int currentEnabledCount
```

#### Field Value

**Type:** System.Int32

### list

```csharp
public List<FloodTentacle> list
```

#### Field Value

**Type:** System.Collections.Generic.List{FloodTentacle}

### RootEffect

```csharp
public GameObject RootEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### rootTentacle

```csharp
public FloodTentacle rootTentacle
```

#### Field Value

**Type:** Global.FloodTentacle

### sefira

```csharp
public string sefira
```

#### Field Value

**Type:** System.String

### usedNode

```csharp
public Dictionary<int, MapNode> usedNode
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,MapNode}

## Methods

### DeleteNode(int)

```csharp
public void DeleteNode(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### DisableTentacle(FloodTentacle)

```csharp
public bool DisableTentacle(FloodTentacle target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.FloodTentacle` |  |

#### Returns

**Type:** System.Boolean

### EnableTentacle(int, MapNode)

```csharp
public bool EnableTentacle(int count, MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** System.Boolean

### GetIndex(FloodTentacle)

```csharp
public int GetIndex(FloodTentacle script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FloodTentacle` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
public void Init()
```

### IsUsedNode(MapNode)

```csharp
public bool IsUsedNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** System.Boolean

### KillAll()

```csharp
public void KillAll()
```
