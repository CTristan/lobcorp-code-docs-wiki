# Class SpriteLoadScript.SefiraLinkedSprite

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteLoadScript.SefiraLinkedSprite
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteLoadScript.SefiraLinkedSprite

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SefiraLinkedSprite()

```csharp
public SefiraLinkedSprite()
```

## Fields

### list

```csharp
public List<SpriteLoadScript.SefiraLinkedSprite.TargetSefira> list
```

#### Field Value

**Type:** System.Collections.Generic.List{SpriteLoadScript.SefiraLinkedSprite.TargetSefira}

## Methods

### AddSefiraData(SefiraEnum, Sprite)

```csharp
public void AddSefiraData(SefiraEnum sefira, Sprite s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `s` | `UnityEngine.Sprite` |  |

### GetSprite(SefiraEnum)

```csharp
public Sprite GetSprite(SefiraEnum curret)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `curret` | `Global.SefiraEnum` |  |

#### Returns

**Type:** UnityEngine.Sprite
