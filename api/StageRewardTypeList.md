# Class StageRewardTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageRewardTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageRewardTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static StageRewardTypeList instance { get; }
```

#### Property Value

**Type:** Global.StageRewardTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public StageRewardTypeInfo GetData(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** Global.StageRewardTypeInfo

### GetList()

```csharp
public StageRewardTypeInfo[] GetList()
```

#### Returns

**Type:** Global.StageRewardTypeInfo[]

### Init(StageRewardTypeInfo[])

```csharp
public void Init(StageRewardTypeInfo[] list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.StageRewardTypeInfo[]` |  |
