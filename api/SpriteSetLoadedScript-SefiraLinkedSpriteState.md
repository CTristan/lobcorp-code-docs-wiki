# Class SpriteSetLoadedScript.SefiraLinkedSpriteState

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteSetLoadedScript.SefiraLinkedSpriteState
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteSetLoadedScript.SefiraLinkedSpriteState

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SefiraLinkedSpriteState()

```csharp
public SefiraLinkedSpriteState()
```

## Fields

### list

```csharp
public List<SpriteSetLoadedScript.SefiraLinkedSpriteState.TargetSefiraSpriteSet> list
```

#### Field Value

**Type:** System.Collections.Generic.List{SpriteSetLoadedScript.SefiraLinkedSpriteState.TargetSefiraSpriteSet}

## Methods

### AddSefiraData(SefiraEnum, Sprite, Sprite, Sprite)

```csharp
public void AddSefiraData(SefiraEnum sefira, Sprite norm, Sprite over, Sprite disable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `norm` | `UnityEngine.Sprite` |  |
| `over` | `UnityEngine.Sprite` |  |
| `disable` | `UnityEngine.Sprite` |  |

### GetSpriteSet(SefiraEnum)

```csharp
public SpriteSetLoadedScript.SefiraLinkedSpriteState.TargetSefiraSpriteSet GetSpriteSet(SefiraEnum current)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.SpriteSetLoadedScript.SefiraLinkedSpriteState.TargetSefiraSpriteSet
