---
uid: Global.SpiderMomChildMovementControl.ChildObject
canonical_path: /api/Global/Object/SpiderMomChildMovementControlChildObject
---

# Class SpiderMomChildMovementControl.ChildObject

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpiderMomChildMovementControl.ChildObject
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpiderMomChildMovementControl.ChildObject

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChildObject()

```csharp
public ChildObject()
```

## Fields

### mother

```csharp
public SpiderMomChildMovementControl mother
```

#### Field Value

**Type:** Global.SpiderMomChildMovementControl

### moveTargetVector

```csharp
public Vector2 moveTargetVector
```

#### Field Value

**Type:** UnityEngine.Vector2

### range

```csharp
private const float range = 0.05
```

#### Field Value

**Type:** System.Single

### startVector

```csharp
public Vector2 startVector
```

#### Field Value

**Type:** UnityEngine.Vector2

### target

```csharp
public GameObject target
```

#### Field Value

**Type:** UnityEngine.GameObject

## Methods

### CheckArrive()

```csharp
private bool CheckArrive()
```

#### Returns

**Type:** System.Boolean

### GenVector()

```csharp
private Vector3 GenVector()
```

#### Returns

**Type:** UnityEngine.Vector3

### Update()

```csharp
public void Update()
```
