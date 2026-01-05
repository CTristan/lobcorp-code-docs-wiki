# Class CreditManager

**Namespace:** [Credit](/api/Credit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreditManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreditManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreditManager()

```csharp
public CreditManager()
```

## Fields

### LastText

```csharp
public string LastText
```

#### Field Value

**Type:** System.String

### list

```csharp
public List<CreditSection> list
```

#### Field Value

**Type:** System.Collections.Generic.List{Credit.CreditSection}

## Properties

### instance

```csharp
public static CreditManager instance { get; }
```

#### Property Value

**Type:** Credit.CreditManager

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Init(List<CreditSection>)

```csharp
public void Init(List<CreditSection> c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `System.Collections.Generic.List{Credit.CreditSection}` |  |
