---
uid: WorkerSprite.UniqueWeaponSpriteUnit
canonical_path: /api/WorkerSprite/UniqueWeaponSpriteUnit
---

# Class UniqueWeaponSpriteUnit

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UniqueWeaponSpriteUnit
```
Has a list of unique weapons?? Maybe??

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UniqueWeaponSpriteUnit

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UniqueWeaponSpriteUnit()

```csharp
public UniqueWeaponSpriteUnit()
```

## Fields

### _commonSprite

```csharp
[Header("May use Unique Sprite : likewise Inventory")]
[SerializeField]
private Sprite _commonSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### indexer

```csharp
public string indexer
```
#INC
#code-generated


#### Field Value

**Type:** System.String

### sprites

```csharp
public List<UniqueWeaponSprite> sprites
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.UniqueWeaponSprite}

## Properties

### CommonSprite

```csharp
public Sprite CommonSprite { get; }
```

#### Property Value

**Type:** UnityEngine.Sprite

## Methods

### GetCopy()

```csharp
public UniqueWeaponSpriteUnit GetCopy()
```

#### Returns

**Type:** WorkerSprite.UniqueWeaponSpriteUnit
