---
uid: Global.DeployAgentList.SortUI
canonical_path: /api/Global/UI/DeployAgentListSortUI
---

# Class DeployAgentList.SortUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployAgentList.SortUI
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeployAgentList.SortUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SortUI()

```csharp
public SortUI()
```

## Fields

### _genderText

```csharp
private string _genderText
```

#### Field Value

**Type:** System.String

### _gradeText

```csharp
private string _gradeText
```

#### Field Value

**Type:** System.String

### _lifeStyleText

```csharp
private string _lifeStyleText
```

#### Field Value

**Type:** System.String

### currentType

```csharp
public PersonalityType currentType
```

#### Field Value

**Type:** Global.PersonalityType

### down

```csharp
public Sprite down
```

#### Field Value

**Type:** UnityEngine.Sprite

### GenderButton

```csharp
public Button GenderButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### GenderImage

```csharp
public Image GenderImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### GenderText

```csharp
public Text GenderText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Grade_Arrow

```csharp
public Image Grade_Arrow
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LifeValue

```csharp
public Text LifeValue
```

#### Field Value

**Type:** UnityEngine.UI.Text

### PersonalityTypeButton

```csharp
public Button PersonalityTypeButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### up

```csharp
public Sprite up
```

#### Field Value

**Type:** UnityEngine.Sprite

## Methods

### GetLifeStyleText(PersonalityType)

```csharp
public string GetLifeStyleText(PersonalityType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.PersonalityType` |  |

#### Returns

**Type:** System.String

### Init()

```csharp
private void Init()
```

### SetSortData(AgentSortData)

```csharp
public void SetSortData(DeployAgentList.AgentSortData sortData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sortData` | `Global.DeployAgentList.AgentSortData` |  |
