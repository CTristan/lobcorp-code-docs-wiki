# Class OfficerManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OfficerManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OfficerManager()

```csharp
public OfficerManager()
```

## Fields

### isLoadedActionList

```csharp
public bool isLoadedActionList
```

#### Field Value

**Type:** System.Boolean

### nameList

```csharp
public static string[] nameList
```

#### Field Value

**Type:** System.String[]

## Properties

### instance

```csharp
public static OfficerManager instance { get; }
```

#### Property Value

**Type:** Global.OfficerManager

## Methods

### Clear()

```csharp
public void Clear()
```

### ClearOfficer()

```csharp
public void ClearOfficer()
```

### CreateDebugOfficer()

```csharp
public OfficerModel CreateDebugOfficer()
```

#### Returns

**Type:** Global.OfficerModel

### CreateDebugOfficer(string)

```csharp
public OfficerModel CreateDebugOfficer(string nodeId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeId` | `System.String` |  |

#### Returns

**Type:** Global.OfficerModel

### CreateOfficerModel(string)

```csharp
public OfficerModel CreateOfficerModel(string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** Global.OfficerModel

### GetNearOfficers(MovableObjectNode)

```csharp
public OfficerModel[] GetNearOfficers(MovableObjectNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.OfficerModel[]

### GetOfficerList()

```csharp
public IList<OfficerModel> GetOfficerList()
```

#### Returns

**Type:** System.Collections.Generic.IList{OfficerModel}

### Init()

```csharp
public void Init()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```
