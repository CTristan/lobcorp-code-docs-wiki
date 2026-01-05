# Class SpriteResourceLoadData

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteResourceLoadData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteResourceLoadData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SpriteResourceLoadData()

```csharp
public SpriteResourceLoadData()
```

## Fields

### count

```csharp
public int count
```

#### Field Value

**Type:** System.Int32

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### isCredit

```csharp
public bool isCredit
```

#### Field Value

**Type:** System.Boolean

### isCustom

```csharp
public bool isCustom
```

#### Field Value

**Type:** System.Boolean

### src

```csharp
public string src
```

#### Field Value

**Type:** System.String

### type

```csharp
public SpriteResourceType type
```

#### Field Value

**Type:** WorkerSprite.SpriteResourceType

## Methods

### GetRandomSprite()

```csharp
public virtual Sprite GetRandomSprite()
```

#### Returns

**Type:** UnityEngine.Sprite

### GetSprite(int)

```csharp
public virtual Sprite GetSprite(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite

### LoadSprite()

```csharp
public virtual void LoadSprite()
```
