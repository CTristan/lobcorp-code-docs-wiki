# Class TutorialManager

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TutorialManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TutorialManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TutorialManager()

```csharp
public TutorialManager()
```

## Fields

### manage

```csharp
public List<TutorialNode> manage
```

#### Field Value

**Type:** System.Collections.Generic.List{Legacy.TutorialNode}

### ui

```csharp
public List<TutorialNode> ui
```

#### Field Value

**Type:** System.Collections.Generic.List{Legacy.TutorialNode}

## Properties

### instance

```csharp
public static TutorialManager instance { get; }
```

#### Property Value

**Type:** Legacy.TutorialManager

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Init(TutorialNode[], TutorialNode[])

```csharp
public void Init(TutorialNode[] ui, TutorialNode[] manage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ui` | `Legacy.TutorialNode[]` |  |
| `manage` | `Legacy.TutorialNode[]` |  |
