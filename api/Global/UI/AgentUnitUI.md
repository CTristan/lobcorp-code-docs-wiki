---
uid: Global.AgentUnitUI
canonical_path: /api/Global/UI/AgentUnitUI
---

# Class AgentUnitUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentUnitUI
```
UI element which displays the agent's name, rank, title, department, and tool status before Yesod's upgrade.

See [AgentUI](/api/InGameUI/AgentUI) for after Yesod's upgrade.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentUnitUI

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentUnitUI()

```csharp
public AgentUnitUI()
```

## Fields

### Activated

```csharp
public bool Activated
```
#INC


#### Field Value

**Type:** System.Boolean

### kitCreatureIcon

```csharp
public Image kitCreatureIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Name

```csharp
public Text Name
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### title

```csharp
public Text title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### activateUI(AgentModel)

```csharp
public void activateUI(AgentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

### DeactivateAllUI()

```csharp
public void DeactivateAllUI()
```
#INC


### Initial(AgentModel)

```csharp
public void Initial(AgentModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

### initUI()

```csharp
public void initUI()
```
#INC


### setUIValue(AgentModel)

```csharp
public void setUIValue(AgentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |
