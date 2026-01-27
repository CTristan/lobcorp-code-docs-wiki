---
uid: WorkerSprite.UniqueWeaponSprite
canonical_path: /api/WorkerSprite/UniqueWeaponSprite
---

# Class UniqueWeaponSprite

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UniqueWeaponSprite
```
Sprite and position for rendering unique weapons?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UniqueWeaponSprite

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UniqueWeaponSprite()

```csharp
public UniqueWeaponSprite()
```

## Fields

### portraitInfo

```csharp
[Header("On Portarit Rendererd")]
public UniqueWeaponSpritePortraitTransformInfo portraitInfo
```

#### Field Value

**Type:** WorkerSprite.UniqueWeaponSpritePortraitTransformInfo

### pos

```csharp
public UniqueWeaponPos pos
```
#INC


#### Field Value

**Type:** WorkerSprite.UniqueWeaponPos

### sprite

```csharp
public Sprite sprite
```
#INC
#code-generated


#### Field Value

**Type:** UnityEngine.Sprite

## Methods

### GetCopy()

```csharp
public UniqueWeaponSprite GetCopy()
```

#### Returns

**Type:** WorkerSprite.UniqueWeaponSprite
