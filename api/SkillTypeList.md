# Class SkillTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static SkillTypeList instance { get; }
```

#### Property Value

**Type:** Global.SkillTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public SkillTypeInfo GetData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### GetDataByName(string)

```csharp
public SkillTypeInfo GetDataByName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### GetList()

```csharp
public SkillTypeInfo[] GetList()
```

#### Returns

**Type:** Global.SkillTypeInfo[]

### GetNextSkill(SkillTypeInfo)

```csharp
public SkillTypeInfo GetNextSkill(SkillTypeInfo typeInfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `typeInfo` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** Global.SkillTypeInfo

### Init(SkillTypeInfo[])

```csharp
public void Init(SkillTypeInfo[] list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.SkillTypeInfo[]` |  |
