# Class Category

**Namespace:** [Manual](/api/Manual)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Category
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Category

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Category(string)

```csharp
public Category(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

## Fields

### id

```csharp
public string id
```

#### Field Value

**Type:** System.String

### next

```csharp
public Category next
```

#### Field Value

**Type:** Manual.Category

### parent

```csharp
public Category parent
```

#### Field Value

**Type:** Manual.Category

### prev

```csharp
public Category prev
```

#### Field Value

**Type:** Manual.Category

### title

```csharp
protected string title
```

#### Field Value

**Type:** System.String

## Properties

### Title

```csharp
public virtual string Title { get; }
```

#### Property Value

**Type:** System.String

## Methods

### LoadText()

```csharp
public virtual void LoadText()
```

### Reload()

```csharp
public void Reload()
```
