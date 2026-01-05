# Class CharacterResourceDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CharacterResourceDataModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CharacterResourceDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static CharacterResourceDataModel instance { get; }
```

#### Property Value

**Type:** Global.CharacterResourceDataModel

## Methods

### GetColor(string)

```csharp
public Color GetColor(string character)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Color

### GetName(string)

```csharp
public string GetName(string character)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** System.String

### GetPortrait(string)

```csharp
public Sprite GetPortrait(string character)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetSefiraPortrait(SefiraEnum, bool)

```csharp
public Sprite GetSefiraPortrait(SefiraEnum sefiraEnum, bool tipherethException = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |
| `tipherethException` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetSpine(string)

```csharp
public GameObject GetSpine(string character)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `character` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject
