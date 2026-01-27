---
uid: WorkerSprite.WorkerSprite_WorkerSpriteManager
canonical_path: /api/WorkerSprite/WorkerSprite_WorkerSpriteManager
---

# Class WorkerSprite_WorkerSpriteManager

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSprite_WorkerSpriteManager
```
Holds sprite data for workers and allows getting clothes sets and other things maybe i dont know

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSprite_WorkerSpriteManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSprite_WorkerSpriteManager()

```csharp
private WorkerSprite_WorkerSpriteManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static WorkerSprite_WorkerSpriteManager _instance
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerSprite_WorkerSpriteManager

### basicData

```csharp
public WorkerBasicSpriteController basicData
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerBasicSpriteController

### equipData

```csharp
public WorkerEquipmentSpriteController equipData
```
#INC


#### Field Value

**Type:** WorkerSprite.WorkerEquipmentSpriteController

## Properties

### instance

```csharp
public static WorkerSprite_WorkerSpriteManager instance { get; }
```

#### Property Value

**Type:** WorkerSprite.WorkerSprite_WorkerSpriteManager

## Methods

### GetClothesSet(int)

```csharp
public SpriteResourceLoadData GetClothesSet(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### GetFistSprite()

```csharp
public Sprite[] GetFistSprite()
```
#INC


#### Returns

**Type:** UnityEngine.Sprite[]

### GetFistSprite(int)

```csharp
public Sprite[] GetFistSprite(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite[]

### GetRandomWeaponSprite(WeaponClassType)

```csharp
public Sprite GetRandomWeaponSprite(WeaponClassType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.WeaponClassType` |  |

#### Returns

**Type:** UnityEngine.Sprite

### LoadCommand()

```csharp
public void LoadCommand()
```
#INC


### Print()

```csharp
public void Print()
```
#INC


### SetBasicData(WorkerBasicSpriteController)

```csharp
public void SetBasicData(WorkerBasicSpriteController d)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d` | `WorkerSprite.WorkerBasicSpriteController` |  |

### SetEquipmentData(WorkerEquipmentSpriteController)

```csharp
public void SetEquipmentData(WorkerEquipmentSpriteController d)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d` | `WorkerSprite.WorkerEquipmentSpriteController` |  |
